# [ESP32 based Webserver for Text to Speech (TTS) Conversion](https://iotdesignpro.com/projects/esp32-based-text-to-speech-converter-webserver) &middot;

Use ESP32 to build a TTS (Text to Speech) engine which can convert any number into speech.

- **Component-Based:** Built based on the idea and source code provided by IoTDesignPro website in the article "ESP32 based Webserver for Text to Speech (TTS) Conversion".

## Installation

The source code is built for ESP32 microcontroller and compiled through the Arduino IDE.

- [Install](https://www.arduino.cc/en/software) Arduino IDE to edit source code and upload code to the ESP32 microcontroller.
- [Install](https://github.com/ArminJo/Talkie) the Talkie library.
- Increasing Max Tokenization Length in Arduino IDE:
  - Press the <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> keyboard shortcut (<kbd>Command</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> for macOS users) to open the "Command Palette".
  - Select the "Preferences: Open Settings (UI)" command from the menu.
  - A "Preferences" tab will now open in the Arduino IDE main panel. In the "Search Settings" field, type 'editor.maxTokenizationLineLength'.
  - Adjust the value of the <code class="notranslate">editor.maxTokenizationLineLength</code> to 2000000.
  - Click the X icon on the "Preferences" tab.

## Circuit Diagram

| Platform | Pinout usage |
| -------- | ------------ |
| ESP32    | Pin 25       |

[![Connecting Speaker to ESP32](https://iotdesignpro.com/sites/default/files/inline-images/Circuit-Diagram-for-ESP32-based-Webserver-for-Text-to-Speech-Conversion.png)](https://iotdesignpro.com/projects/esp32-based-text-to-speech-converter-webserver)

[![LM386 Audio Amplifier Circuit Diagram](https://iotdesignpro.com/sites/default/files/inline-images/LM386-Based-Audio-Amplifier-Circuit.png)](https://circuitdigest.com/electronic-circuits/lm386-audio-amplifier-circuit)

## Documentation

You can find the documentation [on the website](https://iotdesignpro.com/projects/esp32-based-text-to-speech-converter-webserver).
