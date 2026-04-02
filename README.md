This project is an attempt to create a custom local voice assistant for three reasons: avoid being farmed for data by large companies, have a completely local system unreliant on internet access, and increase customizability.

This Node-Red flow contains all of the logical processing for the voice assistant. It connects to dockerized containers hosting open-source processing. The stack includes Openwakeword, rhasspy, node-red, mosquitto (mqtt), mimic3 (a text-to-speech engine), various wyoming containers (for creating satellites), and whisper (automatic speech recognition). 

All of this open-source software is hosted locally on a headless Linux server.

The hardware is extremely variable, and I have not settled on anything specific. I am still experimenting with different options. One of the unsolved issues is achieving over 99% accuracy when it comes to wake words. Current open-source microphone array software is unsatisfactory and is the biggest limiter. 

<img width="1328" height="2204" alt="image" src="https://github.com/user-attachments/assets/03921b8f-c13b-4f29-8686-66aa6523fcd5" />

A screenshot of the whole flow
