Create a folder on your LBCC Google Drive folder named "CS271 *lastname* *firstname*" and share it with me at joe.paris@linnbenton.edu. Make sure I have edit permissions on the folder (we'll walk through doing this together). You will submit your work to me by copying it into this folder.

Open a word processor (Microsoft Word, Google Docs, anything that will allow you to add both text and graphics) and answer the following questions. For the following questions you may turn in **one** document with your group's answers with all your names on it.

**Due before class on October 4.**

# Chapter 1

1. In your pod, discuss what the difference between computer organization and computer architecture is. Is there a hard line of distinction between them? In what ways do they influence each other? Write a summary of your group's conclusions.
2. Have each member of the group briefly state and explain the Principle of Equivalence of Hardware and Software in their own words. As a group come up with a consensus of its meaning and include a summary of it in your document. 
3. State Moore's Law in your own words. 
4. The looming end of Moore's Law has been predicted many times in recent years. What is your opinion of this? Is Moore's Law doomed? Why or why not? What impact does your prediction have on the future of computer hardware? Discuss this with your peers in your pod and write up a short summary of your conclusions.
5. Time for a little math. Answer the questions below ensuring that everyone in the group gets the same answer *and* understands why it is the answer.
   
   How many milliseconds (ms) are in 1 second?

   How many microseconds (μs) are in 1 second?

   How many nanoseconds (ns) are in 1 millisecond?

   How many microseconds are in 1 millisecond?

   How many nanoseconds are in 1 microsecond?

   How many kilobytes (KB) are in 1 gigabyte (GB)?

   How many kilobytes are in 1 megabyte (MB)?

   How many megabytes are in 1 gigabyte (GB)?

   How many bytes are in 20 megabytes?

   How many kilobytes are in 2 gigabytes?
6. Suppose a transistor on an integrated circuit chip were 2 microns in size. According to Moore's Law, how large would that transistor be in 2 years? How is Moore's law relevant to programmers?
7. Discuss your understanding of the von Neumann model with the members of your group. Be sure to include **all** the relevant components and their purpose. What implications does the von Neuman model present to you as a programmer?
9. Why modern machines consist of multiple levels of virtual machines? Discuss this with your group and share your conclusions.
10. Compare and contrast the three main types of Cloud computing platforms. As a group come up with a situation where each type would be an appropriate fit and explain your findings.

# Chapter 2

1. Discuss what overflow is and how can it be detected. How does overflow in unsigned numbers differ from overflow in signed numbers? Write up a summary of your conclusions.
2. What is a biased exponent and what efficiencies can it provide? Write up your groups conclusions.
3. Explain what normalization is and why is it necessary.
4. Explain the difference between ASCII and UNICODE.
5. Convert the following decimal values to binary and hexadecimal by hand (no calculators). Make sure everyone in the group arrives at the same answer and understands why and how they got there.

   a) 588   
   b) 2254   
   c) 652   
   d) 3104   
6. Convert the following decimal fractions to binary with a maximum of six places to the right of the radix point. Make sure everyone in the group arrives at the same answer and understands why and how they got there.


   a) 25.84375
   b) 57.55
   c) 80.90625
   d) 84.874023
7. Convert the following binary fractions to decimal. Make sure everyone in the group arrives at the same answer and understands why and how they got there.

   a) 10111.1101   
   b) 100011.10011   
   c) 1010011.10001   
   d) 11000010.111   
8. Convert the hexadecimal number 0xAC12 to binary.
9. Convert the hexadecimal number 0x7A01 to binary.
10. Convert the hexadecimal number 0xDEADBEEF to binary.
11. Represent the following decimal numbers in binary using two's complement and excess-127 representation. Make sure everyone in the group arrives at the same answer and understands why and how they got there.

    a) 60   
    b) −60   
    c) 20   
    d) −20   
12. What decimal value does the 8-bit binary number 10011110 have under the following circumstances? Make sure everyone in the group arrives at the same answer and understands why and how they got there.

    a) it is interpreted as an unsigned number?   
    b) it is on a computer using two’s complement representation?   
    c) it is on a computer using excess-128 representation?   
13. Using a "word" of 3 bits, list all of the possible signed binary numbers and their decimal equivalents that are representable in two's complement.
14. Using a "word" of 4 bits, list all of the possible signed binary numbers and their decimal equivalents that are representable in two's complement.
15. From the results of the previous two questions, generalize the range of values (in decimal) that can be represented in any given x number of bits using two's compliment?
16. Your group has stumbled on an unknown civilization while sailing around the world. The people, who call themselves Zebronians, do math using 40 separate characters (probably because there are 40 stripes on a zebra). They would very much like to use computers, but would need a computer to do Zebronian math, which would mean a computer that could represent all 40 characters. You are a computer designer and decide to help them. You     decide the best thing is to use BCZ, Binary Coded Zebronian (which is like BCD except it codes Zebronian, not Decimal). How many bits will you need to represent each character if you want to use the minimum number of bits?
17. If the floating-point number representation on a certain system has a sign bit, a 3-bit exponent and a 4-bit significand: 

   a) What is the largest positive and the smallest positive number that can be stored on this system if the storage is normalized? (Assume no bits are implied, there is no biasing, exponents use two's complement notation, and exponents of all zeros and all ones are     allowed.)   
   b) What bias should be used in the exponent if we prefer all exponents to be non-negative? Why would you choose this bias?   
