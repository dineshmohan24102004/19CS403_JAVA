# Ex.No:7(A)           EXCEPTION HANDLING-RUN TIME EXCEPTION
## AIM:
To write a Java program that performs division of two integers and handles ArithmeticException when dividing by zero.

## ALGORITHM :
1.Start the program.

2.Create a Scanner object to read input from the user.

3.Prompt the user to enter two integers.

4.Read the first integer (a).

5.Read the second integer (b).

6.Use a try-catch block to handle exceptions:

7.Inside the try block, perform the division a / b.

8.Print the result.

9.Catch ArithmeticException if division by zero occurs and display an appropriate error message.

10.End the program.









## PROGRAM:
 ```
/*
Program to implement a Exception Handling-Run Time Exception using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

import java.util.Scanner;

public class HelloWorld {
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
           try
           {
               int a=sc.nextInt();
             int b=sc.nextInt();
             int c=a/b;
             System.out.println("Result: " +c); 
           }
               catch(ArithmeticException e)  
        {  
            System.out.println("Arithmetic Exception: Number should not divide by zero");  
        }  
    }
}
*/
```









## OUTPUT:
![Screenshot 2025-05-24 121916](https://github.com/user-attachments/assets/9e9db2f3-f4d2-497b-9bb3-9c61ffb76924)



## RESULT:
The program successfully takes two integer inputs from the user and performs division. It displays the result if the division is valid or catches and handles the ArithmeticException if the divisor is zero.

