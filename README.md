# STM32 FreeRTOS Smart Pedometer

## Overview
A real-time Smart Pedometer developed using the STM32F429ZIT6 microcontroller, FreeRTOS and MPU6050 motion sensor. The system monitors motion data and detects walking steps using a threshold-based step detection algorithm.

## Hardware Requirements
- STM32F429ZIT6 Discovery Board
- MPU6050 Accelerometer and Gyroscope
- I2C interface

## Software Requirements
- Embedded C
- STM32CubeIDE
- FreeRTOS

## Features
- Real-time motion data acquisition using MPU6050
- I2C-based sensor interfacing
- Threshold-based step detection
- Real-time step counting
- FreeRTOS task management and scheduling

## Implementation
- MPU6050 is interfaced with STM32 through the I2C protocol.
- Sensor readings are acquired periodically using FreeRTOS tasks.
- Motion data is processed using a threshold-based algorithm to identify steps.
- FreeRTOS manages task execution and scheduling to ensure responsive operation.

## Concepts Used
- STM32 Microcontroller Programming
- Embedded C
- FreeRTOS Multitasking
- Task Scheduling
- I2C Communication
- Accelerometer and Gyroscope Interfacing
- Sensor Data Processing
- Threshold-Based Detection

## Future Improvements
- Improve step detection accuracy
- Add distance and calorie estimation
- Integrate an LCD or graphical display

## Author
Sneha B.
