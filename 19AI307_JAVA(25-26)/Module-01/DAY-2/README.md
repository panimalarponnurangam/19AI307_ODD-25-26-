# Ex.No:1(B) CONDITIONAL STATEMENT



## QUESTION:
A pirate ship has a code lock that only opens if:

The input code is even, and

If it is less than 100, say "Weak Code".

If it is between 100 and 999, say "Strong Code".

If the code is odd, deny access -"Access Denied".


## AIM:
To design a program that checks whether the entered code is even or odd, and based on its value, displays whether it is a Weak Code, Strong Code, or Access Denied.

## ALGORITHM :


Start the program.

Input the code (integer).

Check if the code is odd:

If odd → print "Access Denied".

If the code is even:

If the code is < 100 → print "Weak Code".

If the code is between 100 and 999 → print "Strong Code".

End the program.




  

## PROGRAM:

 ```
Program to implement a conditional statement using Java 
Developed by: PANIMALAR P
RegisterNumber:  212222110031

```



## SOURCE CODE:


```


import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int code = sc.nextInt();

        if (code % 2 == 0) {         
            if (code < 100)
                System.out.println("Weak Code");
            else if (code >= 100 && code <= 999)
                System.out.println("Strong Code");
            else
                System.out.println("Access Denied");  
        } else {
            System.out.println("Access Denied");
        }
    }
}

```


## OUTPUT:


<img width="2431" height="642" alt="image" src="https://github.com/user-attachments/assets/d1c2cb62-6087-480b-a3d7-8fddf3322ca6" />

## RESULT:
The program has been executed successfully and the desired output has been obtained.
