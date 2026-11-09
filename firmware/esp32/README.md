# ESP32 firmware

Firmware is intentionally not stubbed with guessed GPIO pins.

Before writing the first complete sketch:

1. Identify the exact ESP32 board model.
2. Confirm the nine button pins and language-selector pins.
3. Confirm whether the selected audio module is available.
4. Document the audio module's control interface and wiring.
5. Add a minimal input test, then integrate audio playback.

Place the verified Arduino/PlatformIO source here. Include board selection, library versions and upload instructions.
