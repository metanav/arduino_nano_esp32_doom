# Arduino Nano ESP32 Doom

Please find the details here: https://www.hackster.io/naveenbskumar/yes-arduino-nano-esp32-can-play-doom-ccfde1

Execute command below to flash:

```
$ esptool.py --chip esp32s3 write_flash --flash_size detect  0x00 retro-go_1.39-pre-dirty_esplay-s3.img
```
