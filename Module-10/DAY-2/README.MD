# Ex.No:10(B) JAVA LINKED LIST
## AIM :
To write a Java program that accepts a list of strings from the user, stores them in a LinkedList, and checks whether the word "Programming" is present in the list.



## ALGORITHM :
1.Start.

2.Create a Scanner object to read input from the user.

3.Create an empty LinkedList to store strings.

4.Read an integer n from the user (number of elements to insert).

5.Loop from i = 0 to i < n:

6.Read a string input.

7.Add the string to the LinkedList.

8.Display the contents of the LinkedList.

9.Check if the LinkedList contains the word "Programming" using the .contains() method.

10.Display the result of the check.

11.End.



## PROGRAM:
 ```
/*
Program to implement a JAVA LINKED LIST using Java
Developed by: Dinesh M
RegisterNumber:  212222040039

import java.util.*;

public class Main {
  public static void main(String[] args) {
   Scanner sc=new Scanner(System.in);
    LinkedList<String> llist1 = new LinkedList<String>();
    int n=sc.nextInt();
    for(int i=0;i<n;i++)
    {
    llist1.add(sc.next());
    }
    
    System.out.println("Linked List 1:" + llist1);
    System.out.println("Linked List 1 contains 'Programming' :" + llist1.contains("Programming"));
  
  }
}

*/
```









## OUTPUT:



## RESULT:
The program successfully read n strings from the user, displayed the linked list, and confirmed whether the word "Programming" was present in the list.





