# Ex.No:1(A) INTRODUCTION TO JAVA PROGRAMMING, DATA TYPES, VARIABLES AND OPERATORS

## QUESTION:
Lovely found a magic machine that tells her how two numbers relate to each other.
The machine supports all 6 relational operators:
Operator	Meaning

==	Is equal to

!=	Is not equal to

>	Greater than

<	Less than

>=	Greater than or equal to

<=	Less than or equal to
Lovely enters two numbers. The machine prints the result (true or false) for each operator.

Input Format
First line: First integer number (a)

Second line: Second integer number (b)

Output Format
Print:

a == b: <true/false>

a != b: <true/false>

a > b: <true/false>

a < b: <true/false>

a >= b: <true/false>

a <= b: <true/false>


## AIM:
To write a program that takes two integer inputs and evaluates all six relational operators (==, !=, >, <, >=, <=) between them, then prints whether each comparison is true or false.


## ALGORITHM :
Step 1:

Start the program.

Step 2:

Read the first integer input and store it in variable a.

Step 3:

Read the second integer input and store it in variable b.

Step 4:

Evaluate the relational expressions:

Print the result

Step 5:

End the program.



## PROGRAM:
 ```
Program to implement variables and Operators using Java 
Developed by: PANIMALAR P
RegisterNumber:  212222110031

```

## Sourcecode.java:


````
import java.util.*;
public class Main
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        System.out.println("a == b: "+(a==b));
        System.out.println ("a != b: "+ (a!=b));
        System.out.println("a > b: "+ (a>b));
        System.out.println("a < b: "+(a<b));
        System.out.println("a >= b: " +(a>=b));
        System.out.println("a <= b: "+(a<=b));
        
    }
}
````





## OUTPUT:

<img width="1122" height="592" alt="image" src="https://github.com/user-attachments/assets/18ceb9d3-1d94-4d58-9346-9f4667189f81" />


## RESULT:
The program compares the two numbers using all relational operators and checks whether they are equal, not equal, greater, or less. It then prints true or false for each comparison based on the relationship between the two numbers.



