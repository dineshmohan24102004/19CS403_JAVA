# Ex.No:9(C)             STRING READER
## AIM:
 To Create a Java Program to display and skip the specified number of characters using the predefined Method Skip in StringReader


## ALGORITHM :
1.Start the program.

2.Create a byte array with some predefined values.

3.Initialize a ByteArrayInputStream object using the byte array.

4.Print a message indicating the start of the byte reading process.

5.Use a for loop to read each byte from the input stream:

6.Call read() to get the next byte.

7.Print the byte value.

8.Close the ByteArrayInputStream.

9.Handle any exceptions using a try-catch block.

10.End the program.


## PROGRAM:
 ```
/*
Program to implement a String Reader using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

import java.io.StringReader; 
import java.util.*;
public class StringReaderExample {  
    public static void main(String[] args) throws Exception 
    {  
        Scanner sc=new Scanner(System.in);
        String srg = sc.nextLine();  
        StringReader reader = new StringReader(srg);  
        int k=0; 
            while((k=reader.read())!=-1){  
                System.out.print((char)k);  
            }  
        }  
}  
*/
```









## OUTPUT:

![Screenshot 2025-05-24 125302](https://github.com/user-attachments/assets/87a029de-47be-4179-bc03-04022e7327ba)


## RESULT:
The program successfully reads and prints the bytes from the byte array using ByteArrayInputStream.










