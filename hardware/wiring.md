# TRILINGO – Wiring Plan

## 1. Overview

The ESP32 will act as the main controller. It will detect button presses and trigger the audio playback system to play the corresponding message through the speaker.

## 2. Main Connections

| Component | Connection |
|---|---|
| Button 1 | ESP32 GPIO |
| Button 2 | ESP32 GPIO |
| Button 3 | ESP32 GPIO |
| Audio module | ESP32 control connection |
| Speaker | Audio module output |
| Power supply | ESP32 and audio system |

## 3. Button Logic

Each button will have its own GPIO pin.

When pressed, the ESP32 will detect the input and select the assigned audio file.

## 4. Audio Playback

The ESP32 will communicate with an audio playback module. The module will play the selected MP3 file through the speaker.

## 5. Planned Components

- ESP32 development board
- 3 push buttons
- Audio playback module
- Speaker
- Power supply
- Jumper wires

## 6. Current Status

**Status:** Planned – wiring has not yet been tested.

The exact GPIO pins, module model and power connections will be documented after selecting the final components.
