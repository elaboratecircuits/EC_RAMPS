# EC_RAMPS
Improved version RAMPS type shield for Arduino MEGA2560 R3 compatible boards and for the new ARM4RAMPS 


Completely redrawn schematics and layout of the original RAMPS in Altium.

Active design phase.
Till active shipping phase schematics layout drawings and free prototypes will be available on demand to active 3D printer software developpers. 

The design files will be released after active shipping phase. 

The EC_RAMPS is designed to address some of the shortcomings of the original Pololu RAMPS board and to integrate the most useful add-on modules in the base frame.

Many of the improvements are coming from the RepRap Community, from German RepRap RAMPS 1.4.2 version, from RepRapDiscount and from AUS3D.    


Changes over RAMPS 1.4

 - flat tab high power blade terminals for power connections -avoid power block contact problems
 - more SMD components  
 - 24V compliant, Jumper selection for Mega board power.  
 - integrated Smart DISPLAY Adapter connectors - no need for stacked RRD style adapter - a slimmer stack will fit slimmer case  
 - integrated 20pin FFC connector, alternative connectivity for smart displays (we'll propose soon improved versions for these) 
 - new logic level Power MOSFET transistors with ultralow on-resistance - SMD mounted - much less heat generated.
 - for heatbed MOSFET:  flyback protection diode and alternative footprint for TO220AB style transistors in stand-up position with heatsink  
 - dual individually PWM controlled FAN support onboard - no need for dual FAN adapter
 - two rows connection headers for all stepper modules - for dual motors models 3D printers and CNC (MP-CNC) 
 - blade fuse holders for automotive blade fuses - replaces PTC fuses.
 - suppression capacitors added to each end-stop to avoid spurious signals
 - complete re-layout in order to shorten the power loops and improve heat dissipation.
 - routed pin 22 to smart display IDC connectors
 
 



FRONT SIDE


![alt tag](https://github.com/elaboratecircuits/EC_RAMPS/blob/master/EC_RAMPS_front.PNG)





STACK with ARM4RAMPS


![alt tag](https://github.com/elaboratecircuits/EC_RAMPS/blob/master/ARM4RAMPS-EC_RAMPS-stack-2.PNG)







