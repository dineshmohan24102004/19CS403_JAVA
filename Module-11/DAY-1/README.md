# Ex.No:11(A)         JAVA TREESET
## AIM:
To write a Java program that reads a set of strings from the user, stores them in a TreeSet, and displays the elements in sorted (ascending) order.


## ALGORITHM :
1.Start.

2.Create a Scanner object to read input from the user.

3.Read an integer n representing the number of strings to input.

4.Create an empty TreeSet of type String.

5.Loop from i = 0 to i < n:

6.Read a string from the user.

7.Add the string to the TreeSet using the .add() method.

8.Print the contents of the TreeSet.

9.End.

## PROGRAM:
 ```
/*
Program to implement a JAVA TREESET using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

 import java.util.*;

public class Main{
    
    public static void main(String [] args)
    {
        Scanner sc = new Scanner(System.in);
        
        int n = sc.nextInt();
        
        TreeSet < String> l = new TreeSet<>();
        
        for(int  i=0;i<n;i++)
        {
            l.add(sc.next());
        }
        
        System.out.println("Tree set:\n"+l);
    }
}
*/
```







## OUTPUT:
![Screenshot 2025-05-24 163628](https://github.com/user-attachments/assets/62def825-3a8a-43be-b2bf-3fd27a3631b9)



## RESULT:
The program successfully accepted n strings from the user, stored them in a TreeSet, and printed the elements in sorted order without duplicates.

