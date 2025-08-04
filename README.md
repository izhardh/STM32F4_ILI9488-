# How to Interface an ILI9488 TFT LCD with STM32F4 Microcontroller

This project demonstrates how to interface an ILI9488-based TFT LCD with an STM32F4 microcontroller using SPI communication. The code is based on STM32 HAL drivers and is tested using STM32CubeIDE.

## Features

- ILI9488 TFT LCD driver (SPI mode)
- Display initialization and configuration
- Text rendering on the screen
- Modular and clean C code (HAL-based)

## Requirements

- STM32F4 microcontroller (e.g., STM32F401/STM32F407)
- ILI9488 3.5” TFT LCD (SPI interface)
- STM32CubeIDE
- STM32 HAL library
- Breadboard/jumpers or PCB for connections

## Pin Configuration (example)

| ILI9488 Pin | STM32 Pin (example) |
|-------------|---------------------|
| CS          | PB6                 |
| RESET       | PB7                 |
| DC/RS       | PB8                 |
| MOSI        | PA7 (SPI1_MOSI)     |
| SCK         | PA5 (SPI1_SCK)      |
| LED         | 3.3V or GPIO        |
| GND         | GND                 |
| VCC         | 3.3V                |
