# Ex.No:2(D) MULTI-DIMENSIONAL ARRAY

## AIM:
To write a Java program to demonstrate how primitive data types and arrays are passed to methods

## ALGORITHM :
1.Start the program.

2.Declare an integer variable x and initialize it with a value.

3.Declare and initialize an integer array num.

4.Call the method m1, passing x and num as arguments.

5.Inside method m1:

6.Assign a new value to x.

7.Modify the second element of the array (num[1]).

8.Return to main and print the values of x and num[1].

9.End the program.



## PROGRAM:
 ```
/*
Program to implement a Multi Dimensional Array using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

public class PassingArrays {
public static void main(String[] args) 
{
  int x = 2; 
  int[ ] num = {0, 1}; 
   m1(x, num);
   System.out.println("Value of x: " +x);
   System.out.print("Value of num[1]: " +num[1]);
 }
public static void m1(int x, int[ ] num) 
{
   x = 5; 
   num[1] = 20; 
 }
}
*/
```

## OUTPUT:

![Screenshot 2025-05-23 212529](https://github.com/user-attachments/assets/8f5beed9-1633-4885-975c-0f012e733dd0)


## RESULT:
The program successfully demonstrates that primitive variables remain unchanged when passed to methods, whereas changes to array elements within methods affect the original array.


