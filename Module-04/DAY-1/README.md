# Ex.No:4(A)  JAVA CONSTRUCTOR
## AIM:
To create an Employee class with attributes name, age, and degree, initialize these attributes using a constructor, and display the employee details using a method.

## ALGORITHM :

1.Start.

2.Define a class named Employee.

3.Declare instance variables name, age, and degn (degree).

4.Create a parameterized constructor that accepts name, age, and degn and initializes the instance variables.

5.Define a method display() to print the employee’s name, age, and degree.

6.In the main method, create an Employee object by passing sample data.

7.Call the display() method on the created object to show the details.

8.End.





## PROGRAM:
 ```
/*
Program to implement a Constructor using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

public class Employee
{
    String name;
    int age;
    String degn;
    Employee(String name,int age,String degn){
        this.name=name;
        this.age=age;
        this.degn=degn;
    }
    

    void display()
    {
        System.out.println("Name is:"+name);
        System.out.println("Age is:"+age);
        System.out.println("Degree is:"+degn);
        
    }

    public static void main(String[] args)
    {
        Employee e=new Employee("John",12,"VII");
        e.display();
    }
}

*/
```

## OUTPUT:
![Screenshot 2025-05-23 224228](https://github.com/user-attachments/assets/9dc6103e-439e-4060-b565-cab0a258c6c5)



## RESULT:
The program successfully creates an employee object with specified details and displays the name, age, and degree as output.
