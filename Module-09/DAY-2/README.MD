# Ex.No:9(B) BYTE ARRAY I/O
## AIM:
To write a Java program that reads bytes from a byte array using ByteArrayInputStream and displays them


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
Program to implement a BYTE ARRAY I/O using Java
Developed by: Dinesh M
RegisterNumber:  212222040039

import java.io.ByteArrayInputStream;
public class Main {
  public static void main(String[] args) {

    // Creates an array of byte
    byte[] array = {1, 2, 3, 4};

    try {
      ByteArrayInputStream input = new ByteArrayInputStream(array);

      System.out.print("The bytes read from the input stream: ");

      for(int i= 0; i < array.length; i++) {

        // Reads the bytes
        int data = input.read();
        System.out.print(data + ", ");
      }
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



## RESULT:
The program successfully reads and prints the bytes from the byte array using ByteArrayInputStream.





