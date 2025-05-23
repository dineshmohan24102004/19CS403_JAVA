# Ex.No:2(C)    SINGLE ARRAY

## AIM:
To write a Java program to calculate the sum of elements in an array.

## ALGORITHM :
1.Start the program.

2.Create a Scanner object to read input from the user.

3.Read the number of elements n in the array.

4.Declare an array arr of size n.

5.Use a loop to input n elements from the user into the array.

6.Initialize a variable sum to 0.

7.Traverse the array using a loop:

8.For each element, add it to sum.

9.Print the total sum.

10.End the program.







## PROGRAM:
 ```
/*
Program to implement a Single Array using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

 import java.util.*;
public class sum{
    public static void printSum(){
        int sum=0;
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        int[] arr=new int[n];
        for(int i=0;i<n;i++){
            arr[i]=sc.nextInt();
        }
        System.out.println("Sum of an array:");
        for(int i=0;i<n;i++){
            sum=sum+arr[i];
        }
        System.out.println(sum);
    }
    public static void main(String args[]){
        printSum();
    }
}
*/
```

## OUTPUT:

![Screenshot 2025-05-23 212146](https://github.com/user-attachments/assets/e16328aa-e053-4a36-9305-d4b811e8830a)


## RESULT:
The program was successfully compiled and executed. It accurately computes the sum of all elements entered into the array.


