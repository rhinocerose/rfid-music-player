# rfid-music-player

A player for a child that uses RFID tags to play back media.

## Hardware Options

### MCU
1. Raspberry Pi
2. Arduino
3. ESP32

### Audio Processing
1. **DFPlayer Mini** (
2. **MAX98357** - I2S digtal input audio amplifier
3. **UDA1334**
4. **PCM510x** - requires amplification

### NFC/RFID Read
1. **MFRC522**
2. **PN532**

### Battery
#### Charging
1. **MCP73833** - 

#### Monitoring
1. **DS2438**
2. **BQ77905**
3. **XB8089D**

## Firmware
- [Audio Playback with ESP82 or Pi Pico](https://github.com/earlephilhower/ESP8266Audio)
- [PCM510x used with ESP8266](http://www.nihamkin.com/pcm-audio-on-esp8266-using-the-pcm5102-chip.html)
