# A750 2MB Memory Board 4 layers PCB
4 Layers PCB of the 2MB memory board for the A570 CD-ROM expansion which converts an Amiga 500 into a CDTV.

# Table of contents
1. [Pcicture of the PCB in Kicad](#3D-View)
2. [Why a four layers PCB](#Why)
3. [PCB assembled and installed into the A570 CD](#Pictures)
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

# PCB assembled and installed into the A570 CD <a name="Pictures"></a>
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

The complete project of this four layers PCB is available onto this repository for downloading.

The pcb has been designed with Kicad under Linux: https://www.kicad.org/

# BOM <a name="BOM"></a>
Here is the BOM made by Lolof. Thanks to him !

|Id	|Designator	|Package	|Quantity	|Designation	|Reichelt part number	|Link  |
|---|---|---|---|---|---|---|
|1	|D1,D2      |	D_DO-41_SOD81_P7.62mm_Horizontal	|2	|UF10-005	|UF 4003	|https://www.reichelt.de/de/fr/diode-de-redressement-ultrarapide-do41-200-v-1-a-uf-4003-p42034.html |
|2	|D3 to D8   |	D_DO-35_SOD27_P7.62mm_Horizontal	|6	|1N4150	|1N 4148	|https://www.reichelt.de/de/fr/diode-de-commutation-100-v-150-ma-do-35-1n-4148-p1730.html |
|3	|Q1,Q2	    |TO-18-3	|2	|2N2222A	|2N 2222A	|https://www.reichelt.de/de/fr/transistor-npn-to-18-40-v-0-8-a-0-5-w-2n-2222a-p1968.html |
|4	|R1,R3	    |R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal	|2	|1K	METALL |1,00K	|https://www.reichelt.de/de/fr/r-sistance-film-m-tallique-de-1-00-kohms-metall-1-00k-p11403.html?r=1 |
|5	|R2,R4	    |R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal	|2	|3K3	METALL |3,30K	|https://www.reichelt.de/de/fr/r-sistance-film-m-tallique-de-3-30-kohms-metall-3-30k-p11693.html?&trstct=pos_0&nbc=1 |
|6	|U1 |DIP-40_W15.24mm	|1	|ZIF HEADER| |  |
|7	|ZIF-HEADER	|DIP-28_W15.24mm	|1	|ZIF|	|  |
