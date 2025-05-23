# Ex.No:6(C)             HIERARCHICAL INHERITANCE 

## AIM:
 To demonstrate hierarchical inheritance in Java by creating a base class ArithmeticOperation and two derived classes Addition and Subtraction, each implementing their respective arithmetic operations.


## ALGORITHM :
1,Start.

2,Create a base class ArithmeticOperation with a method displayOperation() (empty or to be optionally overridden).

3,Create a subclass Addition that extends ArithmeticOperation and includes a method add(int a, int b) to add two numbers.

4,Create another subclass Subtraction that also extends ArithmeticOperation and includes a method subtract(int a, int b) to subtract two numbers.

5.In the main method:
a. Create an object of class Addition.
b. Call displayOperation() and add() methods using the object.
c. Create an object of class Subtraction.
d. Call displayOperation() and subtract() methods using the object.

6.End.




## PROGRAM:
 ```
/*
Program to implement a Hierarchical Inheritance using Java
Developed by: Dinesh M
RegisterNumber:  21222204039

class ArithmeticOperation {
    public void displayOperation() {
        
    }
}
class Addition extends ArithmeticOperation {
    public void add(int a, int b) {
        System.out.println("Addition of 2 values " + (a + b));
    }
}

class Subtraction extends ArithmeticOperation {
    public void subtract(int a, int b) {
        System.out.println("Subtraction of 2 values " + (a - b));
    }
}

public class Main {
    public static void main(String[] args) {
        Addition addition = new Addition();
        Subtraction subtraction = new Subtraction();

        addition.displayOperation(); // Accessing parent class member
        addition.add(10, 5);

        subtraction.displayOperation(); // Accessing parent class member
        subtraction.subtract(10, 5);
    }
}
*/
```

## OUTPUT:

![Screenshot 2025-05-23 232210](https://github.com/user-attachments/assets/1020bd18-5919-431c-9b0f-d6e839ced7ea)


## RESULT:
The program successfully demonstrates hierarchical inheritance by creating separate child classes that inherit from a common base class, allowing them to access inherited methods and implement their specific operations like addition and subtraction.






