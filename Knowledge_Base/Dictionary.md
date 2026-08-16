# Dictionary

This is where I write down all the new terms and acronyms I come cross. Not organized in any particular order.

**UART / USART**
: Universal Synchronous/Asynchronous Receiver Transmitter; hardware block/circuit that allows two devices to share serial data (data sent one bit at a time) with or without a shared clock (without a clock, data is timed on a baud rate, which is a set speed). Also translates data between serial and parallel (many bits at a time) forms.

**RTOS**
: Real Time Operating System; specialized OS that handles tasks that are time-sensitive with precise timing constraints.

**ST-LINK**
: A hardware debugger from the same company that produces the STM32 chips. Allows you transfer compiled code directly to the flash memory. Comes either as a dongle or built directly onto the board.

**Bare metal (ex. bare metal programming)**
: definition

**SWD**
: Serial Wire Debug; 2-pin interface used to program and debug ARM microcontrollers, so flashing firmware, reading/writing memory, etc.

**Bootloader**
: A small program that essentially starts up devices. Generally, in puters, the order is: BIOS turns on hardware and performs checks, passes things to bootloader, bootloader finds OS and loads it into memory, some other stuff happens that maybe I'll get into sometime in the future, and passes control to OS, puter starts.

**RTC**
: Real time clock; a specialized chip that keeps track of current time and date. Runs on very low power.

**OTG**
: On The Go; something that allows things like microcontrollers and embedded systems to connect to other USB devices, turning it into a host device.

**FS**
: Full Speed; refers to the 12Mbps throughput tier. Contrary to its name it is not the fastest (the fastest would be high speed, which has a throughput of 480Mbps). Ideal for low-rate data logging, audio streaming, and basic control communication. Consumes less power and requires less hardware complexity.

**EXTI**
: definition

**DMA**
: Direct Memory Access; a hardware component that transfers data between RAM and I/O devices. Handled independently from the CPU, which frees up space for it to complete other tasks.

**CRC**
: Cyclic Redundancy Check; hardware that checks data integrity during transmission and storage by taking bytes and performing some math on them to output a fixed-length remainder. The remainder is compared against an expected value to detect data corruption and errors.
