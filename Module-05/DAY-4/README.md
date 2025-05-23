# Ex.No:5(D) IS-A RELATIONSHIP AND HAS-A RELATIONSHIP
## AIM:
  To write a Java program that calculates the area of a triangle using the formula (1/2) * base * height by accepting base and height as input and displaying the calculated area.
 
## ALGORITHM :
1.Start.

2.Create a class tri with a method sum(int a, int b) that calculates and returns the area of the triangle using the formula (a * b) / 2.

3.In the main method of the areaoftri class, create a Scanner object to read user input.

4.Read two integers a (base) and b (height) from the user.

5.Create an object of the tri class.

6.Call the sum method with the inputs a and b to calculate the area.

7.Print the calculated area.

8.End.

## PROGRAM:
 ```
/*
Program to implement a IS-A RELATIONSHIP AND HAS-A RELATIONSHIP using Java
Developed by: Dinesh M
RegisterNumber:212222040039

import java.util.Scanner;
class tri{
   int sum(int a, int b) {
        return ((a*b)/2);
    } 
}
public class areaoftri {
    public static void main(String args[]) {
        int a, b, s;
        Scanner sc = new Scanner(System.in);
        a = sc.nextInt();
        b = sc.nextInt();
        tri dd = new tri();
        s = dd.sum(a, b);
        System.out.println("Area of Triangle is:" + s);
    }
}
*/
```
## OUTPUT:
![Screenshot 2025-05-23 230659](https://github.com/user-attachments/assets/c81a4bd0-0e71-4e6a-a3d9-3a93100aed35)



## RESULT:
The program successfully reads the base and height of a triangle from the user, computes the area using the formula (1/2) * base * height, and displays the correct area.
