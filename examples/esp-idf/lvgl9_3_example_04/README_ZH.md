# LVGL 9.3 音频界面

[English](README.md) | [简体中文](README_ZH.md)

## 功能

演示板载状态显示、MP3 播放和语音识别。

## 硬件需求

ESP32-S3-AUDIO-Board 开发板和 USB 数据线。 接上兼容的触控 LCD 和摄像头，插入根目录含 MP3 文件的 FAT32 TF 卡。

## 怎么运行

安装[仓库首页](../../../README_ZH.md)列出的 ESP-IDF 版本。在当前目录运行 `idf.py build flash monitor`。

## 预期现象

屏幕显示板载状态及音乐播放器。说 “Hi, ESP” 唤醒识别。

## 常见问题

播放列表为空时，检查曲目是否放在 TF 卡根目录。
