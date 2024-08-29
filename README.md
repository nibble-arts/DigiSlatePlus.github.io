# DigiSlate+

The digital film slate project

DigiSlatePlus is based on the DigiSlate and is inspired by the DIY timecode generator from mitkunz. The aim for the DigiSlatePlus is not only to be able to read and display timecode, but also to generate it itself. To make this possible, the hardware is extended by a real time clock with high running accuracy.

An additional row of LEDs indicates the scene and take numbers, which can be set using a rotary encoder.

An ESP32S3 is used as the main processor, which offers a wireless radio connection via WiFi and Bluetooth. This can be used to set the internal time via an NTP server, configure the slate or export a list of folding processes.

Blackmagic cameras that save scenes and takes as metadata can be connected via Bluetooth. The Slate then sends the settings to the camera.
