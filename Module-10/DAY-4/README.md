# Ex.No:10(D) JAVA HASHSET & LINKEDHASHSET

## AIM:
To write a Java program that reads n strings from the user, stores them in a HashSet, and then displays the elements using an iterator.**


## ALGORITHM :
1.Start.

2.Create a Scanner object to read input from the user.

3.Create an empty HashSet of type String.

4.Read an integer n from the user (number of elements to insert).

5.Loop from i = 0 to i < n:

6.Read a string input.

7.Add the string to the HashSet using .add() method.

8.Create an Iterator for the HashSet.

9.Use a while loop to iterate through the HashSet:

10.Print each element using the iterator.

11.End.



## PROGRAM:
 ```
/*
Program to implement a JAVA HASHSET & LINKEDHASHSET using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

import java.util.*;

public class HashSetDemo{

public static void main(String args[]){

HashSet <String> hs = new HashSet <String>();
Scanner sc=new Scanner(System.in);
int n=sc.nextInt();
for(int i=0;i<n;i++)
{
    
hs.add(sc.next());

}
 Iterator<String> i=hs.iterator();  
 while(i.hasNext())  
 {  
    System.out.println(i.next());  
 }  

}
}
*/
```









## OUTPUT:

![Screenshot 2025-05-24 163217](https://github.com/user-attachments/assets/77249866-a615-481f-8a26-bdcf6120746f)


## RESULT:
The program successfully accepted n strings from the user, stored them in a HashSet (automatically removing duplicates), and displayed the unique elements using an iterator.




