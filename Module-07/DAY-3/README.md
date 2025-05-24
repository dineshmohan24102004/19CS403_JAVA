# Ex.No:7(C)             THREAD IN JAVA
## AIM:
To write a Java program using multithreading to check whether a given number is a palindrome or not by implementing the Runnable interface.


## ALGORITHM :
1.Start the program.

2.Create a class Multi that implements the Runnable interface.

3.Inside the class:

4.Create a Scanner object to read input.

5.Define the run() method.

6.In the run() method:

7.Accept an integer number from the user.

8.Store the original number in a temporary variable.

9.Initialize reverse to 0.

10.Use a while loop to reverse the number:

11.Extract each digit using modulo operation.

12.Build the reverse number by multiplying the current reverse by 10 and adding the digit.

13.Reduce the number by dividing it by 10.

14.After the loop, compare the reversed number with the original.

15.If equal, print that it is a palindrome.

16.Else, print that it is not a palindrome.

17.In the main() method:

18.Create an object of the class Multi.

19.Create a thread using that object and start the thread.

20.End the program.





## PROGRAM:
 ```
/*
Program to implement a Thread concepts using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

   import java.util.*;
    public class Multi implements Runnable
    {  
        Scanner sc=new Scanner(System.in);
        
    public void run()
    {  
        int number=sc.nextInt();
        int remainder=0,reverse=0,temp;
        temp=number;
       while(number != 0)   
        {  
         remainder = number % 10;  
        reverse = reverse * 10 + remainder;  
        number = number/10;  
        }  
        if(temp==reverse)
        {
        System.out.println("The number " +temp+" is Palindrome");  
        }
        else
        {
              System.out.println("The number " +temp+" is not a Palindrome");  
        }
    }  
    public static void main(String args[]){  
    Multi m1=new Multi(); 
    Thread t1 =new Thread(m1); 
    t1.start();  
     }  
    }  
*/
```








## OUTPUT:
![Screenshot 2025-05-24 122358](https://github.com/user-attachments/assets/363bd0de-6bc9-411c-8098-01dcfc11a1ff)



## RESULT:
The program successfully creates a new thread to check if a user-inputted number is a palindrome using the Runnable interface.







