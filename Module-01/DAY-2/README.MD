# Ex.No:1(B) VARIABLES AND OPERATOR

## AIM:
To accept an integer input from the user and display its corresponding English word if it is a prime number among 2, 3, 5, or 7 using a switch-case statement. If the input is not one of these primes, display an appropriate message.

## ALGORITHM :
1.Start the program.

2.Import the Scanner class to accept user input.

3.Create an object sc of the Scanner class.

4.Prompt the user to enter an integer and store it in variable n1.

5.Use a switch statement to compare n1:

6.If n1 is 2, print "TWO".

7.If n1 is 3, print "THREE".

8.If n1 is 5, print "FIVE".

9.If n1 is 7, print "SEVEN".

10.Otherwise, print "please enter valid prime number".

11.End the program.







## PROGRAM:
 ```
/*
Program to implement a variable and operators using Java
Developed by: Dinesh M
RegisterNumber:  212222040039

import java.util.Scanner;
public class Demo {

	public static void main(String[] args) {		
		 Scanner sc = new Scanner(System.in);
             int n1 = sc.nextInt();
		 switch(n1)
		{
			case 2 : System.out.println("TWO");
				   break;
			case 3 : System.out.println("THREE");
				   break;
			case 5 : System.out.println("FIVE");
				   break;
			case 7 : System.out.println("SEVEN");
				   break;
			default : System.out.println("please enter valid prime number");
		}
	}
}

*/
```

## OUTPUT:



## RESULT:
Thus, The program successfully matches the input with known small prime numbers using a switch and displays the correct word representation or an error message otherwise.
