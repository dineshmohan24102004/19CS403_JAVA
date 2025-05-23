# Ex.No:5(B) TIGHTLY ENCAPSULATED CLASS

## AIM:

To write a Java program that uses setter methods to accept two string inputs representing numbers, converts them to integers, multiplies them, and displays the product.

## ALGORITHM :
1.Start.

2.Define a class SetAndGet with two private string variables a and b.

3.Create a method setadd(String a, String b) to set the values of a and b.

4.Create a method getadd() to convert the string variables a and b to integers, multiply them, and print the product.

5.In the main method, create a Scanner object to take input from the user.

6.Read two lines of input as strings.

7.Create an instance of the SetAndGet class.

8.Use the setter method to assign the input values to a and b.

9.Call the getadd() method to compute and display the product.

10.End.









## PROGRAM:
 ```
/*
Program to implement a tightly encapsulated class using Java
Developed by: Dinesh M
RegisterNumber:  212222040039

import java.util.*;
public class SetAndGet {
private String a;
private String b;

public void getadd() {
    int a1=Integer.parseInt(a);
    int b1=Integer.parseInt(b);
	System.out.print("Product is " + (a1*b1)); 
	
}
public void setadd(String a,String b) {
     this.a =a;
     this.b=b;
}

public static void main(String args[]){
     Scanner sc=new Scanner(System.in);
     SetAndGet obj = new SetAndGet();
     String str=sc.nextLine();
     String str1=sc.nextLine();
     obj.setadd(str,str1);
     obj.getadd();
    }
}

*/
```



## OUTPUT:


## RESULT:
The program successfully accepts two numeric strings as input, converts them to integers, calculates their product, and displays the result.



