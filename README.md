Ramps-1.4.3
===========

forked from ultimachine/Ramps 1.4 and GermanRepRap/Ramps-1.4.2

RAMPS 1.4.3 Change log

* Works with 12/24V
 * Capacitors updated to operate at 24V 

* Improved MOSFETs, swapped to Infineon IPD036N04L G 
 * Lower RDSon, 3.9mOhm vs 16mOhm at Vgs = 5V
 * SMD, good heat dissipation via PCB
 * Higher current capability

* Selectable Logic-Level Voltage
 * Jumper to select between 5V and Arduino IOREF
 * Allows easier modification to run RAMPS on Arduino Due
 

RAMPS 1.4.2 Change log

* Standard blade fuses instead of thermal fuses increasing the heat resilience.
 	
* Current carrying improved by increasing the thickness of the cooper at the PCB from 35 to 70 micro meters.

* Suppression caps added to each end-stop to avoid spurious signals.

* Added an additional connector to XY, E1 and E2 to connect a second stepper motor.

* Connector for external reset added.

* Labeled D8, D9,D10 with Heatbed, Extrude 1, Fan and Extruder 2.
