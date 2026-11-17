# 固件

[English](README.md) | [简体中文](README_ZH.md)

| 文件 | 用途 |
| --- | --- |
| [ESP32-S3-AUDIO-Board_FactoryOnly_20250829.bin](ESP32-S3-AUDIO-Board_FactoryOnly_20250829.bin) | 恢复原出厂演示 |
| [ESP32-S3-AUDIO-Board_XiaoZhi_v2.5.0.bin](ESP32-S3-AUDIO-Board_XiaoZhi_v2.5.0.bin) | 小智语音助手演示 |

按[烧录指南](https://docs.waveshare.net/ESP32-S3-AUDIO-Board/Firmware-Flashing/)从偏移地址 `0x0` 烧录所选的合并镜像。

使用 esptool 烧录出厂镜像时，将 `PORT` 替换为开发板的串口。

```sh
python -m esptool --chip esp32s3 --port PORT write_flash 0x0 ESP32-S3-AUDIO-Board_FactoryOnly_20250829.bin
```
