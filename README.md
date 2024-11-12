# Music-Recognition-System

## Overview

This project integrates the **M5Stick** (an ESP32-based microcontroller), **Raspberry Pi**, and **Python** to create a system capable of recognizing music from an audio input. The system captures sound from a microphone, processes the audio, and identifies the corresponding song. The recognition utilizes audio fingerprinting or machine learning techniques, which match the captured sound to a database of known songs.

The project demonstrates how to combine these hardware components and Python-based algorithms to create a portable, real-time music recognition system.

## Features

- **Sound Input**: Capture audio through a microphone attached to the Raspberry Pi or M5Stick.
- **Music Recognition**: Identify the song corresponding to the audio using audio recognition algorithms or APIs.
- **M5Stick Display**: Display the recognized song title, artist, and other details on the M5Stick's small screen.
- **Raspberry Pi Backend**: Manage sound processing, recognition logic, and interaction with external music databases or APIs.

## Components

- **Raspberry Pi**: The main processing unit that handles sound capture, recognition, and database interaction.
- **M5Stick**: A compact ESP32-based device with a small display, used to show the recognized song information.
- **Microphone**: A microphone or sound sensor to capture audio input.
- **Python Libraries**: Various libraries for audio processing and recognition (e.g., `pydub`, `librosa`), along with API integrations for external recognition services (e.g., ACRCloud, Shazam).

## Requirements

### Hardware

- Raspberry Pi 3/4 (or similar)
- M5Stick (ESP32-based)
- Microphone (USB or sensor for Raspberry Pi or M5Stick)
- Internet connection (for API calls or database interaction)

### Software

- Python 3.x
- Python Libraries:
  - `pydub` – For audio manipulation
  - `librosa` – For audio feature extraction
  - `requests` – For interacting with external APIs
  - `m5stack` – For controlling the M5Stick display
  - Other libraries for audio recognition (e.g., `shazamio`, `pyaudio`)
 
  ## License
  This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
