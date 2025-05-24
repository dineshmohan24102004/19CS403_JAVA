# Ex.No:8(D) BUFFER INPUT/OUTPUT STREAM

## AIM:
To create a custom filter by extending FilterWriter that replaces all occurrences of the character 'E' with 'A' while writing data.

## ALGORITHM :
1.Start the program.

2.Define a class CustomFilterWriter that extends FilterWriter.

3.Create a constructor that accepts a Writer object and passes it to the superclass constructor.

4.Override the write(String str) method:

5.Replace all occurrences of 'E' with 'A' in the input string.

6.Write the modified string using the superclass's write() method.

7.End the program.




## PROGRAM:
 ```
/*
Program to implement a Buffer Input/Output Stream using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

    import java.io.*;  
    class CustomFilterWriter extends FilterWriter {  
        CustomFilterWriter(Writer out) {  
            super(out);  
        }  
        public void write(String str) throws IOException {  
            super.write(str.replace('E','A'));  
        }  
    }  
   
*/
```








## OUTPUT:
![Screenshot 2025-05-24 124402](https://github.com/user-attachments/assets/538f6afb-3b33-4bc7-8ce9-e1d4adf2d31f)



## RESULT:
The program successfully filters the output stream by replacing every 'E' character with 'A' before writing the string.


