# Ex 2.2
In this example it is found the  functioning of a DEC 3/8 with high-level active outputs and high-level active validation input will be modeled by a VHDL program.
It is named logic demultiplexer a combinational logic circuit having n address inputs, a data input and at most 2^n outputs, whose functioning is characterized by the fact that at a certain moment of time the information from the data input is transmitted only to that output having a decimal index equivalent to the binary combination from the address inputs.
# Ex 2.3
This is a generic variant made using the conv_std_logic_vector () conversion function which converts an integer into a binary vector with a specified length.A vectorial demultiplexer is a combinational logic circuit that allows the transmission of information from a data bus to one of the output buses depending on the binary combination on the addressinputs. The data bus and the output bus must be the same width.
# Ex 2.4
VHDL model of a DEMUX 3/8 demultiplexer.
The block diagram can be seen using the RTL Schematic and the related VHDL program is shown in this example. The program is a variant of the program where the generic alternative was removed and the validation input was transformed into a data input. 
# Ex 2.5
VHDL model of a DEMUX 2/4x2 vectorial demultiplexer with a data input and 4 outputs on 2 bits each, but without validation inputs.
