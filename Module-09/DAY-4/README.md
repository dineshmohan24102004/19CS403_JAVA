# Ex.No:9(D) TRANSIENT ---SERILIZATION

## AIM:
To write a Java program to serialize an object of class Employeeinfo and save it to a file using ObjectOutputStream.

## ALGORITHM :
1.Start the program.

2.Create a Scanner object to read input from the user.

3.Read employee details: name, department, and roll number.

4.Create an Employeeinfo object using the input data.

5.Create a FileOutputStream object to open (or create) the file "emp.txt".

6.Wrap the FileOutputStream with an ObjectOutputStream.

7.Use writeObject() method to serialize and write the Employeeinfo object to the file.

8.Close the ObjectOutputStream.

9.Use a try-catch block to handle exceptions.

10.End the program.




## PROGRAM:
 ```
/*
Program to implement a Transient using Java
Developed by: Dinesh M
RegisterNumber:   212222040039

 
 try
        {
            Scanner sc=new Scanner(System.in);
            String name=sc.nextLine();
            String dept = sc.nextLine();
            int rollno=sc.nextInt();
           
            Employeeinfo si1 = new Employeeinfo(name,dept,rollno);
            FileOutputStream fos = new FileOutputStream("emp.txt");
            ObjectOutputStream oos = new ObjectOutputStream(fos);
            oos.writeObject(si1);
            oos.close();
        }
        catch (Exception e)
        {
            System.out.println(e);
        } 
*/
```








## OUTPUT:
![Screenshot 2025-05-24 125530](https://github.com/user-attachments/assets/6c438bf0-1e3b-4c9f-bd2c-d7faa57b19b8)



## RESULT:
The program successfully serializes the Employeeinfo object and writes it to the file "emp.txt" without errors.

