# TVZSolderingPracticeKit

## About

This project is a custom-designed printed circuit board (PCB) developed as an educational tool to help students practice and develop through-hole device (THD) soldering skills. The board integrates simple but functional electronic circuits, centered around the NE555 timer IC, to provide hands-on learning in both soldering and basic circuit operation.

## Functional Overview:

<p align="center">
  <img src="https://github.com/jkordek1/TVZSolderingPracticeKit/blob/main/Images/PCB.png?raw=true">
</p>

Powered with 9V battery via barrel jack and adapter.

NE555 Piano Buzzer Circuit:
- Based on the NE555 timer configured in astable mode.
- Drives a buzzer to generate audible tones, simulating a simple piano key.

Charge/Discharge with LED Indicators:
- A basic RC charge/discharge circuit is included to illustrate capacitor behavior.
- LEDs serve as visual indicators for charging and discharging states.

Dummy Passive Component Sections:
- Includes extra pads for resistors, capacitors, and diodes with no critical function—used purely for soldering practice.
- These sections allow repeated practice without impacting circuit operation.

High-Current Trace Design:
- Selected traces are widened to demonstrate PCB design practices for handling higher currents.
- Offers insight into power and thermal considerations in PCB design.

Design considerations:
- Clearly Labeled Silkscreen: Component values and orientation are printed to assist students during assembly.
- Educational Layout: Segmented functional blocks help isolate and explain circuit behavior.

## Fabrication layer

For PCB assembly, use the Fabrication.html file, which includes an easy-to-use Bill of Materials (BOM) with checkmarks. This file can be opened in any web browser.

<p align="center">
  <img src="https://github.com/jkordek1/TVZSolderingPracticeKit/blob/main/Images/PCB-Fabrication-Front.png?raw=true">
</p>

## Bill of materials (BOM)

| Reference                       | Value             | Qty | TME Part Number    |
|---------------------------------|-------------------|-----|--------------------|
| BZ1                             | LD-BZEN-1205      | 1   | LD-BZEN-1205       |
| C1                              | 100n              | 1   | CCT-100N/50V-S     |
| C2                              | 470u / 50V        | 1   | EEUFR1E471         |
| D1                              | SR150-DC          | 1   | SR150-DC           |
| D2                              | RED               | 1   | 1383-2SURD/S530-A3 |
| D3                              | YELLOW            | 1   | 1383UYD/S530-A3    |
| D4                              | GREEN             | 1   | 1383SYGD/S530-E2   |
| D5                              | WHITE             | 1   | INL-5AW30          |
| J1                              | Barrel Jack       | 1   | DCJ250-10-A-K1-K   |
| J2                              | Conn_01x05_Pin    | 1   | PH1RB-40-UA        |
| J3                              | Conn_01x05_Socket | 1   | ZL262-5SG          |
| J4,J5                           | Conn_01x03_Pin    | 2   | ZL201-03G          |
| J6                              | JUMPER-H/R        | 1   | JUMPER-H/R         |
| J7                              | JUMPER-H/B        | 1   | JUMPER-H/B         |
| R1                              | 1k5               | 1   | 1/4W1.5K           |
| R2                              | 1k3               | 1   | 1/4W1.3K           |
| R3                              | 620               | 1   | 1/4W620R           |
| R4                              | 1k1               | 1   | 1/4W1.1K           |
| R5,R9                           | 1k                | 2   | 1/4W1.0K           |
| R6                              | 910               | 1   | 1/4W910R           |
| R7                              | 390               | 1   | CF1/4W-390R        |
| R8                              | 6k2               | 1   | 1/4W6.2K           |
| R10                             | 4k7               | 1   | 1/4W4.7K           |
| R11,R15                         | 2k2               | 2   | 1/4W2.2K           |
| R12,R13,R14                     | 2k2               | 3   | 1/4W2.2K           |
| RV1                             | 10k               | 1   | RK09K1130AH1       |
| SW1,SW2,SW3,SW4,SW5,SW6,SW7,SW8 | SW_Push           | 8   | TACT-64K-F         |
| SW10                            | POWER             | 1   | OS102011MS2QN1     |
| SW11                            | C/D               | 1   | OS102011MS2QN1     |
| U1                              | NE555P            | 1   | NE555P             |
| U2                              | ~                 | 1   | ICVT-8P            |
| U3                              | ~                 | 1   | BAT-6F22L/U-SH     |
| U4,U5,U6,U7                     | ~                 | 4   | B2.5X5/BN2724      |
| U8,U9,U10,U11                   | ~                 | 4   | B3/BN116           |

