# PaintBot
<img src="https://imgur.com/fasSOo4.jpg" width="700">

## Overview
Paintbot is a machine that paints upright surfaces. It's a prototype that can paint indoor walls. The goal of this prototype is to extend it to paint or draw on walls of any size, indoors and outdoors alike. This document is a wiki for the robot's mechanics, electronics and code.

## Iterations
  * [V-Plotter](https://github.com/UniKlo/PaintBot/tree/master/Iterations/V-Plotter)
  
## Mechanics
  * [Motor Rack with Tensioner](https://github.com/UniKlo/PaintBot/tree/master/Mechanics/MotorRack)
  * [Centerpiece](https://github.com/UniKlo/PaintBot/tree/master/Mechanics/Centerpiece)
  * [Spray Gun Holder](https://github.com/UniKlo/PaintBot/tree/master/Mechanics/SprayGunHolder)
  * [Motor Block](https://github.com/UniKlo/PaintBot/tree/master/Mechanics/MotorBlock)
  * [Pulley System (Brackets)](https://github.com/UniKlo/PaintBot/tree/master/Mechanics/PulleySystem)
  * [Pulley Weights 15Kg](https://github.com/UniKlo/PaintBot/tree/master/Mechanics/PulleyWeights)
  * [Pillar](https://github.com/UniKlo/PaintBot/tree/master/Mechanics/Pillar)


## Electronics
  - ### Wiring Schematics
    * [Circuits and Connections with Pictures](https://github.com/UniKlo/PaintBot/tree/master/Electronics/Wiring)
  
  - ###  Parts Reference
    * [Spray Gun](https://www.amazon.com/Graco-257025-Project-Painter-Sprayer/dp/B004Z2090U/ref=asc_df_B004Z2090U/?tag=hyprod-20&linkCode=df0&hvadid=198077767340&hvpos=1o2&hvnetw=g&hvrand=15997159825197345473&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032020&hvtargid=pla-373698499647&psc=1)
    * [Arduino Mega 2560](https://store.arduino.cc/usa/mega-2560-r3)
    * [H-Bridge](https://www.amazon.com/HiLetgo-BTS7960-Driver-Arduino-Current/dp/B00WSN98DC)
    * [12v Power Supply](https://www.amazon.com/MENZO-Universal-Regulated-Switching-Computer/dp/B06VWV5YCH)
    * [XY Motors](https://electricscooterparts.com/motors-my6812.html)
    * [Z-Axis Motor](https://www.makermadecnc.com/product/z-axis-replacement-motor/)

## Code
### [Demo 11/12/2019](https://github.com/UniKlo/PaintBot/tree/master/DEMO_code) <br/>
![](A6B893AF-5B91-4EBE-B7AC-E00EC545.gif)<br/>
This used the encoders' output to control the displacement of the centerpiece so the paintbot could spray 3ft. x 3ft. area on the wall.

### [Automatic Controls](https://github.com/CaseySingleton/RoboLabPaintBotMotorController)

## Use
 * For an even coat, each spray layer should have 50% overlay
 * The spray-gun should 1ft. away from the wall
