# Toolchain policy

## Before device arrival

Prepare only host-side tools that do not depend on the exact hardware revision:

- Git and Git LFS only if required by the eventual source tree
- Python in an isolated virtual environment
- SHA-256 and metadata utilities
- Ghidra for read-only analysis
- A binary inspection workflow
- PlatformIO or ESP-IDF documentation review

## After hardware identification

Select and pin the exact toolchain based on the confirmed MCU/SoC, SDK version, partition format, and upstream source. Record versions in `evidence/toolchain-manifest.md`.

## Do not pre-commit yet

- A target-specific PlatformIO board definition
- GPIO mappings
- Flash offsets
- Partition tables
- Bootloader settings
- A custom firmware image

Those items must come from the delivered device and verified evidence.
