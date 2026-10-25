# Test plan

## Before the device arrives

- Validate repository instructions and documentation links.
- Prepare a reproducible host-side analysis environment.
- Prepare hash, metadata, and evidence recording scripts only after their scope is reviewed.

## First-arrival smoke tests

- Power-on and boot time
- Battery and charging behavior
- Display refresh and ghosting
- Button or touch input
- USB enumeration
- SD card read/write behavior
- Sleep and wake
- Factory update/recovery path

## Firmware-change gates

Every device change must have:

- A stated hypothesis
- A backup reference
- A reversible procedure
- A pass/fail observation
- A recovery result or an explicit reason it was not tested
