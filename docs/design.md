# TRILINGO – Project Design

## 1. Overview

TRILINGO is a multilingual communication device designed to help children express their basic needs, feelings and thoughts through physical buttons and spoken messages.

It supports three languages:
- Moroccan Darija
- French
- English

## 2. Physical Design

The first prototype will use a simple cardboard enclosure.

It is planned to include:
- Three large, easy-to-press buttons on the top.
- A speaker on the front.
- The TRILINGO logo on the front.
- A simple, colorful design that's easy for children to understand.

## 3. How It Works

Each button is assigned to a specific message.

When a button is pressed:
1. The ESP32 detects the button press.
2. It identifies the assigned message.
3. The audio playback system plays the corresponding recording.
4. The speaker outputs the spoken message.

## 4. Audio System

The first version contains six audio files. Each file includes the same phrase spoken in Darija, French and English.

The recordings are generated using ElevenLabs and organized using a custom audio editing application.

## 5. Hardware Plan

The planned components are:
- ESP32 development board
- Three physical push buttons
- Audio playback module
- Speaker
- Power supply
- Connecting wires

The exact components and wiring will be finalized during development.

## 6. Future Improvements

- Add more communication buttons.
- Improve the enclosure.
- Make the device more durable and portable.
- Add easier ways to organize and update audio messages.

---

**Status:** Work in progress. This document describes the current design plan, not a completed physical prototype.
