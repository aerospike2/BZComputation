This repository consist of the hardware and specification of parts associated to the paper "A programmable chemical state machine solves hard computational problems "

University of Glasgow, School of Chemistry

Authors: Abhishek Sharma, Marcus Tze-Kiat Ng, Juan Manuel Parrilla Gutierrez, Yibin Jiang, Leroy Cronin

# BZ Computation
BZ platforms are automated platform that couple Belousov-Zhabotinsky reaction, hydrodynamic of the system and image recgonition to realise computation in a chemical system.


## Platform Overview
The periodicity of the oscillation of the BZ reaction is controlled via mechanical stimuli from the magnetics stirrers. On top of that, the coupling between two or more neighbouring cells are governed by the hydrodynamics through the interfacial stirrers.<br/>
The dimension of each cell was desgined in such a way that no apparent coupling between cells can be observed without activation of the interfacial stirrers.

![alt text](https://github.com/croningp/BZComputation/blob/master/media/out.gif)

## DC motors operation
The DC motors are separated into two categories, namely: <br/>
(i) [Cell-motors](https://uk.rs-online.com/web/p/dc-geared-motors/8347675?cm_mmc=UK-PLA-DS3A-_-google-_-PLA_UK_EN_Automation+%26+Control+Gear_Whoop-_-DC+Geared+Motors_Whoop-_-PRODUCT_GROUP&matchtype=&pla-341179612256&s_kwcid=AL!7457!3!413164772306!!!g!341179612256!&gclid=CjwKCAiAnfjyBRBxEiwA-EECLLOxfyEWQI48JPJwKeyX3iATBWEGEihnJxriuzLXfxe1rH9PmNmegRoCBV8QAvD_BwE&gclsrc=aw.ds) <br/>
(ii) [Interface-motors](https://www.aliexpress.com/item/32780746288.html)<br/>
The motors are then coupled with the magnet holders which then allow the magnetic stirrers to be controlled by modulating the PWM signal generated by the electronics.

## Liquid Handling
All the pumps operated were from Tricontinent C-Series Syringe Pumps with T Valve 3-port. The tubes were 1/8 in PTFE Tubing.


## Image recognition 
Cameras used in both platforms are [logitech C920 HD PRO WEBCAM](https://www.logitech.com/en-gb/product/hd-pro-webcam-c920) <br/>
The height of the cameras from the experimental platforms are as followed:<br/>
1D Platform: 20.5 cm <br/>
2D Platform: 33.4 cm 











## __________________________________________________________________________________

Authors Contribution:                           <br/>
Abhishek Sharma :-                                  <br/>
Marcus Tze-Kiat Ng :-                               <br/>
Juan Manuel Parrilla Gutierrez :-                  <br/>
Yibin Jiang :-                                    <br/>
Leroy Cronin :-
