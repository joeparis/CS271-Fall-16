1. Explain the steps of the fetch-decode-execute cycle. Your explanation should include what is happening in MARIE's various registers.
2. Combine the flowcharts that appear in Figures 4.11 and 4.12 so that the interrupt checking appears at a suitable place.
3. Explain why, in MARIE, the MAR is only 12 bits wide while the AC is 16 bits wide.
4. List the hexadecimal code for the following program (hand assemble it).

| Hex Address | Label | Instruction |
| ----------- | ----- | ----------- |
| 100         |       | Load A      |
| 101         |       | Add One     |
| 102         |       | Jump S1     |
| 103         | S2,   | Add One     |
| 104         |       | Store A     |
| 105         |       | Halt        |
| 106         | S1,   | Add A       |
| 107         |       | Jump S2     |
| 108         | A,    | HEX 0023    |
| 109         | One   | HEX 0001    |

5. What are the contents of the symbol table for the preceding program?

6. Consider the MARIE program below.   

      a) List the hexadecimal code for each instruction.   

      b) Draw the symbol table.   

      c) What is the value stored in the AC when the program terminates?   

   | Address | Label  | Instruction |
   | ------- | ------ | ----------- |
   | 100     | Start, | LOAD A      |
   | 101     |        | ADD B       |
   | 102     |        | STORE D     |
   | 103     |        | CLEAR       |
   | 104     |        | OUTPUT      |
   | 105     |        | ADDI D      |
   | 106     |        | STORE B     |
   | 107     |        | HALT        |
   | 108     | A,     | HEX 00FC    |
   | 109     | B,     | DEC 14      |
   | 10A     | C,     | HEX 0108    |
   | 10B     | D,     | HEX 0000    |

7. Write the following code segment in MARIE's assembly language:

```
if X &gt; 1 then
   Y = X + X;
   X = 0;
endif;
Y = Y + 1;
```
