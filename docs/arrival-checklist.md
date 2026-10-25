# First-arrival checklist

Complete this checklist before modifying the device.

## 1. Preserve the original state

- Photograph the packaging, labels, ports, buttons, and screen.
- Record date received, seller listing, model name, serial number, and visible revision.
- Record the factory firmware version from the device UI.
- Photograph every information screen before changing settings.
- Do not accept an update prompt before recording the original version.

## 2. Identify the hardware

- Determine touch or non-touch variant.
- Record screen size, resolution, and orientation.
- Record USB VID/PID and the operating-system device name.
- Record CPU/SoC, flash, PSRAM, display controller, and storage if observable without destructive disassembly.
- Record button, touch, SD-card, charging, sleep, and wake behavior.

## 3. Acquire factory materials

- Save any vendor update package exactly as received.
- Record SHA-256 hashes before extraction.
- If readback is supported, create a complete factory flash dump.
- Store derived partitions separately from originals.
- Record the exact tool version and command used for each acquisition.

## 4. Establish recovery

- Identify the vendor bootloader or recovery mode.
- Confirm how to return to the factory image.
- Keep a known-good cable and stable power source available.
- Do not flash a custom image until recovery is documented and verified.

## 5. Evidence record

Create `evidence/device-<date>/` with photos, metadata, hashes, logs, and observations. Do not store secrets or personal data.
