# Ex.No:10(C)             JAVA LIST INTERFACE
 ## AIM :

To write a Java program that reads a list of strings from the user into an ArrayList, inserts a new string at a specific position (index 1), and displays the updated list.




## ALGORITHM :
1.Start.

2.Create a Scanner object to take input from the user.

3.Create an empty ArrayList of type String.

4.Read an integer size from the user to determine how many strings to input.

5.Run a loop from i = 0 to i < size:

6.Read a string and add it to the ArrayList.

7.Read one more string input from the user.

8.Insert this string at index 1 in the ArrayList using add(1, element).

9.Display the final contents of the ArrayList.

10.End.

## PROGRAM:
 ```
/*
Program to implement a JAVA LIST INTERFACE using Java
Developed by: Dinesh M
RegisterNumber:  212222040039

import java.util.*;


public class GFG {

	public static void main(String args[])
	{
		Scanner sc=new Scanner(System.in);
		List<String> al = new ArrayList<>();
        int size=sc.nextInt();
        for(int i=0;i<size;i++)
        {
				al.add(sc.next());
        }
        al.add(1,sc.next());
		
		System.out.println(al);
	}
}

*/
```









## OUTPUT:
![Screenshot 2025-05-24 163010](https://github.com/user-attachments/assets/b3a11d75-08b4-43d0-88a1-d2f806a8d7b3)



## RESULT:
The program successfully accepted a list of strings from the user, inserted a new string at position 1, and printed the updated ArrayList.










