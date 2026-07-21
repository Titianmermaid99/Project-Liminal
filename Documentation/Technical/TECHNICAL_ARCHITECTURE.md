# PROJECT LIMINAL — TECHNICAL ARCHITECTURE

**Status:** Initial Planning

---

## Engine

Unity 6000.3.20f1

---

## Target Platforms

- Meta Quest 2
- Meta Quest 3

---

## Development Tools

- Unity Hub
- Unity
- Visual Studio Code
- Codex
- Git
- GitHub Desktop
- GitHub

---

## Multiplayer

The networking solution has not yet been selected.

The networking architecture must support:

- Multiplayer exploration.
- Host-generated shared worlds.
- Public lobbies.
- Private lobbies accessed through codes.
- Quest 2 and Quest 3 compatibility.

---

## Procedural Generation

The world will use procedural generation to create a network of connected spaces.

The host should be responsible for generating authoritative shared world state.

---

## VR Interaction

Interactions should favour physical VR interaction wherever practical.

### XR Player and Locomotion

The canonical Player uses a single PlayerRoot containing Unity's `XROrigin` and `CharacterController`.

Locomotion uses XR Interaction Toolkit components:

- `LocomotionMediator`
- `XRBodyTransformer`
- `GravityProvider`
- `ContinuousMoveProvider`
- `ContinuousTurnProvider`

Movement is head-relative and bound to the left controller thumbstick. Continuous turning is bound to the right controller thumbstick. The XRI body transformer and CharacterController body manipulator own collision-constrained movement and headset-relative capsule alignment.

Teleportation, snap turning, jumping, flying, and custom movement physics are excluded from the current foundation. Continuous turn speed uses the approved Project Liminal default of 45°/second and remains editable through the serialized XRI provider configuration. Movement speed retains its Unity default until Quest device testing.

---

## Performance

The game must be designed for standalone Meta Quest hardware from the beginning.

Performance considerations must influence:

- Rendering.
- Lighting.
- Textures.
- Shaders.
- Procedural generation.
- Networking.
- Memory usage.
