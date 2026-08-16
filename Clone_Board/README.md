# Overview

## Progress Log

I will be updating a progress log every time I work on the project; this can be found [here](./Clone_Board_log.md).

## The Microcontroller

The dev board that I've decided to move foward with is the [STM32F401 "Black Pill"](https://stm32-base.org/boards/STM32F401CCU6-WeAct-Black-Pill-V1.2.html). I wanted to do something simple, and from my online searches the dev boards with an STM32F401 chip seems to be the most beginner friendly.

I couldn't find any official schematics of the dev board online, so I will be using one that seems to be a hobbyist reconstruction as reference. For the most part, I will be relying on the datasheet of the chip.

## Learning Objectives

- Know how to read and extract info from data sheets
- Understand what measures are taken to ensure protection and function of board components (decoupling capacitors, pull up/down resistors, voltage regulators, etc.)
- Learn common terms like SWD, bootloading, etc.
- Understand the core components of a microcontroller dev board and how boards are modified to suit specific needs
- Learn schematic and PCB design/layout best practices

## Components

Internal/on-chip peripherals:

- 1 12-bit ADC
- 11 timers (6 16-bit general purpose, 2 32-bit gen purpose, 2 watchdogs, 1 systick timer)
- 3 I2C buses, 3 USART/UART modules, 4 SPI interfaces, 2 I2S interfaces
- USB 2.0 full speed controller and embedded analog transceiver
- DMA controller, RTC, CRC calculation unit, EXTI

What I would have to implement in the schematics/layout:

- External high and low speed crystal for timing
- USB connector
- Some form of user interface and control, such as buttons
- Power regulation

## Takeaways

TBD, will put in what I learned as a whole from the project here.
