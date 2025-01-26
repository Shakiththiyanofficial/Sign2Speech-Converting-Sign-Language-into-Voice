# Sign2Speech: Converting Sign Language into Audible Speech
## Overview
This project introduces an innovative technology that leverages flex sensors and the ESP32 microcontroller to convert sign language gestures into audible speech. The system records hand motions through flex sensors, identifying finger movements and bending, and then processes the data to produce corresponding vocal outputs.

**Purpose:** Speech-impaired individuals often face challenges communicating when no one around understands sign language, especially in emergencies or when trying to reach someone far away. This system provides a voice for them, enabling better communication and the ability to call for help or convey their needs over a distance.
## Features
- Gesture Recognition: Flex sensors detect finger movements and bending for specific hand gestures.
- Speech Output: Text mapped to gestures is converted into audible speech using Google Text-to-Speech API.
- Customizable Commands: Users can personalize the text associated with gestures via a mobile app.
- Wireless Connectivity: The ESP32 communicates with the user interface over Wi-Fi, ensuring seamless operation.
- Audio Playback: Speech is played on a mobile device and can also be transmitted to a Bluetooth speaker.
## Hardware Components
- ESP32 development board: Acts as the core processing unit with built-in Wi-Fi and Bluetooth capabilities, managing gesture data and communication.
- Flex Sensors: Detect bending angles of fingers to interpret hand gestures.
- Zero PCB: Provides a compact platform for component connections.
- Power Supply: Ensures stable operation of the ESP32 and flex sensors.
## Circuit Diagram

