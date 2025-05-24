# Ex.No:7(E)  POLYMORPHISM

## AIM:
To write a Java program that demonstrates method overloading by defining multiple sum() methods with different parameter types.
## ALGORITHM :
1.Start the program.

2.Define a class HelloWorld with two sum() methods:

3.One method takes two integers as parameters.

4.Another method takes two doubles as parameters.

5.In the main() method:

6.Create a Scanner object to read user input.

7.Read two integer values and two double values from the user.

8.Create an object of the HelloWorld class.

9.Call the sum() method with integer arguments.

10.Call the sum() method with double arguments.

11.Each method prints the result of the sum.

12.End the program.



## PROGRAM:
 ```
/*
Program to implement a Method Overloading in Java
Developed by: Dinesh M
RegisterNumber:  212222040039

import java.util.*;

public class HelloWorld{

        void sum(int a,int b){
    System.out.println(a+b);
   }
  void sum(double a,double b){
    System.out.println(a+b);
  }

  public static void main(String []args)
    {
  HelloWorld obj=new HelloWorld();
  Scanner sc=new Scanner(System.in);
  int a=sc.nextInt();
  int b=sc.nextInt();
  double c=sc.nextDouble();
  double d=sc.nextDouble();
  obj.sum(a,b);
  obj.sum(c,d);
     }
}
*/
```


## OUTPUT:

![Screenshot 2025-05-24 123243](https://github.com/user-attachments/assets/8d6f81b1-7f66-4b39-a116-d9e88cda403d)


## RESULT:
The program successfully demonstrates method overloading by executing the appropriate sum() method based on the argument types and prints the correct results.


