**Due December 1**

1. Assume you have a byte-addressable machine that uses 32-bit integers and you are storing the hex value 3456 at address 0.   
   a) Show how this is stored on a big endian machine.   
   b) Show how this is stored on a little endian machine.   
   c) If you wanted to increase the hex value to 123456, which byte assignment would be more efficient, big or little endian? Explain your answer.   
2. Fill in the following table to show how the given integers are represented, assuming 16-bits are used to store values and the machine uses 2’s complement notation.

   | Integer | Binary | Hex    | 4 Byte Big Endian | 4 Byte Little Endian |
   | ------- | ------ | ------ | ----------------- | -------------------- |
   | 28      | &nbsp; | &nbsp; | &nbsp;            | &nbsp;               |
   | 2216    | &nbsp; | &nbsp; | &nbsp;            | &nbsp;               |
   | -18675  | &nbsp; | &nbsp; | &nbsp;            | &nbsp;               |
   | -12     | &nbsp; | &nbsp; | &nbsp;            | &nbsp;               |
   | 31456   | &nbsp; | &nbsp; | &nbsp;            | &nbsp;               |

3. Consider a 32-bit hexadecimal number stored in memory as follows:

   | Address | Value |
   | ------- | ----- |
   | 100     | 2A    |
   | 101     | C2    |
   | 102     | 08    |
   | 103     | 1B    |
   a) If the machine is big endian and uses 2’s complement representation for integers, write the 32-bit integer number stored at address 100 (you may write the number in hex).   
   b) If the machine is big endian and the number is an IEEE single-precision floating point value, is the number positive or negative?   
   c) If the machine is big endian and the number is an IEEE single-precision floating point value, determine the decimal equivalent of the number stored at address 100 (you may leave your answer in scientific notation form, as a number times a power of two).   
   d) If the machine is little endian and uses 2’s complement representation for integers, write the 32-bit integer number stored at address 100 (you may write the number in hex).   
   e) If the machine is little endian and the number is an IEEE single-precision floating point value, is the number positive or negative?   
   f) If the machine is little endian and the number is an IEEE single-precision floating point value, determine the decimal equivalent of the number stored at address 100 (you may leave your answer in scientific notation form, as a number times a power of two). 

4. There are reasons for machine designers to want all instructions to be the same length.    Why is this not a good idea on a stack machine?

5. A computer has 32-bit instructions and 12-bit addresses. Suppose there are 250 2-address
   instructions. How many 1-address instructions can be formulated? Explain your answer.

6. Convert the following expressions from infix to reverse Polish (postfix) notation.   
      a) (8 – 6) / 2   
      b) (2 + 3) * 8 / 10   
      c) (5×(4 + 3) × 2 – 6)   

7. a) Write the following expression in postfix (Reverse Polish) notation. Remember the rules of precedence for arithmetic operators!   
   ![](http://i.imgur.com/hFve6ha.png)   
   b) Write a program to evaluate the above arithmetic statement using a stack organized
   computer with zero-address instructions (so only pop and push can access memory).

8. a) In a computer instruction format, the instruction length is 11 bits and the size of an address field is 4 bits. Is it possible to have:   
      - 5 2-address instructions   
      - 45 1-address instructions   
      - 32 0-address instructions   
      
  using the specified format? Justify your answer.   
  b) Assume that a computer architect has already designed 6 two-address and 24 zeroaddress instructions using the instruction format above. What is the maximum number of one-address instructions that can be added to the instruction set?

9. Given 16-bit instructions, is it possible to use expanding opcodes to allow the following to be encoded assuming we have a total of 32 registers? If so, show the encoding. If not, explain why it is not possible.

- 60 instructions with 2 register operands
- 30 instructions with 1 register operand
- 3 instructions with one 10-bit address 

**MARIE Programming Project**

Write a program that will first "randomly" generate a number unknown to the user (because MARIE is so limited there is no good way to generate this number so use the same one every time; lame, I know). The user needs to guess what that number is. (In other words, the user needs to be able to input information.) If the user’s guess is wrong, the program should return some sort of indication as to how wrong (e.g. The number is too high or too low). If the user guesses correctly, a positive indication should appear. 

**Read Chapter 6 sections 6.1 to 6.6. for class on November 29**
