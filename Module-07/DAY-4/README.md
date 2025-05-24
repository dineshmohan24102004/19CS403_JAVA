# Ex.No:7(D) SYNCHRONIZATION
## AIM:
To write a Java program to print even numbers up to a given limit using a synchronized static method, demonstrating the concept of thread synchronization.
 
## ALGORITHM :
1.Start the program.

2.Define a class named Table.

3.Inside the class, define a synchronized static method called Even(int n) to print even numbers from 2 to n.

4.In the Even(int n) method:

5.Initialize a variable i with 2.

6.Print a message indicating the start of the even number list.

7.Use a while loop to iterate while i <= n:

8.Print the current value of i.

9.Increment i by 2.

10.After the loop, print a newline for formatting.

11.Add a delay using Thread.sleep(400) to simulate thread activity and demonstrate synchronization.

12.Wrap the Thread.sleep() call in a try-catch block to handle any exceptions.

13.End the program.



## PROGRAM:
 ```
/*
Program to implement a Packages using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

  class Table
  {
    synchronized static void Even(int n)
    {
      
      int i=2;
     System.out.print("List of Even numbers for " +n+ " : ");
      while(i<=n)  
        {  
        //prints the even number  
        System.out.print(i +" ");   
        //increments the variable i by 2  
        i=i+2;  
        } 
        System.out.println();
         try
     {  
      Thread.sleep(400);  
     }
     catch(Exception e){System.out.println(e);}  
      
     
   }  
  }

*/
```






## OUTPUT:
![Screenshot 2025-05-24 122912](https://github.com/user-attachments/assets/44ba9937-8a21-46b0-89b2-7ebd03698ba9)



## RESULT:
The program successfully prints the list of even numbers up to the given limit using a synchronized static method. This demonstrates the concept of synchronization in Java for thread-safe operations.

