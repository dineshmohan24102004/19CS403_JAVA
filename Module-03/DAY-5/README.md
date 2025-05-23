# Ex.No:3(E)  STRINGBUILDER OBJECT REFERENCE IN JAVA

## AIM:
To write a Java program that reads a string from the user, replaces a portion of the string from index 1 to 3 with the word "Java", and prints the modified string.



## ALGORITHM :
1.Start.

2.Import the Scanner class for input.

3.Create the class StringBufferExample3.

4.Define the main method.

5.Create a Scanner object to read input from the user.

6.Read a full line string input and store it in str1.

7.Create a StringBuilder object sb initialized with the input string str1.

8.Use the replace(start, end, str) method on sb to replace characters from index 1 to 3 with "Java".

9.Print the modified string from sb.

10.End.


## PROGRAM:
 ```
/*
Program to implement a StringBuilder Object Reference in Java
Developed by: Dinesh M
RegisterNumber: 212222040039

import java.util.*;
public class StringBufferExample3{  
public static void main(String args[]){ 
Scanner sc=new Scanner(System.in);
String str1=sc.nextLine();
StringBuilder sb=new StringBuilder(str1);  
sb.replace(1,3,"Java");  
System.out.println(sb); 
}  
}  
*/
```


## OUTPUT:
![Screenshot 2025-05-23 223808](https://github.com/user-attachments/assets/a2d15300-ae93-4da6-b478-408e252e4dd7)



## RESULT:
The program successfully replaces the characters from index 1 to 3 of the input string with "Java" and outputs the modified string.

