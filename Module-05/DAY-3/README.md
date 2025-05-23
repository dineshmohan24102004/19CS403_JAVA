# Ex.No:5(C)    GETTER AND SETTER METHOD

## AIM:
To demonstrate encapsulation in Java by using private variables with public getter and setter methods to set and get the value of an integer variable.

## ALGORITHM :
1.Start.

2.Define a class Rec with a private integer variable a initialized to 24.

3.Create a public method get() to return the value of a.

4.Create a public method set(int a) to assign a new value to a.

5.In the main method, create an object e of class Rec.

6.Use the set() method to set the value of a to 24.

7.Use the get() method to retrieve the value of a.

8.Print the value retrieved with a message.

9.End.


## PROGRAM:
 ```
/*
Program to implement a Getter and Setter using Java
Developed by: Dinesh M
RegisterNumber:  212222040039

import java.util.*;
class Rec{
    private int a=24;
    public int get(){
        return a;
    }
    public void set(int a)
    {
        this.a=a;
    }
    
}
public class Main{
    public static void main(String args[]){
        Rec e=new Rec();
        e.set(24);
        System.out.print("My age is "+e.get());
    }
}
*/
```



## OUTPUT:

![Screenshot 2025-05-23 230325](https://github.com/user-attachments/assets/241898b7-4e74-451f-b7d5-2aecb6911420)


## RESULT:
The program successfully encapsulates the variable a, allowing controlled access through getter and setter methods, and displays the assigned value correctly.





