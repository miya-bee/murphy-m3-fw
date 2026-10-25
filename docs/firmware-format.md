# Firmware format and analysis

No device-specific conclusions are approved yet.

## Planned read-only analysis

1. Hash every factory file before opening or modifying it.
2. Identify file type and image boundaries.
3. Locate bootloader, partition table, application slots, filesystem, NVS, and calibration regions.
4. Record offsets and sizes in a table.
5. Extract copies for analysis; never edit the original.
6. Compare the delivered image with public reference material.

## Required outputs

- `evidence/firmware-manifest.md`
- `evidence/flash-layout.md`
- `evidence/hashes.sha256`
- `analysis/` containing derived, read-only artifacts

## Prohibited before approval

- Erasing flash
- Changing boot selection or OTA metadata
- Uploading a custom image
- Treating a public image as a valid image for the delivered unit
