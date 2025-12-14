# JK-FLIPFLOP
AIM:
To implement JK flipflop using verilog and validating their functionality using their functional tables
SOFTWARE REQUIRED:
Quartus prime
THEORY
JK Flip-Flop
JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions.
 
This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs.
 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied.

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. 
 
The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)
Procedure:
1.Go to quartus software.

2.Set new environment.

3.Type the code to implement JK flipflop using verilog and validating their functionality using their functional tables.

4.Run the program.

5.Give inputs in the waveform table .

6.Run the program.



PROGRAM
/* Program for flipflops and verify its truth table in quartus using Verilog programming. Developed by:MINHAJ AHAMED J RegisterNumber: 25006694*/
RTL LOGIC FOR FLIPFLOPS:
[rtl.pdf](https://github.com/user-attachments/files/24150499/rtl.pdf)

TIMING DIGRAMS FOR FLIP FLOPS:

[wave.bmp](https://github.com/user-attachments/files/24150500/wave.bmp)


RESULTS: Thus the JK flipflop using verilog and validating their functionality using their functional tables is implemented and verified.
