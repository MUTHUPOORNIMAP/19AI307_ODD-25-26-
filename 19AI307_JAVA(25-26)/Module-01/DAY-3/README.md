# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:

Write a Java program to calculate the factorial of a number using a for loop. The factorial of n is the product of all positive integers less than or equal to n.

## AIM:
To write a Java program that calculates the factorial of a given number using a for loop.

## ALGORITHM :
1.Start the program and read an integer n from the user.

2.Initialize a variable factorial to 1 to store the result.

3.Use a for loop from 1 to n, multiplying factorial by the loop counter in each iteration.

4.After the loop ends, print the value of factorial as the factorial of n.

5.Stop the program.




## PROGRAM:
 ```
/*
Program to implement a Looping Statement using Java
Developed by: MUTHU POORNIMA P
RegisterNumber:  212224240099
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

public class FactorialCalculator {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();  
        long factorial = 1;

        for (int i = 1; i <= n; i++) {
            factorial *= i;
        }

        System.out.println("Factorial of " + n + " is: " + factorial);
    }
}
```






## OUTPUT:

<img width="887" height="290" alt="image" src="https://github.com/user-attachments/assets/a4073077-99f2-4421-88b5-4b83215dd243" />



## RESULT:

The program successfully computes and displays the factorial value of the entered number.
