# Ex.No:8(A)           IO-FILE STREAM
## AIM:
To write a Java program to read data from a file using FileInputStream and display the contents on the console.

## ALGORITHM :
1.Start the program.

2.Create a FileInputStream object to open the file "sample.txt".

3.Print a message indicating the start of file data.

4.Read the first byte of the file using read().

5.Use a while loop to continue reading bytes until read() returns -1 (end of file):

6.Convert each byte to a character and print it.

7.Read the next byte.

8.Close the FileInputStream after reading is complete.

9.End the program.


## PROGRAM:
 ```
/*
Program to implement a IO File Stream using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

 
             FileInputStream input = new FileInputStream("sample.txt");

        System.out.println("Data in the file: ");

        // Reads the first byte
        int i = input.read();

       while(i != -1) {
           System.out.print((char)i);

           // Reads next byte from the file
           i = input.read();
        }
        input.close();
      
*/
```








## OUTPUT:
![Screenshot 2025-05-24 123507](https://github.com/user-attachments/assets/f629c78c-dce4-4de4-a7ee-7ab16af60dcb)



## RESULT:
Thus the implementation of a Java Program to write a String in a file "testout.txt" using FileOutputStream was executed and verified successfully

