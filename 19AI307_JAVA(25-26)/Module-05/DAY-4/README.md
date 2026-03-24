# Ex.No:5(D) THREAD PRIORITY

## QUESTION:
Write a java program for set the priority and name of the current thread.Consider two threads t1 and t2

## AIM:
To write a Java program that demonstrates thread priority by creating two threads, assigning names and priorities to them, and displaying thread execution.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Create a class that extends Thread.
4. Override the run() method to print the current thread name and priority.
5. Create two thread objects t1 and t2.
6. Set names and priorities for each thread using setName() and setPriority().
7. Start both threads.
8. End the program.





## PROGRAM:
 ```
/*
Program to implement a Thread Priority Concept using Java
Developed by: Muthu Poornima P
RegisterNumber:  212224240099
*/
```

## SOURCE CODE:
```
import java.util.*;

public class ThreadPriorityExample {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String name1 = sc.nextLine();
        String name2 = sc.nextLine();
        Thread t1 = new Thread();
        Thread t2 = new Thread();
        t1.setName(name1);
        t2.setName(name2);
        t1.setPriority(4);
        t2.setPriority(2);
        System.out.println(t1);
        System.out.println(t2);

        sc.close();
    }
}
```






## OUTPUT:


<img width="837" height="242" alt="image" src="https://github.com/user-attachments/assets/fd8e54d4-4cab-40bf-8d86-c1514cb64e6c" />


## RESULT:
Thus, the Java program that demonstrates thread naming and thread priority was successfully executed.
