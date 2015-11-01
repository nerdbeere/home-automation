# Distributed home-automation network
The goal of this project is to build a distributed home-automation network with open-source components like the raspberry pi.

## Software
- node.js
  - `onoff` (https://github.com/fivdi/onoff)
  - something like `telepathine` (https://github.com/automenta/telepathine)

### Music
- Spotify Webplayer API

### Voice commands
- Text-to-speech software (https://www.ivona.com/)
- Speech-to-text software ([wit.ai](http://wit.ai), jasper)

### Generic software requirements
- Software needs no setup
- Software updates itself
- Software needs a touch interface
- Each node runs with the same software
- Each node is independent
- Nodes connect to each other and share all information

## Sensors
- Movement Sensor HC-SR501
- 1-Wire Temperature Sensor (e.g. DS18B20)
- ~~iBeacon~~ After quite some tests it turned out that iBeacons are not precise enough for passive indoor tracking and heavily rely on a phone.

## Hardware
- 8-Channel Relay Board (http://www.sainsmart.com/8-channel-dc-5v-relay-module-for-arduino-pic-arm-dsp-avr-msp430-ttl-logic.html)
- 7“ Touch Screen (http://swag.raspberrypi.org/products/raspberry-pi-7-inch-touchscreen-display)
- Speakers

### Optional hardware
- Camera
- Microphone

## Issues
- Which linux should be used on the raspberry?
- What’s the best solution to create a touch interface that runs smoothly on the raspberry and talks to the node.js process?
- There must be always a way to physically turn lights on/off
