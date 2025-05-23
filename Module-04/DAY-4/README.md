# Ex.No:4(D) FINAL & STATIC IN JAVA

## AIM:
To create a Java class with final instance variables, initialize them through a constructor, and display the student details including a fixed year of study.
 
## ALGORITHM :
1.Start.

2.Declare a class named Class with three private final variables: name, id, and year (initialized to "3th Year").

3.Define a constructor that accepts name and id as parameters and initializes the respective variables.

4.Create a method printDetails() to print the student’s ID, name, and year of study.

5.In the main method, create an instance of Class by passing the student’s name and ID.

6.Call the printDetails() method on the object to display the details.

7.End.


## PROGRAM:
 ```
/*
Program to implement a final & Static using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

public  class Class {

    private final String name;
    private final String id;
    private final String year = "3th Year"; // Final variable with fixed value

    public Class(String name, String id) {
        this.name = name;
        this.id = id;
    }

    public void printDetails() {
        System.out.println("Student Details are,");
        System.out.println("Id is " + id);
        System.out.println("Name is " + name);
        System.out.println("Year of Studying is " + year);
    }

    public static void main(String[] args) {
        Class student = new Class("David", "S201");
        student.printDetails();
    }
}

*/
```


## OUTPUT:

![Screenshot 2025-05-23 225147](https://github.com/user-attachments/assets/0d6c3733-864c-4231-8537-ca382f243ea1)


## RESULT:
Thus, the java program to perform final & static keyword was executed successfully.
