# ESP-SR Voice Recognition

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Recognizes a wake word and English voice commands.

## Hardware Required

ESP32-S3-AUDIO-Board and a USB data cable.

## How to Run

Use the ESP-IDF version listed on the [repository homepage](../../../README.md). Run `idf.py build flash monitor` in this directory.

## Expected Result

Say “Hi, ESP” and then “Turn on the backlight”. The serial monitor logs the wake-up and recognized command.

## Troubleshooting

The backlight commands are reported through the serial monitor.
