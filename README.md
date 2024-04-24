# Booth-Multiplier
This repository contains a hardware implementation of the Booth algorithm in Verilog. The Booth algorithm is utilized for efficient multiplication of signed binary numbers. The Verilog module booth represents a hardware design that performs signed multiplication of two 4-bit operands, X and Y, utilizing Booth's algorithm.

Features:

Modular Design: The Verilog module is structured for modularity and ease of integration into larger digital designs.
Efficient Multiplication: Implements the Booth algorithm for efficient signed multiplication, reducing the number of partial products generated.
Testbench: Includes a comprehensive testbench (booth_tb) to verify the functionality of the booth module under various test cases.
Clock and Reset Handling: Proper clock and reset signal handling ensures reliable operation of the module in synchronous digital systems.
