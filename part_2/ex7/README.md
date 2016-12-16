#	Experiment	7:	Linear	Feedback	Shift	Register	(LFSR)	and	PRB

##Objective:

The objective is to implement a 7 bit LFSR using the 4 bit LFSR introduced in lecture.

##Results
The 7 bit LFSR is sometimes used as a pseudo-random number generator in practical applications as it uses d-flip flops in combination with XOR gates to change the order in which the numbers are generated.

We predicted that the first 10 output values should be 1,3,7,15,31,63,127,126,125,122. This was fairly straight-forward as we just followed the circuit given in lectures but with 7 DFFs and found the values from that.

Instead of hooking up the LFSR to a clock, we used a key button as a clock signal which meant we could step through the numbers. This produced the result that we expected.
