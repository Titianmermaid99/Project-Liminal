# SPRINT HISTORY

**Project:** Project Liminal
**Document Owner:** Technical Lead
**Status:** Living
**Version:** 1.0
**Last Updated:** YYYY-MM-DD

---

# Purpose

This document provides a historical record of every completed sprint throughout the development of Project Liminal.

Unlike the CHANGELOG, which records changes to the project, this document records the work performed, the outcomes achieved, and the lessons gained during each sprint.

Each sprint should be recorded immediately after completion.

---

# Sprint Template

## Sprint

**Sprint ID:**

**Title:**

**Status:**

Completed

**Start Date:**

YYYY-MM-DD

**Completion Date:**

YYYY-MM-DD

---

## Objective

Brief summary of the sprint goal.

---

## Scope

List the work planned for this sprint.

- Item
- Item
- Item

---

## Deliverables

List everything successfully completed.

- Deliverable
- Deliverable
- Deliverable

---

## Challenges

Document any problems encountered.

- Challenge
- Challenge

---

## Decisions Made

Reference approved decisions.

- D-###
- T-###
- W-###

---

## Technical Debt Introduced

Reference Technical Debt entries.

- TD-###

---

## Lessons Learned

Reference Lessons Learned entries.

- LL-###

---

## Outcome

Summarise the overall success of the sprint.

---

# Sprint History

---

## Sprint A0.5 — Project Foundation

**Status:**

Completed

**Start Date:**

YYYY-MM-DD

**Completion Date:**

YYYY-MM-DD

---

### Objective

Create a complete documentation framework capable of supporting the long-term development of Project Liminal.

---

### Deliverables

- Documentation folder structure established.
- Repository navigation standardised.
- README created.
- INDEX created.
- PROJECT_CONSTITUTION completed.
- PROJECT_OVERVIEW completed.
- PROJECT_STATE completed.
- CHATGPT_CONTINUATION completed.
- SPRINT_TEMPLATE completed.
- CHANGELOG completed.
- LESSONS_LEARNED completed.
- APPROVED_DECISIONS completed.

---

### Challenges

- Designing documentation that remains useful over a multi-year development cycle.
- Separating documentation responsibilities to avoid duplication.

---

### Decisions Made

- W-001
- W-002
- W-003

---

### Technical Debt Introduced

None.

---

### Lessons Learned

- LL-001
- LL-002

---

### Outcome

Sprint A0.5 successfully established the documentation, workflow, and project governance required to support long-term development.

Future sprints should follow the processes defined during this sprint.

---

## Sprint A1.5 — Unity Locomotion Integration

**Status:** Pending Technical Lead Review

**Implementation Date:** 2026-07-21

### Objective

Integrate Unity XR Interaction Toolkit continuous locomotion with the canonical XR Player foundation.

### Deliverables

- Project-owned XR locomotion Input Actions containing only Move and Turn.
- Head-relative continuous movement from the left controller thumbstick.
- Continuous turning from the right controller thumbstick.
- XRI locomotion mediator and body transformer integration.
- XRI gravity, ground detection, CharacterController collision, and headset-relative capsule alignment.
- Minimal XRValidation scene containing the Player, floor, boundary walls, and basic lighting.

### Decisions Made

- Unity/XRI locomotion components remain the implementation authority.
- Continuous turn speed uses the approved Project Liminal default of 45°/second; movement and other untuned XRI values remain provisional until Creative Director headset testing.
- Snap turning, teleportation, and custom locomotion scripts remain excluded.

### Verification Status

- Unity import and compilation: completed.
- Repository and prefab configuration inspection: completed.
- Quest headset locomotion testing: pending.

### Technical Debt Introduced

None. Comfort and speed tuning remain intentional validation work rather than technical debt.
