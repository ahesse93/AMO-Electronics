# AMO-Electronics
Collection of different electronics projects useful for AMO experiments

# Current Controller

Regulates a moderate current (~ 5-10 A) flowing through a device
Connect power supply -> device -> current controller -> shunt resistor (1 Ohm?) -> ground
Supply ~ +-15 V on the Molex connector (can be used to daisychain several boards together)
The input voltage on the BNC connector is the voltage the board tries to keep across the shunt resistor (-> 1A / V for a 1 Ohm resistor)
