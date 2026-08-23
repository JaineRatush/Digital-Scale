# Digital-Scale
A digital scale capable of taring and switching units. Created by my friend and I.  
## Objective: 
Understand wheatstone bridges, amplifiers, and state machines by creating a rough digital scale using a load cell and other basic electrical components. 

## Contributions:  
- Soldered the load cell to the HX711 amplifier
- Wired load cell, HX711 ADC Amplifier, Buttons, and capacitors together w/ teammate
- Debugged Button bounce by using ceramic capacitor and built-in Arduino Pullup Resistor pin
- Experimentally determined scale w/ teammate   

[Technical Report](Documentation/DigitalScaleReport.pdf): 
- Flow charts
- Explanation of how load cells use a wheatstone bridge 
- Explanation of the HX711 Analog to Digital Convertor and pins 

## Improvements/Limitations:  
In the first iteration, we created a load cell from scratch using 4 strain gauges, a ruler, and a wheatstone brigde. However, we believe we experienced a lot of noise in all of our tests due to wire overlap, and improper handling of the strain gauges. As a result we switched to a commercial load cell. 

If I were to work on this project again:
- Add 4 load cells and distribute them such that they evenly measure force
- Create a PCB to reduce wiring noise
- Create/Order a food grade platform or bowl 

Contributors: Hannah M. 
