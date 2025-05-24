# Ex.No:11(C)             JAVA LINKED HASHMAP
 ## AIM :

To write a Java program that demonstrates the use of LinkedHashMap by storing key-value pairs, displaying them in insertion order, checking the size of the map, and clearing all entries.



## ALGORITHM :

1.Start.

2.Create a Scanner object to read input from the user.

3.Create an empty LinkedHashMap<Integer, String>.

4.Read an integer size representing the number of key-value pairs to insert.

5.Loop from i = 0 to i < size:

6.Read an integer key.

7.Read a string value.

8.Insert the key-value pair into the map using .put().

9.Use an iterator over the keySet() to print each key and its corresponding value in insertion order.

10.Display the size of the map using .size().

11.Clear the map using .clear().

12.Display the size of the map again to confirm it is empty.

12.End.

## PROGRAM:
 ```
/*
Program to implement a JAVA LINKED HASH MAP using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  LinkedHashMap<Integer,String> map=new LinkedHashMap<Integer,String>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 
  
 Iterator<Integer> keySetIterator = map.keySet().iterator(); while(keySetIterator.hasNext()){ Integer key = keySetIterator.next(); System.out.println("key: " + key + " value: " + map.get(key)); }

System.out.println("Size of Map: " + map.size()); map.clear(); 
System.out.println("Size of Map: " + map.size()); 

 }  
}  
*/
```









## OUTPUT:
![Screenshot 2025-05-24 164222](https://github.com/user-attachments/assets/8523e2da-54f9-4e19-afa9-b5637147e148)



## RESULT:
The program successfully stored integer-string key-value pairs in a LinkedHashMap, displayed the elements in insertion order, showed the map size before and after clearing it.








