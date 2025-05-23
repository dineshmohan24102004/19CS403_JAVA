# Ex.No:4(E)  PARAMETERIZED CONSTRUCTOR
## AIM:
To create a Java program that initializes student details using a constructor and displays the student's ID, name, and year of studying.

## ALGORITHM :

1.Start.

2.Define a class finals with instance variables name, id, and year.

3.Create a parameterized constructor in finals to initialize these variables.

4.Define a method display() in the finals class to print the student details.

5.Define the print class with the main method.

6.Inside main, create an object of finals by passing the student details.

7.Call the display() method on the object to output the student information.

8.End.


## PROGRAM:
 ```
/*
Program to implement a Parameterized Constructor Using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

class finals{
    String name;
    String id;
    String year;
    finals(String name,String id,String year){
        this.name=name;
        this.id=id;
        this.year=year;
    }
    void display(){
        System.out.println("Student Details are,");
        System.out.println("Id is "+id);
        System.out.println("Name is "+name);
        System.out.println("Year of Studying is "+year);
    }
}
public class print{
    public static void main(String args[]){
        finals obj=new finals("David","S201","3th Year");
        obj.display();
    }
}
*/
```




## OUTPUT:
![Screenshot 2025-05-23 225515](https://github.com/user-attachments/assets/0c2b99c7-ac91-40ac-ad57-3cf33881a3d4)



## RESULT:
The program successfully initializes and displays the student’s ID, name, and year of studying as provided through the constructor.

 


