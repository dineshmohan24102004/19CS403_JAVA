# Ex.No:3(B) STRING BUFFER IN JAVA

## AIM:
To write a Java program that reads a string from the user and prints its reverse.


## ALGORITHM :
1.Start.

2.Import the Scanner class from the java.util package to take user input.

3.Create a class named ReverseString.

4.Define the main method.

5.Create a Scanner object to read input from the user.

6.Read the input string using nextLine() and store it in the variable input.

7.Create a StringBuilder object and initialize it with the input string.

8.Use the reverse() method of StringBuilder to reverse the string.

9.Convert the reversed StringBuilder object to a string and print it.

10.End.


## PROGRAM:
 ```
/*
Program to implement a String Buffer using Java
Developed by: Dinesh M
RegisterNumber:  212222040039

import java.util.Scanner;

public class ReverseString {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
      
        String input = scanner.nextLine();
        
        
        StringBuilder reversedString = new StringBuilder(input);
        reversedString.reverse(); 
        
        System.out.println(reversedString.toString());
        
        
    }
}

*/
```

## OUTPUT:



## RESULT:
Thus the java program was executed successfully.
