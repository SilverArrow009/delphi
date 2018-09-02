# delphi
Delphi is a very simple processor with no pipelining, no interrupt controller, no cache or cores, no MMU or memory protection and no peripheral interface. It is a simple von Neumann machine with four 8-bit registers and 8-bit address bus and 20-bit data bus. It runs on its own ISA which is also present in the same folder. The actual 20-bit control word is compressed to 8 bits using a ROM. The ISA sheet depicts the compressions.
Motivation for the ISA comes from the x86 architecture. With one control word and two/operands. The key difference is that this architecture relies on "Selection of operand type" ie , the type of operands must be specified before they are to be used using SEL instruction and three basic types called reg,mem and imm8 are recognized as "register",memory" and "immediate 8 bit" operands.
Looping and conditional jumps are implemented directly by modifying the program counter (PC).

You may need to install logisim simulator before you proceed. Simply double click the .circ file once logisim is installed.

Refer to the quick start guide for more info.

