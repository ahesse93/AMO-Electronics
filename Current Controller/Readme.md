# Current Controller

Regulates a current < 10 A with a Darlington transistor, measuring the current across a 1 Ohm shunt resistor -> 1V = 1A

Regulates the current on the low side, so connect the load on the current input and the output (= ground) back to the power supply
  
C3 can be used to limit the control bandwidth, C4 can be increased to make circuit stable if oscillating.

Appears to be stable for inductive loads of up to 1 mH (and maybe higher). 
