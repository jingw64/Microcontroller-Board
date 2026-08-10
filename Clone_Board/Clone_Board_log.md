# Clone Board

For the very first board of the project, I will be cloning a microcontroller board of my choosing to learn about the design choices behind a microcontroller, the necessary subsystems and components, and general concepts in this specific corner of ECE.

## Takeaways

TBD, will put in what I learned as a whole from the project here.

## Daily Log

I will record what I do for this specific project, the date, and any thoughts I have here. Anything that I do/learn that I think deserves to be highlighted will have a link to that specific section.

---

### 08.08.2026

#### Tasks Accomplished

- Figured out that I wanted to make my own microcontroller board
- Set up a github repo and connected it to VSC for easy access and management
- Remembered how to use git commands
- Found a couple sources to get started on thinking about the project

#### Thoughts

I'm cooked, man.

#### Up Next

- [x] Research what needs to go into a microcontroller board and write/update documentation accordingly
  - No specified goal for research for now; go wherever the rabbit hole takes me tomorrow and figure things out from there

---

### 08.09.2026

#### Tasks Accomplished

- I looked things up pertaining to essential parts of a microcontroller board and what types of boards there are
- Got a better idea of what I wanted to do for the project

#### Thoughts

For a bit I was wondering whether or not I should make a completely custom board or if I should clone a board that's already on the market, but the more I thought about it the more I got lost because I felt that if I wanted to make a custom board, I'd need to know what I'd want it to do so I'll know what to put on it other than the absolutely essential components.

I've come to the conclusion that it might be better to split this project into phases:

1. Clone a board of my choosing and learn about the design choices on the way (learn about things like decoupling capacitors, pull up/down resistors, LDOs, linear regulators, etc.)
2. Tweak the board for a custom purpose (ideally, I'd have figured out a specific project that can utilize the board by this point)
3. Graduate to making a fully custom microcontroller board I guess

Right now, I am eyeing the STM32 (for specific families, probably the STM32F1 or STM32G4 for more general purpose uses; will need to look into this more). It is the industry standard and said to be the easiest MCU to get started with for embedded.

#### Up Next

- [ ] Reorganize and rename certain project files
- [ ] Update readme with more clearly defined goals and ideas for project
- [ ] Find STM32 data sheets and schematics to copy
  - [ ] Figure out necessary footprints for KiCad if needed
- [ ] Look into STM32 families and their distinct purposes
- [ ] Look into integration of communication protocols like I2C, SPI, CAN, etc. on boards (just out of curiosity, nothing urgent)
  - [ ] Figure out if UART is a protocol or if it's some other thing because what the hecky
- [ ] Start on the schematic
