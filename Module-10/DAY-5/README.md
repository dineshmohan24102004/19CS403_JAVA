# Ex.No:10(E)  JAVA LINKEDHASH SET

## AIM:
To write a Java program that stores a list of strings (car names) in a LinkedList, and retrieves the element at index 1 using the .get() method.

## ALGORITHM :
1.Start.

2.Create a Scanner object to read input from the user.

3.Create an empty LinkedList of type String.

4.Read an integer n from the user representing the number of car names to be added.

5.Loop from i = 0 to i < n:

6.Read a string (car name) from the user.

7.Add the string to the LinkedList.

8.Retrieve the element at index 1 using the .get(1) method.

9.Display the retrieved element.

10.End.



## PROGRAM:
 ```
/*
Program to implement a LINKEDHASH SET
Developed by: Dinesh M
RegisterNumber: 212222040039


import java.util.*;

public class Main {
  public static void main(String[] args) {
   Scanner sc=new Scanner(System.in);
    LinkedList<String> cars = new LinkedList<String>();
    int n=sc.nextInt();
    for(int i=0;i<n;i++)
    {
    cars.add(sc.next());
    }
    
    String str = cars.get(1);
    System.out.print("Element at index 1: " + str);
  }
}

*/
```








## OUTPUT:

![Screenshot 2025-05-24 163432](https://github.com/user-attachments/assets/05989a02-3558-4ab8-8e75-076a65d1274b)


## RESULT:
The program successfully read n car names from the user, stored them in a LinkedList, and displayed the element at index 1.


