# Ex.No:8(C)             FILTER READER
## AIM:
To write a Java program that reads characters from a string using StringReader and displays them using a character array.


## ALGORITHM :
1.Start the program.

2.Import the necessary classes (java.io.* and java.util.*).

3.Create a Scanner object to take string input from the user.

4.Read a line of text using nextLine().

5.Create a character array with a specified size (e.g., 39).

6.Use a try-catch block to handle exceptions:

7.Initialize a StringReader object with the input string.

8.Use the read(char[]) method to read the string into the character array.

9.Print the message "Data read from the string:".

10.Print the content of the character array.

11.Close the StringReader.

12.In the catch block, handle any exceptions.

12.End the program.


## PROGRAM:
 ```
/*
Program to implement a Filter Reader using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

    import java.io.*;  
    import java.util.*;
    public class JavaCharArrayReaderReadExample4 {  
       public static void main(String[] args) {  
    Scanner sc=new Scanner(System.in);
    String data=sc.nextLine();
   
    char[] array = new char[39];
    try {
      // Create a StringReader
      StringReader input = new StringReader(data);
      //Use the read method
      input.read(array);
      System.out.println("Data read from the string:");
      System.out.println(array);
      input.close();
    }
    catch(Exception e) {
      e.getStackTrace();
    }
       }  
    }  
*/
```









## OUTPUT:
![Screenshot 2025-05-24 124145](https://github.com/user-attachments/assets/fe7e72d9-915b-4d3d-8e52-c70d84d006e4)



## RESULT:
The program successfully reads a string input using StringReader and prints the contents using a character array.









