# Ex.No:9(E) STRING WRITER

## AIM:
To write a Java program that deserializes a Studentinfo object from a file and displays its data.
## ALGORITHM :

1.Start the program.

2.Declare a Studentinfo reference initialized to null.

3.Use a try-catch block to handle exceptions.

4.Inside the try block:

5.Create a FileInputStream object to open the file "student.txt".

6.Wrap it with an ObjectInputStream.

7.Use readObject() method to read and cast the object to Studentinfo.

8.In the catch block, print any exceptions encountered.

9.Print the deserialized student details (name and rid).

10.End the program.


## PROGRAM:
 ```
/*
Program to implement a STRING WRITER
Developed by: Dinesh M
RegisterNumber: 212222040039

 Studentinfo si=null;
  try
        {
            FileInputStream fis = new FileInputStream("student.txt");
            ObjectInputStream ois = new ObjectInputStream(fis);
            si = (Studentinfo)ois.readObject();
        }
         catch (Exception e)
        {
            System.out.println(e);
            }
             System.out.println("Deserialization-Student Name:"+si.name);
            System.out. println("Deserialization-Student Rollno:"+si.rid);
       
           
 
*/
```









## OUTPUT:

![Screenshot 2025-05-24 125808](https://github.com/user-attachments/assets/e758ad28-88ff-45a4-ae54-5d912e2e3de1)


## RESULT:
The program successfully reads the serialized Studentinfo object from "student.txt" and prints the student's name and roll number.
