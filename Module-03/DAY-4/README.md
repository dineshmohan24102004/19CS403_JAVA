# Ex.No:3(D) STRING TOKENIZER IN JAVA

## AIM:
To write a Java program that reads a string input from the user, splits it into tokens using the delimiter #, and displays the total number of tokens.

## ALGORITHM :
1.Start.

2.Import the Scanner and StringTokenizer classes.

3.Create the class StringTokenizer3.

4.Define the main method.

5.Create a Scanner object to take input from the user.

6.Read a full line input as a string (str1).

7.Create a StringTokenizer object st to tokenize str1 using # as the delimiter.

8.Use countTokens() method of StringTokenizer to count the number of tokens.

9.Print the total number of tokens.

10.End.




## PROGRAM:
 ```
/*
Program to implement a String Tokenizer using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

import java.util.*;    
public class StringTokenizer3  
{    
 
 public static void main(String args[])  
 {    
   Scanner sc=new Scanner(System.in);
   String str1=sc.nextLine();
     
   StringTokenizer st = new StringTokenizer(str1,"#");    
        
         System.out.println("Total number of Tokens: "+st.countTokens());    
 }    
}  
*/
```








## OUTPUT:
![Screenshot 2025-05-23 223448](https://github.com/user-attachments/assets/22afd2ee-9e92-49e6-bb03-fcef3ea5194b)



## RESULT:
The program successfully reads a string with # delimiters from the user, counts the number of tokens separated by #, and prints the correct total number of tokens.
