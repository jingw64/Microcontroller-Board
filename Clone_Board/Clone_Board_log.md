# Clone Board

For the very first board of the project, I will be cloning a microcontroller board of my choosing to learn about the design choices behind a microcontroller, the necessary subsystems and components, and general concepts in this specific corner of ECE.

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

#### Tasks Accomplished {#2}

- I looked things up pertaining to essential parts of a microcontroller board and what types of boards there are
- Got a better idea of what I wanted to do for the project

#### Thoughts {#2}

For a bit I was wondering whether or not I should make a completely custom board or if I should clone a board that's already on the market, but the more I thought about it the more I got lost because I felt that if I wanted to make a custom board, I'd need to know what I'd want it to do so I'll know what to put on it other than the absolutely essential components.

I've come to the conclusion that it might be better to split this project into phases:

1. Clone a board of my choosing and learn about the design choices on the way (learn about things like decoupling capacitors, pull up/down resistors, LDOs, linear regulators, etc.)
2. Tweak the board for a custom purpose (ideally, I'd have figured out a specific project that can utilize the board by this point)
3. Graduate to making a fully custom microcontroller board I guess

Right now, I am eyeing the STM32 (for specific families, probably the STM32F1 or STM32G4 for more general purpose uses; will need to look into this more). It is the industry standard and said to be the easiest MCU to get started with for embedded.

#### Up Next {#2}

- [x] Reorganize and rename certain project files
- [x] Update readme with more clearly defined goals and ideas for project
- [x] Find STM32 data sheets and schematics to copy
  - [ ] Figure out necessary footprints for KiCad if needed
- [x] Look into STM32 families and their distinct purposes
- [ ] Look into integration of communication protocols like I2C, SPI, CAN, etc. on boards (just out of curiosity, nothing urgent)
  - [ ] Figure out if UART is a protocol or if it's some other thing because what the hecky
- [ ] Start on the schematic

---

### 08.10.2026

#### Tasks Accomplished {#3}

- Set up a dictionary for terms because ts is getting to be too much...
- Looked around for types of STM32 dev boards to clone, def learned a little bit
  - Currently looking at NUCLEO-L412RB, STM32G0316-DISCO, NUCLEO-F401RE, STM32F401 "Black Pill"
- Figured out where to go to get dev board data sheets/schematics, same for raw chips
- Found out you can use Latex commands in markdown files $\int_{T_i}^{T_f}\frac{C_v}{T}dT$

#### Thoughts {#3}

This kinda sucks ughawfajfwpw

I want to pick a dev board that's not too complicated (which all the nucleo boards seem to not be), but the black pill needs an external hardware debugger called an ST-LINK, and when I tried to go down that rabbit hole I just got lost because there are counterfeits everywhere and a lot of the ones like the ST-LINK/V2 are supposedly outdated??? And I haven't seen anything about a V3????

The G0316-DISCO on the market comes with a built in ST-LINK interface, but if I were to clone it it seems like I'll need to remove the interface from an already existing board to put onto the clone, meaning I'll have to buy another dev board with the interface (they're like upwards of $20-30 which I guess can be considered a fair price but I have no income so I want to limit costs as much as possible). I'll have to see if they have a BOM with links that I can look at or something.

Anyways I think this is gonna take a lot longer than I thought it would and I'm a lil bit scared

#### Up Next {#3}

- [x] Look into ST-LINK
  - [ ] Try to see if I can purchase an interface so that I don't have to buy the product itself
- [ ] For the love of god please let me settle with a dev board and get started on schematics I still have to figure out firmware stuff later please I'm begging
- [x] Define some terms in the dictionary
- [x] Update the overview for clone board with an accurate description and relevant links

---

### 08.16.2026

#### Tasks Accomplished {#4}

- Settled on STM32F401CEU6 to make black pill
- Data sheeten readen
- Finished wiring up decouplings for the chip itself
- Wired up boot0 and nrst using switches, but might swap them out with buttons instead
- Learned a bit about decoupling capacitors and pull up/down resistors yay!

*Note: Most of this was done on 08.12.2026. File updating and organization was done on 08.15/08.16 (it's currently 1:25 am)*

#### Thoughts {#4}

Data sheet reading is pain

#### Up Next {#4}

- [ ] Add the things for USB connection next
- [x] Update some files
- [ ] Look into what else I need to add to the schematic
