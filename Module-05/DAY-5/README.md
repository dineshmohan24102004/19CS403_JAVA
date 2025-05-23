# Ex.No:5(E) HAS-A RELATIONSHIP
## AIM:

To create a base class Calculation with methods for addition and subtraction, extend it with a subclass My_Calculation that adds multiplication, and demonstrate method calls from both classes.
## ALGORITHM :
1.Start.

2.Define a class Calculation with an integer variable z.

3.Implement a method addition(int x, int y) in Calculation that calculates and prints the sum of x and y.

4.Implement a method Subtraction(int x, int y) in Calculation that calculates and prints the difference between x and y.

5.Define a subclass My_Calculation that extends Calculation.

6.Add a method multiplication(int x, int y) in My_Calculation that calculates and prints the product of x and y.

7.In the main method, create an instance of My_Calculation.

8.Call the inherited methods addition and Subtraction and the subclass method multiplication using the instance.

9.End.





## PROGRAM:
 ```
/*
Program to implement a HAS-A RelationShip
Developed by: Dinesh M
RegisterNumber:  212222040039

class Calculation {
   int z;
	
   public void addition(int x, int y) {
      z = x + y;
      System.out.println("The sum of the given numbers:"+z);
   }
	
   public void Subtraction(int x, int y) {
      z = x - y;
      System.out.println("The difference between the given numbers:"+z);
   }
}

public class My_Calculation extends Calculation {
   public void multiplication(int x, int y) {
      z = x * y;
      System.out.println("The product of the given numbers:"+z);
   }
	
   public static void main(String args[]) {
      int a = 20, b = 10;
      My_Calculation demo = new My_Calculation();
      demo.addition(a, b);
      demo.Subtraction(a, b);
      demo.multiplication(a, b);
   }
}
*/
```








## OUTPUT:
![Screenshot 2025-05-23 231110](https://github.com/user-attachments/assets/6bf15a8f-58e6-4038-b798-2112891c18a2)



## RESULT:
The program successfully demonstrates inheritance by calling methods from the base class and subclass to perform addition, subtraction, and multiplication on given numbers, displaying the results accordingly.

