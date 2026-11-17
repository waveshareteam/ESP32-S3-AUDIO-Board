# 出厂演示

[English](README.md) | [简体中文](README_ZH.md)

## 功能

演示语音唤醒、RGB 灯效和按键控制的 MP3 播放。

## 硬件需求

ESP32-S3-AUDIO-Board 开发板和 USB 数据线。 播放音乐时，接上扬声器并插入根目录含 MP3 文件的 FAT32 TF 卡。

## 怎么运行

安装[仓库首页](../../README_ZH.md)列出的出厂演示 ESP-IDF 版本。在当前目录运行 `idf.py build flash monitor`。

## 预期现象

K2 切换播放和暂停。说 “Hi, ESP” 唤醒，再说“灯光变成红色”切换灯环颜色。

## 常见问题

短按 K1 或 K3 调节音量，长按切换曲目。
