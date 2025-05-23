# Ex.No:6(B) MULTI-LEVEL INHERITANCE

## AIM:
To demonstrate multi-level inheritance in Java by creating a class hierarchy Vehicle → Car → Alto and accessing methods from all the classes using an object of the most derived class.

## ALGORITHM :
1.Start.

2.Define a base class Vehicle with a method display() that prints "Vehicle Class".

3.Define a class Car that extends Vehicle and includes a method print() that prints "Car Class".

4.Define a class Alto that extends Car and includes a method show() that prints "Alto Class".

5.In the main method, create an object of the Alto class.

6.Call the display() method from Vehicle using the Alto object.

7.Call the print() method from Car using the Alto object.

8.Call the show() method from Alto using the same object.

9.End.

## PROGRAM:
 ```
/*
Program to implement a MultiLevel Inheritance using Java
Developed by: Dinesh M
RegisterNumber:  212222040039

class Vehicle {
    public void display() {
        System.out.println("Vehicle Class");
    }
}

class Car extends Vehicle {
    public void print() {
        System.out.println("Car Class");
    }
}

class Alto extends Car {
    public void show() {
        System.out.println("Alto Class");
    }
}

public class Main {
    public static void main(String[] args) {
        Alto alto = new Alto();
        alto.display(); // Accessing Vehicle's display()
        alto.print();   // Accessing Car's print()
        alto.show();    // Accessing Alto's show()
    }
}
*/
```



## OUTPUT:



## RESULT:
The program successfully demonstrates multi-level inheritance where an Alto object can access methods defined in its superclass Car and the grandparent class Vehicle, printing messages from all three classes.





