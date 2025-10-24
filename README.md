# T_Flipflop

**Theory**

A T flip-flop (Toggle flip-flop) is a type of flip-flop circuit that changes (toggles) its output state every time it receives a clock pulse when its T input is HIGH (logic 1). If the T input is LOW (logic 0), the output state does not change, and the flip-flop holds its previous value.​

Inputs and Outputs
T (Toggle input)

Clock (CLK)

Q (Output)

Q' (Complement output)

Working Principle
When T = 0: The output Q remains unchanged (hold state).

When T = 1: The output Q toggles (switches from 0 to 1 or from 1 to 0) with each clock pulse.

Truth Table
T	Q (present)	Q (next)	Action
0	0	0	Hold
0	1	1	Hold
1	0	1	Toggle
1	1	0	Toggle
Characteristic Equation
Q
n
e
x
t
=
T
⊕
Q
Q 
next
 =T⊕Q
where 
⊕
⊕ means XOR operation.

Features
When T is held HIGH and clock pulses are given, the output frequency of Q is half the input clock frequency. Thus, T flip-flops are widely used as frequency dividers.

They are commonly built by feeding the J and K inputs of a JK flip-flop together or by connecting an XOR gate to a D flip-flop.​

Useful in designing binary counters and toggle switches.
