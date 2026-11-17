# ESP-SR 语音识别

[English](README.md) | [简体中文](README_ZH.md)

## 功能

演示唤醒词和英文语音命令识别。

## 硬件需求

ESP32-S3-AUDIO-Board 开发板和 USB 数据线。

## 怎么运行

安装[仓库首页](../../../README_ZH.md)列出的 ESP-IDF 版本。在当前目录运行 `idf.py build flash monitor`。

## 预期现象

说 “Hi, ESP” 唤醒，再说 “Turn on the backlight”。串口监视器显示唤醒和命令识别日志。

## 常见问题

背光命令的识别结果通过串口输出。
