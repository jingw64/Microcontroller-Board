# Microcontroller Basics

## Essential Components

- The chip - you need this for obvious reasons... can't develop anything without it because there's nothing for you to develop with
- GPIO pins - for communicating with external hardware
- USB interface - for connecting to your puter
- Voltage regulator - for stepping down voltage
- Clock oscillator - for synchronization of signals and instructions
  - Some chips have internal clocks and therefore do not need this (ATtiny85, CH32V003, STM32), but this is a separate thing to dive into
- Reset button - for resetting all operations when things go a little south

## Types of Boards

Brief desc. of boards that I thought might be good to use as reference for this project.

### Arduino UNO

Very beginner friendly, extensive documentation. Runs with an ATmega328P chip. Good for learning and very simple projects like basic automation, reading sensors, and controlling motors.

### Raspberry Pi Pico

Cheap and decently high performance. Runs with an RP2040 chip. Ideal for IoT projects and hardware control. Has programmable I/O, which are good for generating signals separate from the main CPU.

### ESP32

Common for hobbyist projects. Has built in bluetooth and wifi features, and is very fast and powerful compared to the Arduino UNO. Versatile in what IDEs you can program it in, has its own hall sensor, DACs, and communication protocol interfaces. Best used in IoT projects.

### STM32

Industry standard. Very customizable: you can configure clocks, registers, interrupt priorities, etc. to your liking. All of this can be done in the CubeIDE. Seems to be very generalist (I've seen people build keyboards with it). Extensive documentation but steep learning curve. [^1]

[^1]: It might be best to go with this one due to how it will get me to be more familiar with industry tools.
