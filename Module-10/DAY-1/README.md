# Ex.No:10(A)         JAVA COLLECTION FRAMEWORK –ARRAY LIST
## AIM:
To write a Java program that reads 5 integer inputs from the user, stores them in an ArrayList, and displays the size of the ArrayList.

## ALGORITHM:
1.Start.

2.Create an empty ArrayList to store integers.

3.Create a Scanner object to take input from the user.

4.Loop from 1 to 5:

5.Inside the loop, read an integer input from the user.

6.Add the input to the ArrayList.

7.After the loop ends, print the size of the ArrayList.

8.End.

## PROGRAM:
 ```
/*
Program to implement a ARRAY LIST using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

import java.util.*;
public class Main
{
	public static void main(String[] args) {
		ArrayList<Integer> al=new ArrayList<Integer>();
        Scanner sc=new Scanner(System.in);
        for(int i=1;i<=5;i++)
        {
        al.add(sc.nextInt());
        }
     
        System.out.println(al.size());
	}
}

*/
```









## OUTPUT:
![Screenshot 2025-05-24 162351](https://github.com/user-attachments/assets/1e3a17d3-3aaf-4854-b0ce-4e0542857a9c)



## RESULT:
The program successfully accepted 5 integer inputs from the user, stored them in an ArrayList, and printed the size of the ArrayList as 5.

