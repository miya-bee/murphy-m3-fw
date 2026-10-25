# Murphy M3 Firmware Preparation

## Scope

This directory is for preparation and evidence collection for Murphy M3 firmware development before the device arrives.

## Important assumptions

- The exact hardware revision and factory firmware are unknown until the device arrives.
- Public Murphy M3 reverse-engineering material is reference material, not proof that the delivered device is identical.
- Do not select a production firmware image or flash the device based only on public information.

## Safety rules

- Do not write to a physical device without explicit user approval.
- Do not overwrite or delete the factory firmware.
- Preserve a complete factory dump and its SHA-256 hash before modification.
- Keep bootloader, partition metadata, calibration data, user data, and recovery instructions separate.
- Treat unknown hardware, pin mappings, partitions, and firmware formats as unknown; do not guess.
- Keep external downloads, pushes, releases, and credentials behind explicit approval.

## Workflow

1. Read-only preparation
2. Device identification
3. Factory backup and hash verification
4. Firmware and partition analysis
5. Build environment reproduction
6. Host-side and fixture tests
7. Explicit approval before device flashing

## Evidence requirements

Record commands, tool versions, source URLs, hashes, observed device identifiers, assumptions, and unresolved questions.
