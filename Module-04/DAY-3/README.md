# Ex.No:4(C)    CONSTRUCTOR CHAINING(SUPER KEYWORD)

## AIM:
To write a Java program demonstrating constructor invocation in inheritance where the constructor of the superclass Vehicle is called before the subclass Car constructor

## ALGORITHM :
1.Start.

2.Create a class Vehicle with a constructor that prints "I am a Vehicle".

3.Create a subclass Car that extends Vehicle and has its own constructor printing "I am a Car".

4.In the main method of the Main class, create an object of the Car class.

5.When the Car object is created, the Vehicle constructor is automatically invoked first, followed by the Car constructor.

6.Observe the output displaying messages from both constructors.

7.End.


## PROGRAM:
 ```
/*
Program to implement a Constructor Chaining using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

 class Vehicle {
    //Write Your Code Here
    Vehicle()
    {
        System.out.println("I am a Vehicle");
    }
}

class Car extends Vehicle {
    //Write Your Code Here
    Car()
    {
        System.out.println("I am a Car");
    }
}
public class Main {
    public static void main(String[] args) {
        //Write Your Code Here
        Car car=new Car();
    }
}
*/
```

## OUTPUT:
![Screenshot 2025-05-23 224848](https://github.com/user-attachments/assets/8013d7ba-0b96-4798-9a6a-c87808686621)



## RESULT:
The program successfully demonstrates constructor chaining in inheritance. When a Car object is created, the output shows the message from the Vehicle constructor followed by the message from the Car constructor.






