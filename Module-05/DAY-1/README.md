# Ex.No:5(A)  DATA HIDING AND ENCAPSULATION
## AIM:

To demonstrate encapsulation in Java by creating a Person class with a private age variable and public getter and setter methods, and to use these methods to set and get the age value

## ALGORITHM :
1.Start.

2.Create a class Person with a private integer variable age.

3.Define a public method setAge(int age) to assign a value to age.

4.Define a public method getAge() to return the value of age.

5.In the main method, create a Scanner object to take input from the user.

6.Create an object p1 of the Person class.

7.Read the age input from the user and set it using the setAge() method.

8.Retrieve the age using the getAge() method and display it.

9.End.





## PROGRAM:
 ```
/*
Program to implement a Data Hiding & Encapsulation using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

import java.util.*;
class Person {
  private int age;
  public int getAge() {
    return age;
  }
  public void setAge(int age) {
    this.age = age;
  }
}

public class Main {
  public static void main(String[] args) {
    Scanner sc=new Scanner(System.in);
    Person p1 = new Person();
    p1.setAge(sc.nextInt());
    System.out.println("My age is " + p1.getAge());
  }
}
*/
```


## OUTPUT:

![Screenshot 2025-05-23 225734](https://github.com/user-attachments/assets/d830044a-f383-40c2-ad12-ae561ef5b854)


## RESULT:
The program successfully encapsulates the age variable in the Person class and allows controlled access through getter and setter methods. It reads the age input from the user and correctly displays it.
