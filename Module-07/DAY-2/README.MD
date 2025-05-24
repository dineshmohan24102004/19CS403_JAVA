# Ex.No:7(B) EXCEPTION HANDLING-FINALLY
## AIM:
To write a Java program to demonstrate the use of try-catch-finally block by handling ArithmeticException during division operation.

## ALGORITHM :
1.Start the program.

2.Create a Scanner object to read user input.

3.Initialize an integer variable a with a value (e.g., 100).

4.Prompt the user to input an integer b.

5.Inside the try block:

6.Perform the division of a by b.

7.Display the result if the operation is successful.

8.If an exception occurs (e.g., divide by zero), control passes to the catch block:

9.Catch the ArithmeticException and display an error message.

10.Regardless of whether an exception occurs or not, the finally block will be executed:

11.Print a message indicating the execution of the finally block.

12.Continue executing the rest of the program after the try-catch-finally clause.

13.End the program.



## PROGRAM:
 ```
/*
Program to implement a Exception Handling-Finally using Java
Developed by: Dinesh M
RegisterNumber:  212222040049

import java.util.*;
public class HelloWorld {
    public static void main(String[] args) 
    {
      Scanner sc=new Scanner(System.in);
      try {
          int a=100;
         int b=sc.nextInt();
          int c=a/b;
          System.out.println("Valid Statement :" +c);
      }
      catch(ArithmeticException ex)
        {
            System.out.println("Exception: " +ex);
        }
         
        finally
        {
            System.out.println("Finally block executed");
        }
         
        System.out.println("Outside try-catch-finally clause");
    }
}
      
*/
```









## OUTPUT:



## RESULT:
The program demonstrates proper handling of exceptions using try, catch, and finally blocks. It executes the finally block in both success and failure scenarios.



