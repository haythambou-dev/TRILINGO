# Hardware notes

## Current concept

- Controller: ESP32 development board (exact board/model and pinout still to be identified).
- Inputs: nine picture buttons in a 3×3 layout (planned).
- Language selection: three-position selector (planned).
- Audio: DFPlayer Mini and 3 W / 8 Ω speaker have been discussed; working connection is not yet verified.
- Power: battery and charging/protection design deferred until the rest of the architecture is confirmed.

## Important

Do not copy a GPIO map from a generic ESP32 tutorial. ESP32 boards differ, and some pins have boot, flash or input-only restrictions. Record the exact board model and verify every chosen pin before wiring.

Do not connect a speaker directly to an ESP32 GPIO. Use the appropriate audio module/amplifier output and follow its datasheet.

## To fill in

- ESP32 board manufacturer/model:
- Board revision:
- Audio module exact model:
- Speaker part/link:
- Button part/link:
- Power source:
- Confirmed GPIO map:
- Measured supply voltages:
