# TF 卡 MP3 播放

[English](README.md) | [简体中文](README_ZH.md)

## 功能

扫描 TF 卡根目录并通过音频输出播放 MP3 文件。

## 硬件需求

ESP32-S3-AUDIO-Board 开发板和 USB 数据线。 接上扬声器，并插入根目录含 MP3 文件的 FAT32 TF 卡。

## 怎么运行

安装[仓库首页](../../../README_ZH.md)列出的 ESP-IDF 版本。在当前目录运行 `idf.py build flash monitor`。

## 预期现象

串口监视器列出检测到的文件，扬声器播放音频。

## 常见问题

找不到曲目时，检查卡的格式和文件位置。
