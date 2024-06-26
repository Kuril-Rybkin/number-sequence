# number-sequence
## Task specification:
The task is to develop a program that analyzes a sequence of integers.
Assume a sequence of non-negative integers (0, 1, 2, ... ). The sequence starts with number zero, the numbers a re in an ascending order, and the numbers are adjacent to each other (no extra spaces or leading zeros). The beginning of the sequence is:

01234567891011121314151617181920...

The task of the program is to find the number and the particular digit in the given position in the sequence. For example:
- there is digit 0 of the number 0 in position 0,
- there is digit 2 of number 12 in position 15,
- there is digit 1 of number 710 in position 2021, ...

To make the program universal, we consider the sequences where the numbers are in various bases. For example, if the base i s 2, the sequence may look like:

01101110010111011110001001...

For example, there is digit 0 of number 110 in position 14 for the binary sequence.

Your program will be given a list of problems to solve in its standard input. Each problem consists of two decimal integers: the first number determines the position in the sequence, the second number is the base. The program computes the digit/number for each such problem and displays the result; the format is shown below. The program terminates when there are no further problems in the input, i.e., when the EOF is reached.
The program must validate input data. If the input is invalid, the program must detect it, it shall output an error message (see below), and terminate. If displayed, the error message must be sent to the standard output (do not send it to the error output) and the error message must be terminated by a newline (\n). The input is considered invalid, if:
- a position in the sequence is invalid (not an integer, negative position),
- the base is invalid (not an integer, outside of closed interval [ 2 ; 36 ] ).
