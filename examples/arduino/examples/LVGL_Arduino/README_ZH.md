# LVGL Arduino 音频界面

[English](README.md) | [简体中文](README_ZH.md)

## 功能

演示板载状态和 TF 卡音乐播放的 LVGL 触控界面。

## 硬件需求

ESP32-S3-AUDIO-Board 开发板和 USB 数据线。 完整演示需连接当前配置的 2.8 英寸触控 LCD、摄像头和扬声器，并插入含 MP3 文件的 FAT32 TF 卡。

## 怎么运行

安装[仓库首页](../../../../README_ZH.md)列出的 Arduino-ESP32 版本，将项目文件夹位置设为 [Arduino 目录](../../)。选中 **ESP32S3 Dev Module**，将 **Flash Size**、**PSRAM**、**Partition Scheme** 分别设为 **16MB**、**OPI PSRAM**、**ESP SR 16M**，然后打开 `LVGL_Arduino.ino` 并上传。

## 预期现象

屏幕显示板载状态和音乐播放器，可选择 TF 卡上的曲目播放。

## 常见问题

使用其他屏幕时，检查 `Board_Configuration.h` 中的屏幕驱动选择。
