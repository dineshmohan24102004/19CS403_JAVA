# Ex.No:3(C)    STRING BUILDER IN JAVA

## AIM:
To write a Java program that takes two inputs—a string (possibly with spaces) and a word—and appends the second input to the first with a space in between, then prints the combined result.



## ALGORITHM :
1.Start.

2.Import Scanner from java.util to read input from the user.

3.Create the class Assignment11.

4.Define the main method.

5.Create a Scanner object sc for input.

6.Read a full line input from the user and store it in the string variable a.

7.Read the next token (word) input from the user and store it in the string variable c.

8.Create a StringBuilder object b initialized with the string a.

9.Append a space and the string c to b.

10.Print the resulting string from the StringBuilder object b.

11.End.






## PROGRAM:
 ```
/*
Program to implement a String Builder using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

import java.util.Scanner;
public class Assignment11 {

	public static void main(String[] args) {
	    Scanner sc=new Scanner(System.in);
		String a =sc.nextLine();
		String c=sc.next();
	
		StringBuilder b = new StringBuilder(a);
		b.append(" "+c);
		System.out.print(b);

	}

}
*/
```


## OUTPUT:

![Screenshot 2025-05-23 223117](https://github.com/user-attachments/assets/36d3cde1-5c71-4142-8b2b-64146702ebc4)


## RESULT:
The program successfully takes a line of text and a separate word as input from the user, then appends the word to the end of the input line with a space in between, and finally prints the combined string as output.



