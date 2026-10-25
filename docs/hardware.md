# Hardware identification

## Current status

The device has not arrived. All hardware details below are unconfirmed until measured on the delivered unit.

## Public reference hypothesis

The public `crosspoint-reader/Murphy` M3 material describes one M3 hardware line as ESP32-S3-based with 16 MiB flash, 8 MiB PSRAM, a 416x240 e-paper panel, SD storage, buttons, and touch. This must be verified against the delivered unit.

Reference: https://github.com/crosspoint-reader/Murphy/tree/main/m3

## To record on arrival

- Product name, label, serial, and hardware revision
- Touch or non-touch variant
- Screen dimensions and resolution
- MCU/SoC marking
- Flash and PSRAM capacity
- Display controller and panel marking
- Battery and charging controller
- Button and touch behavior
- USB VID/PID and serial device name
- SD card and partition contents
- Factory firmware version and update filename
- Board and connector photographs

## Unknowns

- Whether the delivered revision matches the public M3 dump
- Whether the factory bootloader permits safe readback
- Whether OTA/update files contain a complete recovery image
