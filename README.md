# Tiny-Vidiot
Here are two versions of a very low profile vidiot module for Amiga !
Gerber files are available.
The Kicad project will be also available very soon.

# Table of contents
1. [Why an another Vidiot](#1)
2. [Pictures of the PCB in Kicad](#2)
3. [PCB assembled](#3)
4. [About the project files](#4)
5. [BOM](#5)

# Why an another Vidiot <a name="1"></a>

THe schematics of the Tiny-Vidiot is the same as the one from Sukkopera, and so the same of the one from a1k.org.

So why ? Because we (Lolof, Seb132 and I) have decided to design the smallest Vidiot module ever made to allow us to install expansions into the Amiga with the smallest possible constraints.

To obtain the littlest pcb possible, the two followings thinks were decided:
  - Components are 0603 footprints,
  - The Tiny-Vidiot pcb is a four layers. One internal layer is for GND while the second internal layer is for VCC power signals.

# Pictures of the final PCB in Kicad <a name="2"></a>

Tiny-Vidiot version. 12.4mm wide PCB !
![image](https://user-images.githubusercontent.com/80821708/213568383-35f6042e-cdbf-44e3-9c6a-240d0060f56b.png)

![image](https://user-images.githubusercontent.com/80821708/213568646-11a295ff-2300-4434-ad6a-f0e54becd8ca.png)

And the Mini version of the Tiny-Vidiot. 10.4mm wide PCB !

![image](https://user-images.githubusercontent.com/80821708/213570336-721f3a78-cb72-436e-a560-116a93786419.png)

![image](https://user-images.githubusercontent.com/80821708/213570677-b04bc635-df9a-4f88-a3f0-f05f26aa861e.png)

# PCB assembled <a name="3"></a>

Pictures of the assembled prototype (thanks to Lolof for the pictures)
![IMG_3140](https://user-images.githubusercontent.com/80821708/213567397-c4a8a1f8-dc9e-40f4-9552-731b9c4371af.jpg)

![IMG_3141](https://user-images.githubusercontent.com/80821708/213567418-fe9c2d24-4b66-4a82-8015-57d3b7310136.jpg)

![C=_vs_TinyVidiot](https://user-images.githubusercontent.com/80821708/213567445-dfd29cc0-e84f-4822-a7b8-ce808b918b36.jpg)

![IMG_3124](https://user-images.githubusercontent.com/80821708/213567731-bf22ae6f-379d-4df1-8ad6-de846a88ae92.jpg)

![IMG_3126](https://user-images.githubusercontent.com/80821708/213567756-c26bacb2-14e1-49d0-84ea-3370266fc0fc.jpg)

# About the project files <a name="4"></a>

The complete project of this four layers PCB is available here for downloading.

The pcb has been designed with Kicad 5.1.12 (https://www.kicad.org/) under Linux Mint XFCE Edition (https://linuxmint.com/).

To make this pcb, I did not wear out the planet or try to reinvent the wheel... I simply used the Kicad project made by Sukkopera.

The Sukkopera project is available here:
https://github.com/SukkoPera/OpenAmigaVideoHybrid

# BOM <a name="5"></a>

Please note you'll find into the archive the README_SukkoPera.md file with mention about the evolution of the BOM.

|Id	|Designator	|Package	|Quantity	|value	|
|---|---|---|---|---|
|1	|C5,C4,C3,C2,C1 |0603 | 5	| 100nF |
|2	|R12,R20,R4   |	0603 	| 3	|	8k |
|3	| R16,R24,R29,R39,R8,R23,R15,R7	    | 0603	| 8 |75R|
|4	|  R17,R9,R1,R25  | 0603	| 4	| 1k	|
|5  |R18,R10,R2 |0603|3|2k|
|6  |R19,R11,R3 |0603|3|4k|
|7  |R26,R36  |0603|2|220R|
|8  |R31,R34  |0603|2|37.4k|
|9  |R37,R38  |0603|2|36R|
|10 |R35  |0603|1|19.6k|
|11 |R30  |0603|1|90.9K|
|12 |R28  |0603|1|150R|
|13 |R27  |0603|1|27k|
|14 |R22,R14,R6|0603|3|390R|
|15 |R21,R13,R5|0603|3|470R|
|16 |R33  |0603|1|6.04k|
|17 |R32  |0603|1|13.3k|
|18 |Q1,Q2,Q3,Q4,Q5|SOT-23|5|2N3904|
|19 |Q6 |SOT-23|1|2N3906|
|20 |J1 |Pin_Header_Right_angled_1x22_Pitch2.54mm|1| |

