# Ex.No:12(B)   COMPARABLE & COMPARATOR INTERFACE
## AIM :
To write a Java program that compares two integer values using the compareTo() method of the Integer class and displays the comparison results.


## ALGORITHM :
1.Start.

2.Create a Scanner object to read input from the user.

3.Read two integers from the user and convert them to Integer objects (valA and valB).

4.Use valA.compareTo(valB) to compare valA with valB and store the result in comparisonA.

5.Use valB.compareTo(valA) to compare valB with valA and store the result in comparisonB.

6.Print the values of comparisonA and comparisonB.

7.If the result is 0, both values are equal.

8.If the result is positive, the first value is greater.

9.If the result is negative, the first value is smaller.

10.End.


## PROGRAM:
 ```
/*
Program to implement a COMPARABLE & COMPARATOR INTERFACE using Java
Developed by: Dinesh M
RegisterNumber:  212222040039

import java.util.*;
public class ComparableExample {

    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        
        Integer valA = Integer.valueOf(sc.nextInt());
        Integer valB = Integer.valueOf(sc.nextInt());

        int comparisonA = valA.compareTo(valB);
        int comparisonB = valB.compareTo(valA);

        System.out.println(comparisonA);
        System.out.println(comparisonB);
    }
}
*/
```









## OUTPUT:



## RESULT:
The program compares two integer values and outputs:A positive number if the first value is greater than the second,Zero if both values are equal,A negative number if the first value is less than the second.




