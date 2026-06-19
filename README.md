# WT-UMI Hardware Guide

*Whole-Body Tactile UMI for Force-Supervised Humanoid Manipulation*

Thanks for checking out WT-UMI! This page includes the WT-UMI hardware CAD models and how to use them. See [https://wt-umi.github.io/WTUMI/](https://wt-umi.github.io/WTUMI/) for more info about the project.

## Bill of Materials

| Item | Quantity | Link | Price Per Unit (USD) |
|--------|--------|--------|--------|
| Unitree G1 EDU | 1 | [Unitree](https://shop.unitree.com/products/unitree-g1?srsltid=AfmBOooywuZiixrGhkgvL5SS5FZtO47X1lQXipC_o8SLUKqVyyMUXSf0) | By Quote |
| Bambu Labs PLA Basic Starter Classic Pack | 1 | [Bambu](https://us.store.bambulab.com/products/pla-basic-beginner-s-filament-pack) | 91.96 |
| eSUN TPU 95A 1kg Spool | 1 | [Amazon](https://a.co/d/0618Pq8b) | 23.99 |
| TouchTronix SensX 187 | 1 | [DigiKey](https://www.digikey.com/en/products/detail/touchtronix-robotics/SNX1117-SNS-01/29174650) | 950.00 |
| PCB | 1 | Included | |
| TouchTronix SensX 160 | 2 | [DigiKey](https://www.digikey.com/en/products/detail/touchtronix-robotics/SNX2008-SNS-01/29174648) | 369.00 |
| PCB | 2 | Included | |
| Waveshare USB to TTL Converter | 2 | [Waveshare](https://www.waveshare.com/usb-to-ttl.htm?srsltid=AfmBOooLo5CUwUNtYH6NzxOANTHLAckVCtbSQ9pF8hjKjUb2Lh8MXvgSwlg) | 6.49 |
| FlexiTac Sensor | 2 | Custom | By Quote |
| PCB | 2 | Custom | By Quote |
| Arduino Nano | 2 | [Amazon](https://a.co/d/06jfDjr3) | 25.70 |
| 32 Pin 0.5 Pitch FPC Cable | 4 | [Amazon](https://a.co/d/0dFpjsOI) | 7.59 |
| 32 Pin 0.5 Pitch FPC Connector | 4 | [Amazon](https://a.co/d/04K6ABs0) | 9.99 |
| 20A Silicone Rubber | 1 | [Amazon](https://a.co/d/04Qe01Qw) | 39.04 |
| PVC Backed Fabric | 1 | [Amazon](https://a.co/d/0bmkGth6) | 19.99 |
| M3 Screws | | [McMaster](https://www.mcmaster.com/products/screws/system-of-measurement~metric/socket-head-screws-2~/steel-socket-head-screws~~/thread-size~m3/) | |
| ├─ L 8mm | 22 | | 12.82 Per 100 |
| └─ L 22mm | 8 | | 13.29 Per 100 |
| M3 Nuts | 12 | [McMaster](https://www.mcmaster.com/products/nuts/hex-nuts-5~/hex-nuts-2~~/hex-nuts-5~material~steel-2/system-of-measurement~metric/thread-size~m3/) | 3.06 Per 100 |
| M2 Screws | | [McMaster](https://www.mcmaster.com/products/screws/system-of-measurement~metric/socket-head-screws-2~/steel-socket-head-screws~~/thread-size~m2/) | |
| └─ L 6mm | 16 | | 16.02 Per 100 |
| Adhesives | | | |
| ├─ Polyimide Tape | 1 | [Amazon](https://a.co/d/0h5d9CHF) | 15.99 |
| ├─ Duct Tape (*Optional*) | 1 | [Amazon](https://a.co/d/042LzFVH) | 13.75 |
| ├─ 200 MP Adhesive Transfer Tape | 1 | [Amazon](https://a.co/d/04m7I20O) | 15.99 |
| └─ Foam Mounting Tape (*Optional*) | 1 | [Amazon](https://a.co/d/09W4lI6i) | 10.99 |


## 3D Printing Specifications

> *All prints for this project were performed on Bambu Lab P1S and Bambu Lab H2D.*

### All Prints

- Nozzle Diameter: 0.4 mm
- Layer Height: 0.2 mm
- Top Surface Pattern: Monotonic Line
- Bottom Surface Pattern: Monotonic
- Wall Loops: 2
- Bed: Textured PEI, 60°C

### PLA Prints

- Infill: 15% Gyroid
- Supports: Tree (where necessary)
- Nozzle Temperature: 210°C

### TPU Prints

- Infill: 25% Gyroid
- Supports: Linear (where necessary)
- Nozzle Temperature: 240°C



## Assembly Instructions

### Chest Plate

1. Cut two 304 mm × 203 mm pieces of PVC-backed fabric.

<p align="center"><img src="./assets/c2.jpg" width="360"></p>


2. Using transfer tape, attach one layer of PVC-backed fabric to the chest plate.
3. Mold/cut a 304 mm × 203 mm piece of silicone rubber, approximately 4 mm thick.

<p align="center"><img src="./assets/c4.jpg" width="360"></p>

4. Carefully place the TouchTronix SensX 187 over the chest plate, making sure to align the flat flex cable with the PCB slot on the side of the chest plate.

<p align="center"><p align="center"><img src="./assets/c5.jpg" width="360"></p>

5. Place the second piece of PVC-backed fabric on top of the TouchTronix SensX 187.

<p align="center"><img src="./assets/c6.jpg" width="360"></p>

6. Place the silicone rubber sheet on top of the PVC-backed fabric.

<p align="center"><img src="./assets/c7.jpg" width="360"></p>

7. Secure the layers to the chest plate with duct tape. Ensure that the layers are not loose and remain firmly held to the chest plate.

<p align="center"><img src="./assets/c8.jpg" width="360"></p>

8. Insert the PCB into the PCB cover.

<p align="center"><img src="./assets/c9.jpg" width="360"></p>

9. Snap the PCB cover into place on the side of the chest plate, being careful not to pinch the wire while doing so.

<p align="center"><img src="./assets/c10.png" width="640"></p>

10. Insert 4× M3 nuts into the slots in the back of the chest plate adapter.

<p align="center"><img src="./assets/c11.png" width="640"></p>

11. **If using for teleoperation**: Mount the chest plate adapter to the Unitree G1 with 4× M5 provided bolts. (Otherwise, skip this step. Remaining steps are unaffected.)

<p align="center"><img src="./assets/c12.png" width="640"></p>

12. Slide the chest plate over the chest plate adapter, making sure to align the grooves.

<p align="center"><img src="./assets/c13.png" width="640"></p>

13. Use 4× M3 L8 screws to fasten the chest plate to the chest plate adapter.


### Forearm Covers

1. Assemble FlexiTac sensors according to: https://flexitac.github.io/
<p align="center"><img src="./assets/w2.png" width="640"></p>

2. Align the top and bottom pieces of the forearm covers along their grooves.
<p align="center"><img src="./assets/23.png" width="640"></p>

3. Fasten 2× connectors to each side using 2× M2 screws for each of the connectors.
4. Cut/mold a 160 mm × 100 mm piece of silicone rubber, approximately 4 mm thick.
<p align="center"><img src="./assets/w5.jpg" width="360"></p>

5. Align the FlexiTac sensor with the bottom edge of the rounded cover so that the taxel area is centered on the cover, while leaving the two mounting holes exposed.

   a. *Optional*: Reinforce the flat flex cable portion of the sensor with additional polyimide tape to prevent unwanted damage.

<p align="center"><img src="./assets/w6.jpg" width="360"></p>

6. Using duct tape or polyimide tape, secure the FlexiTac sensor to the cover.
<p align="center"><img src="./assets/w7.jpg" width="360"></p>

7. Place the silicone rubber pad over the taxel area of the FlexiTac sensor so it fully covers the taxel area.
<p align="center"><img src="./assets/w8.jpg" width="360"></p>

8. Secure the silicone rubber pad with duct tape or polyimide tape.

   a. *Optional*: Also secure the flat flex sensor ends down with polyimide tape.
<p align="center"><img src="./assets/w9.jpg" width="360"></p>

9. Connect flat flex ends of the sensor to the flat flex connector boards.
<p align="center"><img src="./assets/w10.jpg" width="360"></p><p align="center">

10. Using a flat flex cable, connect the connector associated with the smaller flat flex sensor end to FPC-1 and the other to FPC-2 on the FlexiTac PCB.

    a. Use foam adhesive to mount the PCB to the flat side of the forearm cover, leaving some slack in the flat flex cables.

    b. *Note*: The BOM lists only 32-pin flat flex cables. Here, a 16-pin cable was used for clarity.


11. **If using for teleoperation**: Remove the 4× screws in the Unitree G1 wrist pitch joint. (Otherwise stop here and repeat the above steps for the other cover.)
<p align="center"><img src="./assets/w12.png" width="640"></p>

12. Mount the forearm adapter to the Unitree G1 using the same 4× screws.
<p align="center"><img src="./assets/w13.png" width="640"></p>

13. Slide the forearm cover assembly over the adapter so the adapter holes line up with the mounting hole, then secure the forearm cover to the adapter using two M3 L8 screws.
<p align="center"><img src="./assets/w14.png" width="640"></p><p align="center">

14. Repeat for both forearm covers.



### GripTac


1. Cut a 104 mm × 67 mm piece of PVC-backed fabric.
2. Mold/cut a 104 mm × 67 mm piece of silicone rubber, approximately 4 mm thick.
<p align="center"><img src="./assets/g3.jpg" width="360"></p><p align="center">

3. *Optional*: If desired, remove the end from the TPU finger.
<p align="center"><img src="./assets/g4.png" width="640"></p>

4. Place 4× M3 L22 screws through the holes in the finger adapter.
<p align="center"><img src="./assets/g5.png" width="640"></p>

5. Line up the holes in the TPU finger with the holes in the adapter, then secure it with 4× M3 L8 screws.


6. Place the TouchTronix SensX 160 on the flat face of the TPU finger and feed its flat flex end through the slot.
<p align="center"><img src="./assets/g6.jpg" width="360"></p><p align="center">

7. Place a layer of polyimide tape over the sensor and across the flat face of the TPU finger, being careful to avoid trapping dust or air bubbles.
<p align="center"><img src="./assets/g8.jpg" width="360"></p><p align="center">

8. Connect the PCB to the flat flex end of the sensor.
<p align="center"><img src="./assets/g9.jpg" width="360"></p><p align="center">

9. Connect the USB-to-TTL converter to the PCB.
<p align="center"><img src="./assets/g10.png" width="640"></p>

10. Slide the 4× screws protruding from the finger adapter through one set of mounting holes in the main GripTac body and fasten them with 4× M3 nuts.
<p align="center"><img src="./assets/g11.jpg" width="360"></p><p align="center">

11. Place a layer of transfer tape over the polyimide layer on the TPU finger, then cover it with the previously cut piece of PVC-backed fabric.
<p align="center"><img src="./assets/g12.jpg" width="360"></p><p align="center">

12. Place another layer of transfer tape over the PVC-backed fabric and cover it with the molded silicone rubber.
<p align="center"><img src="./assets/g13.jpg" width="360"></p><p align="center">

13. Using foam tape, attach the USB-to-TTL converter somewhere out of the way of the sensor.
<p align="center"><img src="./assets/g14.png" width="640"></p>

14. **If using for human data collection**: Mount the Pico controller holder to the top of the GripTac with 3× M3 L8 screws, then slide the correct Pico controller in.
15. **If using for teleoperation**: Replace the default hands on the Unitree G1 using the adapter end of the GripTac.