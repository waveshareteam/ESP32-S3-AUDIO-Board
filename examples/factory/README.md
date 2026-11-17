# Factory Demo

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Demonstrates voice wake-up, RGB light effects and button-controlled MP3 playback.

## Hardware Required

ESP32-S3-AUDIO-Board and a USB data cable. For playback, connect a speaker and insert a FAT32 TF card with MP3 files in the root directory.

## How to Run

Use the factory project ESP-IDF version on the [repository homepage](../../README.md). Run `idf.py build flash monitor` in this directory.

## Expected Result

K2 toggles playback. Say “Hi, ESP” and then “灯光变成红色” to set the light ring to red.

## Troubleshooting

K1 and K3 adjust the volume on a short press and change tracks on a long press.
