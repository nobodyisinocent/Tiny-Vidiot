# Tiny-Vidiot
A very low profile vidiot module for Amiga

# Table of contents
1. [Why an another Vidiot](#1)
2. [Pictures of the PCB in Kicad](#2)
3. [Why a four layers PCB](#3)
4. [PCB assembled](#4)
5. [About the project files](#5)
6. [BOM](#6)

# Why an another Vidiot <a name="1"></a>

THe schematics of the Tiny-Vidiot is the same as the one from Sukkopera, and so the same of the one from a1k.org.

So why ? Because we (Lolof, Seb132 and I) have decided to design the littlest Vidiot module ever made to allow us to install expansions into the Amiga without any contrainst.

To obtain the littlest pcb possible, the two followings thinks were decided:
  - Components are 0603 footprints,
  - The Tiny-Vidiot pcb is a four layers. One internal layer is for GND while the second internal layer is for VCC power signals.

# Pictures of the PCB in Kicad <a name="2"></a>

# PCB assembled <a name="4"></a>
Pictures of the Tiny-Vidiot here soon.

# About the project files <a name="5"></a>

The complete project of this four layers PCB is available here for downloading.

The pcb has been designed with Kicad under Linux: https://www.kicad.org/

To make this pcb, I did not wear out the planet or try to reinvent the wheel... I simply used the Kicad project made by Sukkopera.

The Sukkopera project is available here:
https://github.com/SukkoPera/OpenAmigaVideoHybrid

# BOM <a name="6"></a>

|Id	|Designator	|Package	|Quantity	|Designation	|Link  |
|---|---|---|---|---|---|
|1	|U1 to U4      |	SOJ	|4	|HM514400CS7 | ebay, utsource & aliexpress are your friends ! |
|2	|C1 to C4   |	SMD 0805	|4	|	|https://www.reichelt.com/fr/en/index.html?ACTION=446&LA=446&nbc=1&q=100%20nf%20g0805 |
|3	|CN1	    |Female right angle 2x20 pin header		|1 |	|https://de.aliexpress.com/item/32758316130.html |
|4	|Jumper    |Male right angle 1x02 pin header	|1	|	|https://fr.aliexpress.com/item/4000694229610.html |

