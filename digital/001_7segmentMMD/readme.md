Description:

This is a Scrolling Message Pannel using Seven segments displays.

An external oscillator with a regulable frequency sets the output data rate using a counter that address an eeprom.   
An associated , slowed counter (8 bit) allows us to set the scroll rate and an adder allows to use the delayed value
as an offset for the cyclic output data sequence.

A Decoder allows to activate sequentially each column then the offset helps to scroll it.


Files Included:

An eeprom Editor

Proteus simulation file 8X compatible (use it at your risk)
Schematic with minimalistic wiring
example bin file

Ways to improving:

Extend the message length:  get a big modulo counter and wire to more input bits of the eeprom.

Extend the displays size:   Change the length of the column decoder and possibly the size of the counter/adder.


julio alexander aguilar angulo. 2014
