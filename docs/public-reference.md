# Public reference material

## Primary reference

- Repository: https://github.com/crosspoint-reader/Murphy
- M3 directory: https://github.com/crosspoint-reader/Murphy/tree/main/m3
- Purpose: public firmware dump, extracted artifacts, reverse-engineering notes, and porting notes.

## Reported reference hypothesis

The public M3 notes describe one hardware line as ESP32-S3 based, with 16 MiB flash, 8 MiB PSRAM, a 416x240 e-paper panel, SD storage, side buttons, and touch. They also describe an ESP-IDF/Arduino-derived firmware image.

These details are unverified for the device that will arrive in December 2026. Treat them as hypotheses until confirmed from the delivered hardware and factory image.

## Use policy

- Record the public repository commit or tag used for each comparison.
- Do not copy a public firmware image to the device merely because the model name matches.
- Prefer upstream source, documentation, and reproducible build instructions over prebuilt binaries.
- Preserve license and attribution information for any code reused later.
