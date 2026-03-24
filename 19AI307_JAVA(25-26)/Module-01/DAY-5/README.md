# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:

Write a Java program to reverse a given string.

## AIM:
To write a Java program that reverses a given string entered by the user.

## ALGORITHM :
1.Start the program and read a string input from the user.

2.Create a StringBuilder object with the input string.

3.Use the reverse() method of StringBuilder to reverse the string.

4.Convert the reversed StringBuilder back to a string.

5.Display the reversed string and stop the program.





## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
Developed by: Muthu Poornima P
RegisterNumber:  212224240099
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

public class ReverseString {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String str = scanner.nextLine();
        String reversed = new StringBuilder(str).reverse().toString();
        System.out.println("Reversed string: " + reversed);
        scanner.close();
    }
}
```






## OUTPUT:

<img width="842" height="317" alt="image" src="https://github.com/user-attachments/assets/3646dd59-c855-401f-945f-2cc91981ec54" />



## RESULT:

The program successfully displays the reversed version of the input string.
