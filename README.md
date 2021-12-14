# Basic-CPU
Pedram Aghazadeh
Calculator:
Bits are from low to high
A0, B0, S0, C0: 1
A1, B1, S1, C1: 2
A2, B2, S2: 4
A3, B3, S3: 8
Multiplication and Division are Unsigned(input & output).
Division calculates A/0 as 15(INF).
Division can calculate the remainder(4 outputs connected to ground in Full Divisor circuit).
For Division 5-bit subtractor was necessary.
C1 C0 Operation
0  0  SUM
0  1  MUL
1  0  SUB
1  1  DIV
Press button to see the result of operation.
CPU:
M. Morris Mano Computer Systems Architecture Chapter 6 Basic Computer
Instructions and machine language can be found at book.
