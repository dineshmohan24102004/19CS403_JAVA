# Ex.No:4(B) INTRODUCTION TO JAVA INHERITANCE

## AIM:
To demonstrate single inheritance in Java by creating a base class Animal with methods eat and sleep, and a derived class Bird that inherits from Animal and adds a method fly. Then, call these methods to show inheritance.



## ALGORITHM :
1.Start.

2.Define a base class Animal with two methods: eat() and sleep(), which print messages.

3.Define a subclass Bird that extends the Animal class and adds a new method fly().

4.In the main method of class Ans, create an object of Animal and call its methods eat() and sleep().

5.Create an object of Bird and call the inherited methods eat(), sleep(), and its own method fly().

6.Observe the output demonstrating inheritance.

7.End.








## PROGRAM:
 ```
/*
Program to implement a Inheritance using Java
Developed by: Dinesh M
RegisterNumber:  212222040039

class Animal {
    void eat() {
        System.out.println("Calling get Method");
    }

    void sleep() {
        System.out.println("Calling display Method");
    }
}

class Bird extends Animal {
    void fly() {
        System.out.println("Calling process Method");
    }
}

public class Ans {
    public static void main(String[] args) {
        Animal animalObj = new Animal();
        animalObj.eat();
        animalObj.sleep();
        Bird birdObj = new Bird();
        birdObj.eat();
        birdObj.sleep();
        birdObj.fly();
    }
}
*/
```

## OUTPUT:



## RESULT:
The program successfully demonstrates single inheritance where the Bird class inherits methods from the Animal class and adds its own method. The output shows calls to the base class methods and the subclass method as expected.

