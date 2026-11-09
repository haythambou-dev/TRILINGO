# TRILINGO

> An affordable, customizable, multilingual communication-device concept for children, designed with the Moroccan context in mind.

**Project status:** Prototype/design in progress. This repository is an honest working record, not a claim that the final device is complete.

## What is TRILINGO?

TRILINGO is a planned physical communication aid built around picture-based buttons. A child selects a picture representing a need or message; the device is intended to help communicate that message using recorded speech in **Moroccan Darija, French, and English**.

The current concept uses an ESP32-based controller and a 3×3 layout of nine physical picture buttons. Audio playback hardware and the final enclosure/electronics are still being verified.

## Why make it?

The goal is to explore a locally relevant, affordable and customizable communication aid. The project is being developed as a hands-on prototype, with usability and reliability to be tested rather than assumed.

## Current status

| Area | Status |
|---|---|
| Product concept | Defined |
| 9-button, 3×3 interaction concept | Planned; physical implementation needs verification |
| ESP32 development board | Board acquired; exact model and pinout need confirmation |
| Audio playback | Planned; module and wiring not yet verified |
| Darija / French / English recordings | To be recorded and tested |
| Enclosure CAD and STEP files | Not yet added |
| Custom PCB | Not yet designed / not applicable if prototype uses modules and wiring |
| Firmware | To be added after pin mapping and hardware verification |
| User testing | Not yet documented |

See [project status](docs/PROJECT_STATUS.md) and [the hardware notes](docs/HARDWARE_NOTES.md).

## How it is intended to work

1. The child presses a picture button.
2. The controller identifies the selected button.
3. The device selects the matching message in the chosen language.
4. The corresponding recorded message is played through the speaker.

This is the intended interaction flow. The complete audio path and language-selection implementation are still under development.

## Repository structure

```text
TRILINGO/
├── README.md
├── BOM.csv
├── docs/
│   ├── PROJECT_STATUS.md
│   ├── HARDWARE_NOTES.md
│   ├── TEST_PLAN.md
│   └── diagrams/
├── electronics/
│   ├── schematic/
│   ├── pcb/
│   └── wiring/
├── firmware/
│   └── esp32/
└── mechanical/
    ├── assembly/
    ├── parts/
    ├── step/
    └── renders/
```

## Screenshots and media

Add genuine project images as work progresses:

- Full 3D assembly: `mechanical/renders/`
- Individual CAD parts and STEP exports: `mechanical/step/`
- Schematic and wiring diagram: `electronics/schematic/` and `electronics/wiring/`
- PCB screenshots and source: `electronics/pcb/`
- Prototype and final-product photos: `docs/photos/`
- Demo video: add its public URL here when one exists.

Do not use concept renders as evidence of a completed physical build. Label concept images clearly.

## Bill of materials

See [`BOM.csv`](BOM.csv). Prices, exact part numbers and purchase links must be filled from the actual parts used or selected. Items already owned should be marked as owned.

## Build and firmware

Firmware instructions will be added after the exact ESP32 board, pin assignments and audio hardware are confirmed. No pin mapping is assumed in this starter repository.

## Contributions and originality

I'm designing and building TRILINGO myself. I sometimes use AI to help with ideas, writing, or debugging, but I make the design decisions and work on understanding and testing everything myself.

## License

No license yet. I'll choose one once I decide how I want people to use and modify the project.
