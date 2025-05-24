# Ex.No:12(E)  JAVA DEQUEUE

## AIM:
To write a Java program that stores integers in a Deque implemented by a LinkedList and displays all the elements of the Deque.
## ALGORITHM :

1.Start.

2.Create a Scanner object to read input from the user.

3.Create an empty Deque<Integer> implemented by a LinkedList<Integer>.

4.Read an integer size representing the number of elements to add.

5.Loop from i = 0 to i < size:

6.Read an integer from the user.

7.Add the integer to the Deque using .add().

8.Print the elements of the Deque.

9.End.

## PROGRAM:
 ```
/*
Program to implement a JAVA DEQUEUE
Developed by: Dinesh M
RegisterNumber: 212222040039

import java.util.*;

public class deQueueDemo {
	

	public static void main(String args[])
	{
	
		Deque<Integer> dq = new LinkedList<Integer>();
        
	    Scanner sc=new Scanner(System.in);
	    int size=sc.nextInt();
	    for(int i=0;i<size;i++){
	        dq.add(sc.nextInt());
	    }
	    System.out.println("Display the element of Dequeue:");
		System.out.println(dq);

		
	}
}
 
*/
```









## OUTPUT:

![Screenshot 2025-05-24 165739](https://github.com/user-attachments/assets/3a58f09c-d4e1-4972-b514-020a02a1e0f9)


## RESULT:
The program successfully stored integers entered by the user in a Deque and displayed all the elements in insertion order.


