# Ex.No:11(D) RELATED TO MAP CONCEPTS

## AIM:
To write a Java program that stores key-value pairs in a HashMap and displays the entries sorted in descending order of keys using Java Stream API.

## ALGORITHM :

1.Start.

2.Create a Scanner object to read input from the user.

3.Create an empty HashMap<Integer, String>.

4.Read an integer size representing the number of key-value pairs.

5.Loop from i = 0 to i < size:

6.Read an integer key.

7.Read a string value.

8.Insert the key-value pair into the map using .put().

9.Use .entrySet().stream() to create a stream of map entries.

10.Sort the stream in reverse order of keys using .sorted(Map.Entry.comparingByKey(Comparator.reverseOrder())).

11.Use .forEach(System.out::println) to display each key-value pair.

12.End.




## PROGRAM:
 ```
/*
Program to implement a RELATED TO MAP CONCEPTS using Java
Developed by: Dinesh M
RegisterNumber: 212222040039


import java.util.*;  
public class MapExample3{  
 public static void main(String args[]){  
Map<Integer,String> map=new HashMap<Integer,String>();          
      Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  }   

      map.entrySet()  
       
      .stream()  
   
      .sorted(Map.Entry.comparingByKey(Comparator.reverseOrder())) 

      .forEach(System.out::println);  
 }  
}  
*/
```









## OUTPUT:

![Screenshot 2025-05-24 164341](https://github.com/user-attachments/assets/ccf3120b-2dee-496c-8b5f-2f9c441ba6e6)


## RESULT:
The program successfully read key-value pairs, stored them in a HashMap, and displayed them in descending order of keys using the Java Stream API.


