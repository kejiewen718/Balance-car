# Balance Car

STM32F103C8 two-wheel self-balancing car project.

## Overview

This repository contains a Keil-based embedded project for a balance car built on `STM32F103C8`.
The project includes:

- MPU6050 attitude acquisition and Mahony attitude estimation
- Encoder-based speed feedback
- Balance, velocity, and turn control loops
- TB6612 motor driver control with PWM output
- Bluetooth control
- OLED display
- Battery voltage detection
- Ultrasonic ranging support
- Flash-based parameter storage

## Main Structure

- `core/`: Cortex-M3 core and startup files
- `driver/`: peripheral drivers and control algorithms
- `st_lib/`: STM32 Standard Peripheral Library
- `user/`: Keil project files and application entry

## Development Environment

- MCU: `STM32F103C8`
- IDE: `Keil uVision`
- Library: `STM32 Standard Peripheral Library`

## Notes

- Build output files are excluded from version control.
- The original project entry is `user/main.c`.
