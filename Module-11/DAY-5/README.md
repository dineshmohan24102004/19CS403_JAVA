# Ex.No:11(E)  JAVA HASHMAP

## AIM:
To write a Java program that stores key-value pairs in a HashMap, displays all entries, and retrieves the value associated with a specific key.
## ALGORITHM :

1.Start.

2.Create a Scanner object to read input from the user.

3.Create an empty HashMap<Integer, String>.

4.Read an integer size from the user indicating the number of key-value pairs to be inserted.

5.Loop from i = 0 to i < size:

6.Read an integer key.

7.Read a string value.

8.Insert the key-value pair into the map using .put(key, value).

9.Use a for-each loop with Map.Entry to iterate over the map entries.

10.Print each key and its corresponding value.

11.Retrieve the value associated with the key 100 using .get(100).

12.Print the retrieved value.

12.End.

## PROGRAM:
 ```
/*
Program to implement a HASHMAP
Developed by: Dinesh M
RegisterNumber: 212222040039


import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  HashMap<Integer,String> map=new HashMap<Integer,String>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 
  for(Map.Entry m:map.entrySet()){  
   System.out.println(m.getKey()+" "+m.getValue());  
  }
  Integer key = 100; String value = map.get(key);


  System.out.println("value: "+ value);


 }  
}  
*/
```









## OUTPUT:

![Screenshot 2025-05-24 164719](https://github.com/user-attachments/assets/9663ed35-9b40-4949-ad5d-c2bf41701d6f)


## RESULT:
The program successfully Accepted and stored key-value pairs in a HashMap.




