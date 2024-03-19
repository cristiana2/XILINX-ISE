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
# Ex 6.2 
It will be modeling/synthesize in VHDL a parallel-parallel register with 8 bits length, also called buffer register using Flip-Flop type D. We can observe that in line 38 it is found the rising_edge() function which is written to detect the appearance of the positive edge of the clock pulse.
# Ex 6.3
It will be modeling/synthesize in VHDL a series-series right shift register.For modeling, it was necessary to input a saQ signal at the output
of the register because the oQ output cannot appear in the right member of an assignment instruction.
# Ex 6.4
It will be modeling/synthesize in VHDL a series-parallel right shift register.Also for this modeling it was necessary to introduce a signal saQ at the output of the register, because the output oQ cannot appear in the right member of an assignment instruction. Changing the value of this signal is done only on the positive edge of the clock signal. The occurrence of the edge is also detected with the rising_edge() function in line 39. If the active edge is the negative edge, its detection involves the use of the falling_edge() function.
# Ex 6.5
Modeling VHDL, synthesize and test an 8-bit series-parallel register (right shift register) made with FF type D flip-flops. There is no initialization signal.The command block is modeled with the instruction in line 40 in the form of a concatenation between the serial input and the old contents of the register shift with one position to the right.The block of memory cells is modeled with the instructions in lines 42 and 43. The input of the saQ signal is necessary because the
output of this block is on the one hand the output of the system and on the other hand the reaction from the input of the control block.
