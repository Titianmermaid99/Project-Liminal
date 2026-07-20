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