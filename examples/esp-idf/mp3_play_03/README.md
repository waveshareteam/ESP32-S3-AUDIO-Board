# TF Card MP3 Playback

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Scans the root of a TF card for MP3 files and plays them through the audio output.

## Hardware Required

ESP32-S3-AUDIO-Board and a USB data cable. Connect a speaker and insert a FAT32 TF card with MP3 files in its root directory.

## How to Run

Use the ESP-IDF version listed on the [repository homepage](../../../README.md). Run `idf.py build flash monitor` in this directory.

## Expected Result

The serial monitor lists the detected files and the speaker plays the audio.

## Troubleshooting

If no tracks are found, check the card format and file location.
