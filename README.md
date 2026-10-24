# Mini Keyboard

A mini keyboard with 4 mechanical switches, a rotary encoder and 7 RGB LEDs. I designed the PCB and modeled the case myself.

I don't need funding for this project.

## How I made it

I designed a mini keyboard with 4 switches, an encoder and 7 LEDs. First I designed the schematic.

![Schematic](https://github.com/user-attachments/assets/930d395e-9aec-416e-b555-5844c37303d3)

Then I designed the PCB, synchronized the footprints and wired everything up following guides from the internet and Claude. Unfortunately I had the LEDs on the wrong side, so I had to flip all of them and rewire most of the design.

![PCB layout](https://github.com/user-attachments/assets/dbf85efd-2e5a-41df-bdd2-a97cec05c6bf)

Then I exported the 3D model of the design and dropped it into Fusion.

![PCB 3D model in Fusion](https://github.com/user-attachments/assets/d41c7c44-ba11-4d8a-a28a-d101590abdd4)

After that I started modeling the case in Fution .

![Case modeling](https://github.com/user-attachments/assets/9bfbd178-73ac-4fbb-8e49-ff0f38f0d8a2)

I designed 5 parts: the main case, the mounting plate, the lid, the encoder knob and the USB-C support.

![Case design 1](https://github.com/user-attachments/assets/85c9f51c-b986-42fc-ae0c-173d24438f84)
![Case design 2](https://github.com/user-attachments/assets/cc39f520-c644-40f6-9c2e-3fe726a5d28c)
![Case design 3](https://github.com/user-attachments/assets/8a0b6474-b307-4adf-8b29-c4bd37d481fc)
![Case design 4](https://github.com/user-attachments/assets/daa1787d-085e-48fc-9d8b-a9b4e398073b)
![Case design 5](https://github.com/user-attachments/assets/08c01ebe-c286-423a-8855-4f6ff2245328)

I found the switch models online, downloaded them and imported them into Fusion.

Lastly, I added clearances: 0.3 mm between the PCB and the case and between the case and the mounting plate, 0.15 mm between the case and the lid (for a snug fit), and 0.15 mm between the encoder knob and the encoder.

## Bill of Materials

| Reference | Component | Qty | Part | Manufacturer | MPN |
|---|---|---|---|---|---|
| U1 | Microcontroller | 1 | Seeed XIAO RP2040 | Seeed Studio | 102010428 |
| SW1-SW4 | Key switches | 4 | MX-style switch | Gateron | KS-3Y10B050NW-X1 |
| SW5 | Rotary encoder | 1 | EC11E (vertical, with push switch) | Alps Alpine | EC11E |
| D3-D9 | RGB LEDs | 7 | SK6812 MINI-E | Worldsemi | SK6812MINI-E |
| - | Keycaps | 4 | - | - | - |
| - | Encoder knob | 1 | 3D printed | - | - |
| - | PCB | 1 | Custom 2-layer, designed in KiCad | - | - |
| - | Case | 1 | 3D printed: case, mounting plate, lid, USB-C support | - | - |

The same list is in `BOM.csv`.

Also lasty here is  the full 3d design for Autodesk fution

