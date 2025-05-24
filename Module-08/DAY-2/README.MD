# Ex.No:8(B) IO-FILE READER/WRITER
## AIM:
To write a Java program that reads characters from the console using InputStreamReader until a specific termination character (#) is entered.


## ALGORITHM :
1.Start the program.

2.Declare an InputStreamReader object to read input from System.in.

3.Use a try-finally block to ensure the input stream is properly closed.

4.Inside the try block:

5.Initialize a character variable c.

6.Use a do-while loop to:

7.Read a character from the console.

8.Print the character.

9.Continue until the character # is encountered.

10.In the finally block, close the InputStreamReader if it's not null.

11.End the program.






## PROGRAM:
 ```
/*
Program to implement a IO File Reader/Writer using Java
Developed by: Dinesh M
RegisterNumber:  212222040039

import java.io.*;
public class ReadConsole {

   public static void main(String args[]) throws IOException {
      InputStreamReader cin = null;

      try {
         cin = new InputStreamReader(System.in);
       //  System.out.println("Enter characters, 'q' to quit.");
         char c;
         do {
            c = (char) cin.read();
            System.out.print(c);
         } while(c != '#');
      }finally {
         if (cin != null) {
            cin.close();
         }
      }
   }
}
*/
```









## OUTPUT:



## RESULT:
The program successfully reads and displays each character typed by the user until the termination character # is entered.



