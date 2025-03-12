# RTOS
Buidling my own RTOS from scratch on STM32F429 discovery board using stm32cube-IDE



## LED Driver for STM32 RTOS Project
This repository is part of my custom RTOS development project for the STM32F429I-DISC1 board using STM32CubeIDE.  

### LED Driver Overview
The LED driver is a fundamental module that provides essential control over the onboard LED (PA5) on the STM32F429I-DISC1. It includes the following features:  
- **Initialization Function (`led_init`)**: Configures the GPIO pin for the LED as an output.  
- **LED Control Functions (`led_on` and `led_off`)**: Enables turning the LED on or off for visual feedback in the RTOS environment.  

### Files Included
- `main.h` – Contains function declarations and essential includes.  
- `led.h` – Declares LED control functions.  
- `led.c` – Implements the LED control logic.  

This module will serve as a basic foundation for task scheduling, synchronization, and other RTOS features in upcoming milestones.  

Stay tuned for updates as the RTOS evolves! 
