# APPROVED DECISIONS

**Project:** Project Liminal  
**Document Owner:** Creative Director & Technical Lead  
**Status:** Living  
**Version:** 1.0  
**Last Updated:** YYYY-MM-DD

---

# Purpose

This document records every major decision that has been formally approved during the development of Project Liminal.

Once a decision is approved, it becomes part of the project's official direction until it is deliberately amended or replaced.

This document is a historical record and should not contain proposals or discussions.

---

# Decision Categories

🎨 Design

Gameplay, mechanics, atmosphere, progression, story and player experience.

🛠 Technical

Architecture, Unity implementation, XR, networking, optimisation and engineering.

📋 Workflow

Documentation, sprint process, repository organisation and development practices.

---

# Approved Decisions

---

## PD-001 — Project Identity

**Category:** 🎨 Design

**Status:** Approved

Project Name:

Project Liminal

---

## PD-002 — Genre

**Category:** 🎨 Design

**Status:** Approved

Project Liminal is a cooperative psychological horror exploration game built exclusively for virtual reality.

---

## PD-003 — Primary Platform

**Category:** 🛠 Technical

**Status:** Approved

Primary platform:

- Meta Quest 2
- Meta Quest 3

Quest 2 serves as the minimum performance target.

---

## PD-004 — Development Roles

**Category:** 📋 Workflow

**Status:** Approved

Creative Director

- Defines the creative vision.
- Approves project decisions.

Technical Lead

- Responsible for technical architecture.
- Protects long-term project health.
- Reviews implementation plans.

Developer (Codex)

- Implements approved work.
- Follows technical documentation.
- Does not make major design decisions independently.

---

## PD-005 — Development Workflow

**Category:** 📋 Workflow

**Status:** Approved

Every implementation follows this process:

1. Discuss sprint.
2. Approve sprint.
3. Planning prompt.
4. Planning review.
5. Implementation prompt.
6. Codex implementation.
7. Playtesting.
8. Review.
9. Documentation update.
10. Commit.

---

## PD-006 — VR Interaction Philosophy

**Category:** 🎨 Design

**Status:** Approved

Project Liminal prioritises physical interaction.

Players perform actions naturally rather than relying on traditional button-based interactions wherever practical.

---

## PD-007 — Inventory Philosophy

**Category:** 🎨 Design

**Status:** Approved

Inventory is physical.

Players use their hands, body slots and backpack instead of abstract inventory menus.

---

## PD-008 — Horror Philosophy

**Category:** 🎨 Design

**Status:** Approved

Psychological horror is prioritised over frequent jump scares.

Fear should emerge from uncertainty, atmosphere and player imagination.

---

## PD-009 — Multiplayer Philosophy

**Category:** 🎨 Design

**Status:** Approved

Project Liminal is designed around cooperative multiplayer.

Networking will be implemented after the single-player technical foundation is complete.

---

## PD-010 — XR Foundation

**Category:** 🛠 Technical

**Status:** Approved

The project will use:

- OpenXR
- XR Interaction Toolkit
- Unity Input System

Controller-based interaction only.

Teleport locomotion is excluded.

Hand tracking is excluded.

---

## PD-011 — Documentation Philosophy

**Category:** 📋 Workflow

**Status:** Approved

Project documentation is the authoritative source of truth.

Documentation takes precedence over conversation memory.

Major decisions must be documented before implementation.

---

# Amending Decisions

Approved decisions may only be changed through deliberate review by the Creative Director and Technical Lead.

When a decision changes:

- Do not delete the original decision.
- Mark it as Superseded.
- Record the replacement decision with a new decision ID.

This preserves the project's development history.

---

## Related Documents

- PROJECT_CONSTITUTION.md
- PROJECT_OVERVIEW.md
- PROJECT_STATE.md
- GAME_BIBLE.md
- TECHNICAL_ARCHITECTURE.md

## D-001 — Inventory Philosophy

**Status:** Approved

**Date Approved:** YYYY-MM-DD

**Sprint:** A0.5

### Decision

The player uses a fully physical inventory consisting of hands, body slots and a backpack.

### Reasoning

A physical inventory reinforces immersion, encourages meaningful item management, and aligns with the project's VR-first philosophy.

### Implications

- No traditional inventory menu.
- All items require a physical representation.
- Future systems must integrate with the physical inventory.

### Superseded By

N/A

### — Unity Version
Unity 6000.3.20f1
Locked unless deliberately reviewed and superseded.