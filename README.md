# Stealthburner_LGX_Mount
## Introduction
![StealthBurner_LGX_Mount.png](./Images/StealthBurner_LGX_Mount.png)
I didn't find a mounting with some bells and whistles I wanted to use my LGX with the Stealthburner. Then I designed my own.

It should be compatible with both versions of rail carriage. The one we screw on the back (Afterburner carriage with CW1) and the one we screw on the front (Stealthburner carriage with CW2). I only fully tested with the Stealthburner carriage.

The 3D printed parts may not follow the Voron design recommendations.

All photos are not of the same design iteration. I didn't want to shoot the whole sequence of the mounting each time I improved the parts.

## Parts
3D printed:

- Mounting

| Filename                  | Description          |
|---------------------------|----------------------|
| LGX-Mount-SW-rxxx - 1.STL | Mounting part 1      |
| LGX-Mount-SW-rxxx - 2.STL | Mounting part 2      |
| LGX-GearCover-rxxx.STL    | LGX gear wheel cover |
- Cover

| Filename | Description |
|---|---|
| [a]_LGX_Stealthburner_Cover-rxxx - noPCB.STL | Stealthburner side cable cover - noPCB version |
| [a]_LGX_Stealthburner_Cover-rxxx - PCB-1.STL | Stealthburner side cable cover - PCB version |
| [a]_LGX_Stealthburner_Cover-rxxx - PCB-2.STL | Stealthburner side cable cover spacer - PCB version |

For the moment Cover PCB version files are useless because it is not possible to mount the PCB on the mounting. I may try to make it possible.

Additional hardware:
- M3x20 (x2). SHCS / ISO 4762 recommended
- M3x30 (x2). SHCS / ISO 4762 recommended (M3x25 is enough for the screws on the back mounting)
- M3x6 (x1). FHCS / ISO 10642 recommended
- M3 Heat insert (x3).

## LGX Mounting
![001.jpg](./Images/001.jpg)
Put insert in the 3 holes.

Take care to get the insert quite well straight. It is for the Stealthburner to move easily along the M3x25 screws afterward when you want to swap the toolhead.

The insert on the left (of the photo) edge is to screw a future cover.

![001-3.jpg](./Images/001-3.jpg)
In case you want to use the rail carriage that has holes to screw on the back (CW1), add two more inserts in the back of the part.

![002.jpg](./Images/002.jpg)
    Add the back of the mounting. It should fit on the rectangular joint. Later, it doesn't have to be separated from the mounting. Then I choose to glue it but it is really not mandatory.

![003.jpg](./Images/003.jpg)
Screw the bottom with 2 M3x20.

![004.jpg](./Images/004.jpg)
Screw the front with the provided Bondtech LGX M3x27.

![005.jpg](./Images/005.jpg)
There is a hole in the front of the mounting to check if the PTFE tube go well to the top of the mounting.

![006.jpg](./Images/006.jpg)
Screw the mounting on the carriage with 2 M3x30.

![006-2.jpg](./Images/006-2.jpg)
In case you want to use the rail carriage that has holes to screw on the back (CW1), screw the mounting on the carriage with 2x M3x25 or 2x M3X30.

![007.jpg](./Images/007.jpg)
Pass the Stealthburner wires with their connectors in the right square hole.

![008.jpg](./Images/008.jpg)
All 3 connectors passed.

![009.jpg](./Images/009.jpg)
Screw few turns the Stealthburner M3x25 to hold it.

![010.jpg](./Images/010.jpg)
Once the connectors are passed, you can screw the LGX wheel cover with a M3x6. I use a FHCS one.

![011.jpg](./Images/011.jpg)
Mount the toolhead. Take attention to not pinch the toolhead wires between the Stealthburner and its mounting when tighning the whole.

![012.jpg](./Images/012.jpg)
Voil??.

## Cover
Based on wile.e1 cover for Stealthburner and CW1 (https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/wile-e1/Stealthburner_CW1_PCB_Cover)
![013.jpg](./Images/013.jpg)
Screw: M3x8. M3x6 works too.
Two version:
- One with a PCB feature. It is just an adaptation from the original design but as for now it is not possible to mount the PCB, The PCB version is useless. Will try to make it possible.
- One without PCB feature (noPCB).