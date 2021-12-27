# A750 2MB Memory Board 4 layers PCB
4 Layers PCB of the 2MB memory board for the A570 CD-ROM expansion which converts an Amiga 500 into a CDTV.

Gerber files already uploaded.
The project files will be uploaded here very soon.

# Table of contents
1. [Pictures of the PCB in Kicad](#3D-View)
2. [Why a four layers PCB](#Why)
3. [PCB assembled and installed into the A570 CDROM](#Pictures)
4. [About the project files](#About-the-project-files)
6. [BOM](#BOM)


# Pictures of the PCB in Kicad <a name="3D-View"></a>

Front (Components) layer

![Layer-1](https://user-images.githubusercontent.com/80821708/144846552-b889925a-0a85-4bc6-98f6-5b099e9fbbf8.png)


GND layer

![Layer-GND](https://user-images.githubusercontent.com/80821708/144846600-be56b236-0c7d-4ead-a12e-6e39ea7debb7.png)


VCC layer

![Layer-VCC](https://user-images.githubusercontent.com/80821708/144846642-ec702289-324c-4af5-a55f-34ef19cbf1cc.png)


Back layer

![Layer-4](https://user-images.githubusercontent.com/80821708/144846665-0a8b7b74-a93e-4939-b370-0913f63c6b76.png)


The PCB in the 3D Viewer

![PCB Board](https://user-images.githubusercontent.com/80821708/143296017-c496af39-76a1-4e35-8a8e-abc80ebff179.png)


# Why a four layers PCB <a name="Why"></a>
Four layers with two internal power layers (one GND & one VCC) is better for having the best stability possible.

The original project is a two layers PCB designed by Daleking. Its link is available here:
https://github.com/daleking/Amiga_A570_2MB

# PCB assembled and installed into the A570 CDROM <a name="Pictures"></a>
Some pictures of the A570 2MB momory board assembled and installed onto the A570 CDROM.
These pictures are from from m0c aka m0xz0r. Thanks a lot to him. :-)

![15faa6ae-da2f-4164-a6cd-629f1fc4fd1c](https://user-images.githubusercontent.com/80821708/144842788-84bfdbd2-ab74-42bf-ad99-5dc1440e5b1c.jpg)

![b0e7dbab-04ca-4b85-99ef-c1e41b9204f9](https://user-images.githubusercontent.com/80821708/144842804-5cb29aba-1196-4da6-b4dc-c791981640f1.jpg)

![9915e4c3-17a2-4d65-bf34-2be298b24b1e](https://user-images.githubusercontent.com/80821708/144842822-8e6b936b-0593-4f97-9a1e-8dd36ebe716b.jpg)

As you can see onto the pictures, the capacitors aren't soldered. It's just for the test. These cpacitors are necessary for the decoupling.
If you assemble this expansion, the capacitors will have to be soldered to obtain the best stability possible.

Onto the pictures below, you can see that the board is runing fine.

![e344f33f-6bc1-4d67-80e5-30b79a5ca414_resultat](https://user-images.githubusercontent.com/80821708/144845169-d863cc11-b604-4ac4-9f58-cd29576e6098.jpg)

![09afdfdb-9596-4fb6-b5c1-57d9b2bf31d9_resultat](https://user-images.githubusercontent.com/80821708/144845212-6089620d-be7b-4f04-91cf-b438df2819f3.jpg)

![4a56a2eb-dcbc-4c56-8fea-7ce89a8caf47_resultat](https://user-images.githubusercontent.com/80821708/144845224-fdd5442d-cdc6-4ffe-b444-3d7a3825a4cd.jpg)

# About the project files <a name="About-the-project-files"></a>

The complete project of this four layers PCB will be available very soon onto this repository for downloading.

The pcb has been designed with Kicad under Linux: https://www.kicad.org/

# BOM <a name="BOM"></a>
The BOM will be available here very soon. :-)

|Id	|Designator	|Package	|Quantity	|Designation	|Link  |
|---|---|---|---|---|---|
|1	|U1 to U4      |	SOJ	|2	|HM514400CS7 |	|ebay, utsource & aliexpress are your friends ! |
|2	|C1 to C4   |	SMD 1206	|4	|	|https://www.reichelt.com/fr/en/index.html?ACTION=446&LA=446&nbc=1&q=100%20nf%20g1206 |
|3	|CN1	    |Female right angle 2x20 pin header		|1 |	|https://de.aliexpress.com/item/32758316130.html |
|4	|Jumper    |Male right angle 1x02 pin header	|1	|	|https://fr.aliexpress.com/item/4000694229610.html |

