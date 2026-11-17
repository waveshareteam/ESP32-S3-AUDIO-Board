# LVGL Arduino Audio Interface

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Demonstrates an LVGL touch UI with board status and TF card music playback.

## Hardware Required

ESP32-S3-AUDIO-Board and a USB data cable. For the full demo, connect the configured 2.8-inch touch LCD, camera and speaker, and insert a FAT32 TF card with MP3 files.

## How to Run

Install the Arduino-ESP32 version listed on the [repository homepage](../../../../README.md) and set the sketchbook to [the Arduino directory](../../). Select **ESP32S3 Dev Module**, set **Flash Size** to **16MB**, **PSRAM** to **OPI PSRAM** and **Partition Scheme** to **ESP SR 16M**, then open `LVGL_Arduino.ino` and upload.

## Expected Result

The display shows board status and a music player for the tracks on the TF card.

## Troubleshooting

Check the LCD selection in `Board_Configuration.h` if your panel differs.
