# Ex.No:12(A)         JAVA TREE MAP
## AIM:
To write a Java program that stores key-value pairs in a TreeMap, displays the original map, clears the map, and then displays the empty map.

## ALGORITHM :

1.Start.

2.Create a Scanner object to read input from the user.

3.Create an empty TreeMap<String, String>.

4.Read an integer size indicating the number of key-value pairs to insert.

5.Loop from i = 0 to i < size:

6.Read a string key.

7.Read a string value.

8.Insert the key-value pair into the TreeMap using .put().

9.Print the contents of the original TreeMap.

10.Clear all entries from the map using .clear().

11.Print the map again to show that it is empty.

12.End.



## PROGRAM:
 ```
/*
Program to implement a JAVA TREE MAP using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

import java.util.*;
import java.util.Map.Entry;  
public class Example6 {  
    public static void main(String args[]){  

   TreeMap<String,String> tree_map1 = new TreeMap<String,String>();      
  Scanner sc=new Scanner(System.in);
   int size=sc.nextInt();
   for(int i=0;i<size;i++)
   {
      String n1 = sc.next();
      String s1= sc.next();
       
   	  tree_map1.put(n1,s1);  
   }
    
  System.out.println("Orginal TreeMap content: "+tree_map1);
  tree_map1.clear();
  System.out.println("The New map: "+tree_map1);
 }
}

*/
```









## OUTPUT:
![Screenshot 2025-05-24 164919](https://github.com/user-attachments/assets/8cb729ad-954d-4821-bb44-486ab0229c77)



## RESULT:
The program successfully read key-value pairs, stored them in a TreeMap, displayed the original map in sorted order by keys, cleared the map, and then displayed the empty map.
