# LVGL 9.3 Audio Interface

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Demonstrates an LVGL interface with onboard status, MP3 playback and voice recognition.

## Hardware Required

ESP32-S3-AUDIO-Board and a USB data cable. Connect a compatible touch LCD and a camera, and insert a FAT32 TF card with MP3 files in its root directory.

## How to Run

Use the ESP-IDF version listed on the [repository homepage](../../../README.md). Run `idf.py build flash monitor` in this directory.

## Expected Result

The display shows board status and an audio player. Say “Hi, ESP” to wake the recognizer.

## Troubleshooting

If the player list is empty, check that the tracks are in the root of the TF card.
