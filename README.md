# C-Program-to-check-if-a-Number-Is-Positive-Or-Negative

Check if a Number is Positive or Negative in C
Given an integer input, The objective is to write a code to Check if a Number is Positive or Negative in C Language.

For Instance,
Input : Num = -5
Output : The number is Negative
Check if a Number is Positive or Negative in C
Check if a Number is Positive or Negative in C
Given an integer input, the objective is check whether the given integer is Positive or Negative. In order to do so we have the following methods,

Method 1: Using Brute Force
Method 2: Using Nested if-else Statements
Method 3: Using the ternary operator
We’ll discuss each method in-depth in the section below.

While loop in C
Check if a Number is Positive or Negative in C
Related Pages
Even or Odd number 

Sum of First N Natural numbers

Sum of N natural numbers

Sum of numbers in a given range

Prime number within a given range

Method 1: Using Brute Force
This method uses Brute Force to check whether a given integer is Positive or Negative.

C Code
Run
#include <stdio.h>
int main()
{
    int num = 23;
      
    //Conditions to check if the number is negative/positive or zero
    if (num > 0)
         printf("The number is positive");
    else if (num < 0)
        printf("The number is negative");
    else
        printf("Zero");
    
    return 0;
}
Output
Insert a number: 23
The number is Positive
Algorithm
For a user input num

If the num > 0: it is a positive number.
If the num < 0: it is a positive number.
Else the number has to be zero itself
Same logic we have followed in the below C program. 

Method 2: Using Nested if-else Statements
This method uses a nested if-else Statements to check whether a given number is Positive or Negative.

C Code
Run
#include <stdio.h>
int main()
{
    int num = -10;
    
    //Condition to check if num is negative/positive or zero
    if (num >= 0)
    {
        if (num == 0)
            printf("The number is 0");
        else
            printf("The number is Positive");
    }
    else
        printf("The number is Negative");
    
    return 0;
}
Output
Insert a number: -10
The number is Negative
Algorithm
This method uses a nested if-else Statements to check whether a given number is Positive or Negative.

For a user input num

If the num >= 0
If num == 0 : num is zero
Else number has to be positive 
Else the number has to be negative
Same logic we have followed in the below C program. 

Method 3: Using Ternary Operators
This method uses a ternary operator in C to check whether a number is Positive or Negative.

C Code
Run
#include <stdio.h>
int main()
{
    int num = -4;
    
    //Condition to check if the 0, positive or negative
    
    if(num == 0)
        printf("Zero");
    else
        (num > 0) ? printf("Positive"): printf("Negative");
    
    return 0;
}
Output
Insert a number: -4
Negative
Algorithm
This method uses a ternary operator to check whether a number is Positive or Negative.

For a user input num

If the num == 0 num is zero
Else (num > 0) ? printf(“Positive”): printf(“Negative”);
Same logic we have followed in the below C program. 
