# TRILINGO 🗣️

**A simple communication device designed to help children express themselves.**

TRILINGO is a project I'm building to make communication easier for children who have difficulty expressing their needs, feelings and thoughts.

The idea came from wanting to create something simple but useful: a small physical device with buttons that play spoken messages when pressed.

I want TRILINGO to support three languages: Moroccan Darija, French and English, so children can communicate in the language they're most comfortable with.

## How it works

The device will have three large physical buttons. Each button represents a different message. When a child presses one, the ESP32 will detect the input and play the corresponding voice recording through a speaker.

For the first prototype, I'm planning to use a cardboard enclosure to test the design and button placement before making a more finished version.

## Voice system

I'm using ElevenLabs to generate the voice recordings instead of recording them myself.

So far, I've generated six audio files, each containing the same phrase in Darija, French and English. That's 18 spoken phrases in total.

I'm also developing a small audio editing application to help me listen to, trim, adjust and organize the recordings before integrating them into TRILINGO.

## Hardware

The current plan is to use an ESP32 as the main controller, together with three physical buttons, a speaker, audio playback components and a power supply.

I'll finalize the exact components and wiring as the design develops.

## Technologies

- ESP32 for controlling the device.
- ElevenLabs for generating voices.
- Python and web technologies for software tools.
- GitHub for organizing and documenting development.

## Current progress

The main idea and initial design direction are established. I've also started working on the multilingual audio system and the audio editing application.

My next goal is to finalize the physical design, choose the electronic components and get the three buttons playing their assigned messages.

## What's next?

I want to start with a simple working prototype instead of trying to build everything at once. Once the basic system works, I'll improve the design and add more phrases and features.

TRILINGO is still a work in progress, and I'll be documenting the process as I build it.

**Made with curiosity, code and a little cardboard. 💛**
