# Murphy M3 Firmware Preparation Plan

## Phase 00 — Preparation before device arrival

Status: In progress

Objectives:

- Establish a safe workspace and evidence model.
- Collect public reference material without assuming hardware equivalence.
- Prepare the first-arrival checklist.
- Decide which tools can be installed before the exact hardware is confirmed.

Acceptance criteria:

- The project has repository guidance and a written safety boundary.
- The first-arrival checklist covers identification, backup, recovery, and logging.
- Unknowns are explicitly listed rather than guessed.

## Phase 01 — Identify the delivered hardware

Status: Not started

Prerequisites: Device delivered and charged.

Acceptance criteria:

- Exact model, hardware revision, display, input method, MCU/SoC, storage, and factory firmware version are recorded.
- Photos and USB/serial identifiers are stored in the evidence directory.
- No firmware write has occurred.

## Phase 02 — Preserve the factory state

Status: Not started

Prerequisites: Phase 01 complete; recovery path identified.

Acceptance criteria:

- Factory update files and/or flash dump are preserved.
- SHA-256 hashes are recorded.
- A tested recovery procedure exists before experimentation.

## Phase 03 — Reproduce and extend the firmware build

Status: Not started

Prerequisites: Phase 02 complete; target toolchain confirmed.

Acceptance criteria:

- A clean build can be reproduced.
- Host-side tests pass.
- The first hardware change is a narrowly scoped, reversible probe or diagnostic build.
