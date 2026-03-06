# BoosteR-CDE (my version)

![](https://github.com/lucadentella/CS4/raw/main/images/foto.jpg)

## Description

[BoosteR-CDE](https://usuaris.tinet.cat/fmco/railcom_en.html#booster) is a great DCC booster designed by my friend Paco Cañada.

I took its schematics and designed a board in EasyEDA, to be able to order PCBs and parts from online services (JLCPCB, Aliexpress...).

This repository contains my version of the booster, **I'm not copying here** the *firmware* and the user manual, both are available on Paco's [official website](https://usuaris.tinet.cat/fmco/download_en.html).

## Board

![](https://github.com/lucadentella/CS4/raw/main/images/3drender.png)

 - [Schematics (pdf)](https://github.com/lucadentella/BoosteR-CDE/blob/main/board/schematics.pdf)
 - [Gerber files for PCB manufacturing (zip)](https://github.com/lucadentella/BoosteR-CDE/raw/main/board/gerber.zip)
 
## Part list

| Designator | Part | Value | Note |
|---|---|---|---|
| C1,C2 | Capacitor | 2200uF 35V | Aluminum Electrolytic |
| C3,C4 | Capacitor | 100uF 35V | Aluminum Electrolytic |
| C5,C7 | Capacitor | 100nF | Polypropylene |
| C6 | Capacitor | 47uF | Aluminum Electrolytic |
| C8 | Capacitor | 220nF | Polypropylene |
| C9,C10 | Capacitor | 15nF | Polypropylene |
| C11 | Capacitor | 22nF | Polypropylene |
| D1,D2,D3,D4 | Diode | BY255 |  |
| D5 | Diode | 1N4007 |  |
| D6 | Diode | 1N4148 |  |
| LED1 | LED | 5mm | color at your choice |
| R1 | Resistor | 220 | THT 1/4W |
| R2 | Resistor | 2.2K | THT 1/4W |
| R3 | Resistor | 1K | Adjustable, 3362P|
| R4,R5,R6,R7 | Resistor | 1K | THT 1/4W |
| R8 | Resistor | 470 | THT 1/4W |
| R9 | Resistor | 0.22 | THT 5W |
| R10 | Resistor | 10K | THT 1/4W |
| R11 | Resistor | 3.3 | THT 1/4W |
| U1 | LM350T |  |  |
| U2 | L7805 |  |  |
| U3 | PC817 |  |  |
| U4,U5 | 6N137 |  |  |
| U6 | PIC12F629 |  |  |
| U7 | L6203 |  |  |