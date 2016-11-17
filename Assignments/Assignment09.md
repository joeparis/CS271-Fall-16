**Due November 29**

1. What are the potential problems (perhaps more than one) with the following assembly language code fragment (implementing a subroutine) written to run on MARIE? The subroutine assumes the parameter to be passed is in the AC and should double this value. The Main part of the program includes a sample call to the subroutine. You can assume this fragment is part of a larger program.

    ```
    Main, Load   X
          Jump   Sub1
    Sret, Store  X
      . . .
    Sub1, Add    X
          Jump   Sret
    ```

2. Write a MARIE program to evaluate the expression A x B + C x D. Turn in your `.mas` file named 9_2. Be sure to include all the names of your group members in comments at the top of the file.
3. Write the following code segment in MARIE assembly language. (Hint: Turn the for loop into a while loop):
    ```
    Sum = 0;
   
    for X = 1 to 10 do   
      Sum = Sum + X;
    ```
4. Write a MARIE program using a loop that multiplies two positive numbers by using repeated addition. For example, to multiple 3 x 6, the program would add 3 six times, or 3+3+3+3+3+3. Your program should take input from the user. Turn in your `.mas` file named 9_4. Be sure to include all the names of your group members in comments at the top of the file.
5. Write a MARIE subroutine to subtract two numbers. Your program should take input from the user. Turn in your `.mas` file named 9_5. Be sure to include all the names of your group members in comments at the top of the file.
6. Write a MARIE program that will find the smaller of two numbers entered by the user. Turn in your `.mas` file named 9_6. Be sure to include all the names of your group members in comments at the top of the file.
7. Write a MARIE program that will find the smallest of a set of numbers entered by the user. The first number the user will provide will be the count of all the numbers to be compared (this will never be greater than 10) followed by the numbers themselves. Turn in your `.mas` file named 9_7. Be sure to include all the names of your group members in comments at the top of the file.
