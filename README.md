# Scicalc

 Scicalc is a scientific calculator inspired by the TI 84 calculator. It features the rp2350a mcu with the RP Rm2 radio module for bluetooth and wifi connectivity which are essential in daily life. It has a 2 inch tft lcd display which had bright colors and has a in built rechargable battery. It supports 1.5A fast charging along with a modular architecture.  

 The firmware for this project can be found [here](https://github.com/Keyaan-07/scicalc-fw)
 
 # Features  

 - Features a large 2 inch color display for advanced calculations.  
 - A fast mcu for advanced calculations which is newer and faster.  
 - 128 mbit storage for firmware which can be updated for new features.  
 - Fully custom design and Open Source!  
 - Cheap to make and helps in evolving skills.  

# Images
The 3d model looks like this:  
![3d render isometric](/media/3d-render-isometric.png)  
![3d render top](/media/3d-render-top.png)  
The keycaps attach to the buttons in this manner. I had this idea after looking at bridges!  
![towers](/media/towers.png)  
![3d pcb](/media/pcb-kicad.png)  
![schematic](/media/Scicalc.svg)  
![3d render opened](/media/3d-render-opened.png)  

CAD model can be found [here](https://cad.onshape.com/documents/84fe92d66eafc534d9523f7c/w/e5f687d44fa54d018b5fb56d/e/4c7f7c65e5851fcead59abe7)!! View the PCB Online [here on Kicanvas](https://kicanvas.org/?repo=https%3A%2F%2Fgithub.com%2FAhad732%2FScicalc%2Ftree%2Fmain%2FHardware)  

BOM
|Designator                                  |Footprint                              |Value                      |Quantity|Price|Link                                                                                 |
|--------------------------------------------|---------------------------------------|---------------------------|--------|-----|-------------------------------------------------------------------------------------|
|C1, C10, C11, C2, C3, C4, C5, C6, C7, C8, C9|402                                    |100n                       |100     |0.16 |https://www.lcsc.com/product-detail/C5137487.html                                    |
|C15, C16                                    |402                                    |15p                        |100     |0.1  |https://www.lcsc.com/product-detail/C5448872.html                                    |
|C17, C18                                    |402                                    |10u                        |20      |0.42 |https://www.lcsc.com/product-detail/C6119763.html                                    |
|C19                                         |402                                    |1u                         |50      |0.12 |https://www.lcsc.com/product-detail/C7393850.html                                    |
|D1-D50                                      |D_SOD-123                              |1N4148W                    |100     |0.65 |https://www.lcsc.com/product-detail/C5381435.html                                    |
|D53                                         |402                                    |Red                        |100     |0.67 |https://www.lcsc.com/product-image/C52675960.html                                    |
|D54                                         |402                                    |Green                      |100     |0.61 |https://www.lcsc.com/product-detail/C55072283.html                                   |
|J1                                          |USB_C_Receptacle_HCTL_HC-TYPE-C-16P-01A|USB_C_Receptacle_USB2.0_16P|10      |0.68 |https://www.lcsc.com/product-image/C7507405.html                                     |
|J2                                          |PinHeader_1x02_P2.54mm_Vertical        |Battery-2000 Mah           |1       |6.62 |https://robu.in/product/wly104050-2500mah-3-7v-single-cell-rechargeable-lipo-battery/|
|J3                                          |PinSocket_1x09_P2.54mm_Vertical        |Screen                     |1       |9.57 |https://robu.in/product/smartelex-2-inch-ips-tft-lcd-module/                         |
|L1                                          |603                                    |3.3u                       |50      |0.57 |https://www.lcsc.com/product-image/C411948.html                                      |
|R1, R2                                      |402                                    |27                         |100     |0.06 |https://www.lcsc.com/product-detail/C55098303.html                                   |
|R10, R5, R8                                 |402                                    |10K                        |100     |0.09 |https://www.lcsc.com/product-detail/C2759773.html                                    |
|R11                                         |402                                    |604                        |100     |0.08 |https://www.lcsc.com/product-detail/C49656019.html                                   |
|R3, R4                                      |402                                    |5.1K                       |100     |0.06 |https://www.lcsc.com/product-detail/C54920813.html                                   |
|R9                                          |402                                    |470                        |100     |0.06 |https://www.lcsc.com/product-detail/C54920802.html                                   |
|SW1-SW51                                    |SW_SPST_TS-1088-xR020                  |SW_Push                    |60      |3.03 |https://www.lcsc.com/product-detail/C720477.html                                     |
|U1                                          |QFN-60-1EP_7x7mm_P0.4mm_EP3.4x3.4mm    |RP2350A                    |3       |3.9  |https://www.lcsc.com/product-detail/C42411118.html                                   |
|U2                                          |SOT-23                                 |MCP1700x-330xxTT           |5       |0.55 |https://www.lcsc.com/product-detail/C41381676.html                                   |
|U3                                          |WSON-8-1EP_6x5mm_P1.27mm_EP3.4x4.3mm   |W25Q128JVP                 |3       |10.27|https://www.lcsc.com/product-detail/C190862.html                                     |
|U5                                          |rpi_rmc20452t                          |RM2                        |1       |7.05 |https://robu.in/product/raspberry-pi-radio-module-rmc20452t/                         |
|U6                                          |VQFN-16-1EP_3x3mm_P0.5mm_EP1.6x1.6mm   |BQ24075RGT                 |3       |3.24 |https://www.lcsc.com/product-detail/C15464.html                                      |
|Y1                                          |Crystal_SMD_3225-4Pin_3.2x2.5mm        |12 mhz                     |5       |0.59 |https://www.lcsc.com/product-detail/C46613546.html                                   |
|                                            |                                       |PCB + Stencil              |        |19.12|                                                                                     |
|                                            |                                       |Parts Shipping             |        |6.09 |                                                                                     |
|                                            |                                       |                           |Total   |74.36|                                                                                     |


