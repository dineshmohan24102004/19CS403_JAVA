# Ex.No:8(E)  INPUT STREAM READER.

## AIM:
To write a Java program that reads and displays the contents of a file using FileReader and BufferedReader classes.


## ALGORITHM :
1.Start the program.

2.Create a FileReader object to open the file "sample.txt".

3.Wrap the FileReader object with a BufferedReader for efficient reading.

4.Initialize an integer variable to hold the read character.

5.Use a while loop to read characters one by one until end-of-file (-1) is reached:

6.Convert the integer to a character.

7.Print the character.

8.After reading, print a newline for formatting.

9.Close the BufferedReader and FileReader objects to release resources.

10.End the program.

## PROGRAM:
 ```
/*
Program to implement a INPUT STREAM READER
Developed by: Dinesh M
RegisterNumber: 212222040039

          FileReader fr=new FileReader("sample.txt");   
          BufferedReader br=new BufferedReader(fr);    
          int i;    
          while((i=br.read())!=-1)
          {  
          System.out.print((char)i);  
          }  
            System.out.print("\n");
          br.close();    
          fr.close(); 
*/
```








## OUTPUT:
![Screenshot 2025-05-24 124647](https://github.com/user-attachments/assets/3661ead3-0014-426c-a579-70584ced15da)



## RESULT:
Thus, the java program uses InputStreamReader to read input and handles loop termination based on the presence of # at the end of the input string, as specified. 

