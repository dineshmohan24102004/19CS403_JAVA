# Ex.No:6(E)  MULTIPLE INHERITANCE

## AIM:
To implement a Java program that demonstrates hierarchical inheritance and the use of constructors in a parent class (Animal) and its child classes (Dog and Cat).

## ALGORITHM :

1.Start.

2.Create a base class Animal with a constructor that prints "Animal is the Base Class".

3.Create a class Dog that extends Animal:

4.Call super() in its constructor to invoke the Animal constructor.

5.Print "Dog is the Derived Class of Animal".

6.Create another class Cat that also extends Animal:

7.Call super() in its constructor to invoke the Animal constructor.

8.Print "Cat is the Derived Class of Animal".

9.In the main method:

Create an object of Dog, which invokes both the Animal and Dog constructors.

Create an object of Cat, which invokes both the Animal and Cat constructors.

10.End.




## PROGRAM:
 ```
/*
Program to implement a Multiple Inheritance
Developed by: Dinesh M
RegisterNumber:  212222040039


class Animal {

    public Animal() {
        System.out.println("Animal is the Base Class");
    }
}

class Dog extends Animal {

    public Dog() {
        super();
        System.out.println("Dog is the Derived Class of Animal");
    }
}
class Cat extends Animal {
    public Cat() {
        super();
        System.out.println("Cat is the Derived Class of Animal");
    }
}

public class Main {
    public static void main(String[] args) {
        Dog dog = new Dog();
        Cat cat = new Cat();
    }
}

*/
```








## OUTPUT:
![Screenshot 2025-05-23 233040](https://github.com/user-attachments/assets/9e7ca841-c68f-4978-8949-83e8d948236d)



## RESULT:

The program successfully demonstrates hierarchical inheritance in Java, where multiple child classes (Dog, Cat) inherit from a common parent class (Animal), and their constructors invoke the parent constructor using super().
