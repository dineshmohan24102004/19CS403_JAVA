# Ex.No:11(B)   JAVA MAP & HASHMAP AND HASHTABLE
## AIM :
To write a Java program that uses a HashMap to store key-value pairs of integers and doubles, display the map entries, and check for the presence of a specific key and value.

## ALGORITHM :

1.Start.

2.Create a Scanner object to read input from the user.

3.Create an empty HashMap<Integer, Double>.

4.Read an integer size representing the number of key-value pairs to insert.

5.Loop from i = 0 to i < size:

6.Read an integer key.

7.Read a double value.

8.Insert the key-value pair into the map using .put().

9.Use a for-each loop with Map.Entry to iterate through the map and print all key-value pairs.

10.Check if the map contains the key 3 using .containsKey(3) and display the result.

11.Check if the map contains the value 3.3 using .containsValue(3.3) and display the result.

12.End.




## PROGRAM:
 ```
/*
Program to implement a JAVA MAP & HASHMAP AND HASHTABLE using Java
Developed by: Dinesh M
RegisterNumber:   212222040039

import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  Map<Integer,Double> map=new HashMap<>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  Double b=sc.nextDouble();
  map.put(a,b);  
  } 
 
  for(Map.Entry m:map.entrySet()){  
   System.out.println(m.getKey()+" "+m.getValue());  
  }  
 
         
        System.out.println(map.containsKey(3));     
         
       
        System.out.println(map.containsValue(3.3)); 
 }  
}  
*/
```









## OUTPUT:



## RESULT:
The program successfully stored integer-double pairs in a HashMap, displayed all entries, and correctly checked for the existence of key 3 and value 3.3 using appropriate map methods.







