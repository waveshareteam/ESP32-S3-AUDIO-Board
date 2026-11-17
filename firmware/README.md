# Firmware

[English](README.md) | [简体中文](README_ZH.md)

| File | Purpose |
| --- | --- |
| [ESP32-S3-AUDIO-Board_FactoryOnly_20250829.bin](ESP32-S3-AUDIO-Board_FactoryOnly_20250829.bin) | Restore the original factory demo |
| [ESP32-S3-AUDIO-Board_XiaoZhi_v2.5.0.bin](ESP32-S3-AUDIO-Board_XiaoZhi_v2.5.0.bin) | XiaoZhi voice assistant demo |

Use the [flashing guide](https://docs.waveshare.com/ESP32-S3-AUDIO-Board/Firmware-Flashing) to flash either combined image from offset `0x0`.

To flash the factory image with esptool, replace `PORT` with the board’s serial port.

```sh
python -m esptool --chip esp32s3 --port PORT write_flash 0x0 ESP32-S3-AUDIO-Board_FactoryOnly_20250829.bin
```
