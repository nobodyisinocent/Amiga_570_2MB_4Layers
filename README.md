# A750 2MB Memory Board 4 layers PCB
4 Layers PCB of the 2MB memory board for the A570 CD-ROM expansion which converts an Amiga 500 into a CDTV.

# Table of contents
1. [3D picture of the PCB](#3D-View)
2. [Why a four layers PCB](#Why)
3. [PCB assembled and installed into the A570 CD](#Pictures)
4. [About the project files](#About-the-project-files)
6. [BOM](#BOM)


# 3D picture of the PCB <a name="3D-View"></a>

![PCB Board](https://user-images.githubusercontent.com/80821708/143296017-c496af39-76a1-4e35-8a8e-abc80ebff179.png)
The PCB of the 2MB board !

# Why a four layers PCB <a name="Why"></a>
Four layers with two internal power layers (one GND & one VCC) is better for having the best stability possible.

The original project is a two layers PCB designed by Daleking. Its link is available here:
https://github.com/daleking/Amiga_A570_2MB

# PCB assembled and installed into the A570 CD <a name="Pictures"></a>
Here, soon, you'll see pictures of the memory board assembled !

# About the project files <a name="About-the-project-files"></a>

The complete project of this four layers PCB is available here for downloading.

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
