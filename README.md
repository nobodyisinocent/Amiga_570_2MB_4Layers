# A570 2MB Memory Board 4 layers PCB
4 Layers PCB of the 2MB memory board for the A570 CD-ROM expansion which converts an Amiga 500 into a CDTV.

Gerber files already uploaded.
The project files will be uploaded here very soon.

# Table of contents
1. [Last Revision of the A570 2MB RAM expansion](#1)
2. [Pictures of the PCB in Kicad](#2)
3. [Why a four layers PCB](#3)
4. [PCB assembled and installed into the A570 CDROM](#4)
5. [About the project files](#5)
6. [BOM](#6)

# Last Revision of the A570 2MB RAM expansion <a name="1"></a>

Release Date: 10/01/2022

Distances between ICs are not the same,

The capacitors are now 0805 mounting form,

The pads of ICs footprints have been lengthened to facilitate the soldering of the ICs.

# Pictures of the PCB in Kicad <a name="2"></a>

Front (Components) layer

![Layer-1](https://user-images.githubusercontent.com/80821708/148837138-d1a8b375-6ec7-4138-aea1-799d3d1ba5c5.png)


GND layer

![Layer-GND](https://user-images.githubusercontent.com/80821708/148837190-e5bf6acf-7753-4f80-85a1-783b2b866673.png)


VCC layer

![Layer-VCC](https://user-images.githubusercontent.com/80821708/148837221-e7e1a17e-ea20-46fb-94e2-04f74e4c8e81.png)


Back layer

![Layer-4](https://user-images.githubusercontent.com/80821708/148837252-b53b4aa6-532a-4e85-a7dc-c155f12fe4ba.png)


The PCB in the 3D Viewer

![Capture d’écran_2022-01-10_22-15-49](https://user-images.githubusercontent.com/80821708/148840654-83552b57-806d-463a-8bea-bfe32286e967.png)

# Why a four layers PCB <a name="3"></a>
Four layers with two internal power layers (one GND & one VCC) is better for having the best stability possible.

The original project is a two layers PCB designed by Daleking. Its link is available here:
https://github.com/daleking/Amiga_A570_2MB

# PCB assembled and installed into the A570 CDROM <a name="4"></a>
Some pictures of the A570 2MB momory board assembled and installed onto the A570 CDROM.
These pictures are from from m0c aka m0xz0r. Thanks a lot to him. :-)

![Capture d’écran_2022-01-10_21-58-15](https://user-images.githubusercontent.com/80821708/148838726-770fdd8c-aa70-4734-90b2-16cb79261f94.png)

![Capture d’écran_2022-01-10_21-54-59](https://user-images.githubusercontent.com/80821708/148838758-2fbe66a6-0df1-4b3b-932d-c06703f070c9.png)

Onto the two pictures above, you can see the pcb with same distances between all ICs. If you take a look at the picture below, you'll see that the distance wasn't the same between the ICs...

![9915e4c3-17a2-4d65-bf34-2be298b24b1e](https://user-images.githubusercontent.com/80821708/144842822-8e6b936b-0593-4f97-9a1e-8dd36ebe716b.jpg)

As you can see onto the picture above, the capacitors aren't soldered. It's just for the test. These cpacitors are necessary for the decoupling.
If you assemble this expansion, the capacitors will have to be soldered to obtain the best stability possible.

Onto the pictures below, you can see that the board is runing fine.

![e344f33f-6bc1-4d67-80e5-30b79a5ca414_resultat](https://user-images.githubusercontent.com/80821708/144845169-d863cc11-b604-4ac4-9f58-cd29576e6098.jpg)

![09afdfdb-9596-4fb6-b5c1-57d9b2bf31d9_resultat](https://user-images.githubusercontent.com/80821708/144845212-6089620d-be7b-4f04-91cf-b438df2819f3.jpg)

![4a56a2eb-dcbc-4c56-8fea-7ce89a8caf47_resultat](https://user-images.githubusercontent.com/80821708/144845224-fdd5442d-cdc6-4ffe-b444-3d7a3825a4cd.jpg)

# About the project files <a name="5"></a>

The complete project of this four layers PCB will be available very soon onto this repository for downloading.

The pcb has been designed with Kicad under Linux: https://www.kicad.org/

# BOM <a name="6"></a>

|Id	|Designator	|Package	|Quantity	|Designation	|Link  |
|---|---|---|---|---|---|
|1	|U1 to U4      |	SOJ	|4	|HM514400CS7 | ebay, utsource & aliexpress are your friends ! |
|2	|C1 to C4   |	SMD 0805	|4	|	|https://www.reichelt.com/fr/en/index.html?ACTION=446&LA=446&nbc=1&q=100%20nf%20g0805 |
|3	|CN1	    |Female right angle 2x20 pin header		|1 |	|https://de.aliexpress.com/item/32758316130.html |
|4	|Jumper    |Male right angle 1x02 pin header	|1	|	|https://fr.aliexpress.com/item/4000694229610.html |

