# Current Controller

Regulates a moderate current (~ 5-10 A) flowing through a device using a Darlington transistor  
Connect power supply -> device -> current controller -> shunt resistor (1 Ohm?) -> ground  
  
The input voltage on the BNC connector is the voltage the board tries to keep across the shunt resistor (-> 1A / V for a 1 Ohm resistor)
  
C3 can be used to limit the control bandwidth, C4 can be increased to make circuit stable if oscillating.

Appears to be stable for inductive loads of up to 1 mH (and maybe higher).
