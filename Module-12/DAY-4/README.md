# Ex.No:12(D) JAVA QUEUE
## AIM:
To write a Java program that stores integers in a PriorityQueue, displays the queue, converts it to an array, and prints the elements of the array.


## ALGORITHM :
1.Start.

2.Create a Scanner object to read input from the user.

3.Create an empty PriorityQueue<Integer>.

4.Read an integer size representing the number of elements to add.

5.Loop from i = 0 to i < size:

6.Read an integer from the user.

7.Add the integer to the PriorityQueue using .add().

8.Print the contents of the PriorityQueue.

9.Convert the PriorityQueue to an array using .toArray().

10.Iterate over the array and print each element.

11.End.





## PROGRAM:
 ```
/*
Program to implement a JAVA QUEUE using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

import java.util.*;

public class PriorityQueueDemo {
	

	public static void main(String args[])
	{
	
		PriorityQueue<Integer> pQueue = new PriorityQueue<Integer>();
        
	    Scanner sc=new Scanner(System.in);
	    int size=sc.nextInt();
	    for(int i=0;i<size;i++){
	        pQueue.add(sc.nextInt());
	    }
	    System.out.println("The PriorityQueue: " + pQueue);
  
       
        Object[] arr = pQueue.toArray();
  
        System.out.println("The array is:");
        for (int j = 0; j < arr.length; j++)
            System.out.println(arr[j]);

		
	}
}

*/
```









## OUTPUT:
![Screenshot 2025-05-24 165624](https://github.com/user-attachments/assets/109486bc-61f6-411a-a413-44a864858bf5)



## RESULT:
The program successfully stored integers in a PriorityQueue, displayed its elements, converted the queue to an array, and printed the elements of the array.


