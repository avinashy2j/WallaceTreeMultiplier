# WallaceTreeMultiplier
Full Custom Design of 5-bit x 5-bit Multiplier Circuit for 45nm CMOS

# Overview
Multiplier circuits are digitals circuits used in arithmetic operation and have vital role in microprocessors. The most common form of multiplication is the product of two unsigned binary numbers. Forming partial product and adding them, is a very common approach to multiply two numbers and can be achieved by unsigned array multiplication techniques.
Apart from this, there are many architectures used to implement multiplications to reduce the time complexity of the circuit.
In this project, I selected Wallace tree topology to implement 5-bit x 5-bit multiplier circuit. The design was executed on Custom Methodology. First the schematic was generated and then the layout was completed on Layout XL suite. Half adder, Full Adder and 2x1AND standard cells were used in this design and the goal to route the long and irregular wire connect the Carry Save Adder circuits.
The steps that used to create tree are following:
1.	Partial Product results creation 
2.	Partial Product results decrement 
3.	Partial Product results addition 

# Project Description 
1.	1.Wallace tree topology was implemented using Carry Save Adder with HA, FA & 2x1AND RVT std. cells on schematic and EDP efficient size were obtained by using logical effort and sweeping the width of transistor.
2.	Challenge was to layout the long and irregular interconnect wire among CSAs which was successfully achieved.
3.	During Layout, Floorplan was created with aspect ratio 1 (square boundary) and area utilization was 79.22% (~80%).
4.	Routing results showed that 4 metals layers were used with 51.5% horizontal and 48.5% vertical nets. The total net length was     found to be 540.01 um with 162 number of routes created.
5.	5.After Place & Route, chip area was achieved to be 196.84 sq. um.
