# Ex.No:9(A)          DATA I/O STREAM
## AIM:
To write a Java program that writes primitive data types (int, double, char) to a file using DataOutputStream.

## ALGORITHM :
1,Start the program.

2.Create a FileOutputStream object to open or create the file "testout.txt".

3.Wrap the FileOutputStream with a DataOutputStream to write primitive data types.

4.Create a Scanner object to take input from the user.

5.Read an integer, a double, and a character from the user.

6.Use writeInt(), writeDouble(), and writeChar() methods of DataOutputStream to write the data to the file.

7.Close both DataOutputStream and FileOutputStream objects to release resources.

8.Print a success message.

9.End the program.


## PROGRAM:
 ```
/*
Program to implement a DATA I/O STREAM using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

FileOutputStream fout=new FileOutputStream("testout.txt");    
DataOutputStream dout=new DataOutputStream(fout);
Scanner sc=new Scanner(System.in);
int num=sc.nextInt();
double db=sc.nextDouble();
char ch=sc.next().charAt(0);
                 dout.writeInt(num);  
                 dout.writeDouble(db);
                 dout.writeChar(ch);
                 dout.close();    
                 fout.close();
                 System.out.println("Successfully Completed");  
                 
*/
```



## OUTPUT:
![Screenshot 2025-05-24 124911](https://github.com/user-attachments/assets/0025ddd2-3f65-46ce-8719-fe7091a2e292)



## RESULT:
The program successfully writes an integer, a double, and a character to "testout.txt" in binary format, and displays a completion message.

