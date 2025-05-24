# Ex.No:12(C)             JAVA STACK & VECTOR
 ## AIM :

To write a Java program that stores strings in a Vector, displays the entire vector, and prints the first element of the vector.
## ALGORITHM :
1.Start.

2.Create a Scanner object to read input from the user.

3.Create an empty Vector<String>.

4.Read an integer size representing how many pairs of strings to add.

5.Loop from i = 0 to i < size:

6.Read two strings from the user.

7.Add both strings to the vector using .add().

8.Print the entire vector.

9.Retrieve and print the first element of the vector using .firstElement().

10.End.



## PROGRAM:
 ```
/*
Program to implement a JAVA STACK & VECTOR  using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

import java.util.*;

public class VectorDemo {
	public static void main(String args[])
	{

		
		Vector<String> vec_tor = new Vector<String>();
        Scanner sc=new Scanner(System.in);
        int size=sc.nextInt();
	    for(int i=0;i<size;i++)
	    {
		vec_tor.add(sc.next());
	    vec_tor.add(sc.next());
	    }
	

		System.out.println("The vector is: " + vec_tor);

	    System.out.println("The first element is: "
                           + vec_tor.firstElement());
	}
}

*/
```









## OUTPUT:
![Screenshot 2025-05-24 165419](https://github.com/user-attachments/assets/bd81dfde-2f6a-4dd7-a073-4f49431c86c6)



## RESULT:
The program successfully stored user-input strings in a Vector, displayed all elements, and printed the first element of the vector.








