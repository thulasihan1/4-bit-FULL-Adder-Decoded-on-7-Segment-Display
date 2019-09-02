# 4-bit-FULL-Adder-Decoded-on-7-Segment-Display

The purpose of this project is to understand on how analyze specifications and pinouts on CMOS IC datasheets and to understand on how computers add numbers. This circuit can be easily programmable. 


The 4 bit Full Adder is able to add 4 bits of Input A and 4 bits of Input B in order to output 4 bits of the SUM and an additional Carry Out bit. Carry In of the first Full adder is set to 0 (GND). The RED LEDs are represented as the 4 bits of the SUM and the YELLOW LED is represented as the Carry Out. Once a certain output is created based on the inputs of A and B, the output of the 4 bits of the SUM are then decoded by a BCD to 7 Segment Decoder where the output is displayed in decimal. The 7 Segment Display is powered with a VCC= 2.2 V. I used a 9v Battery to power the circuit and used a series of diodes as a voltage regulator to drop the 9V to (2.2- 5V). I also used a multimeter to constantly test  and monitor the voltage supplied to the circuit in order to figure out the amount of diodes needed to reach to the requirment voltage and to make necessary adjustments on the voltage input of the circuit.


Future Improvments: After sucessfully creating this circuit I realized that improvments can be made. Since the 7 Segment display can only go up to 9, my 4 bit Full adder is able to output numbers greated than 9 therefore a second 7 Segment display must be needed. The Carry Out bit must also be included when the OUTPUT is decoded by the 7 segment display therefore a 5 bit to 7 Segment decoder must be designed. 4 input fip switches should have also be considered instead of using the positive and negative rails on the breadboard. 


Schematics and Datasheets are within this Repository. 

IMPLEMENTATION

![69624531_499449460874498_6428344115326353408_n](https://user-images.githubusercontent.com/39424972/64087433-0395e400-cd0b-11e9-9963-8dc042978961.jpg)


