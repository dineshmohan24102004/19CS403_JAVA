# Ex.No:2(A)  STATIC METHOD

## AIM:
To write a Java program to reverse a given integer number.

## ALGORITHM :
1.Start the program.

2.Create a Scanner object to read input from the user.

3.Declare three integer variables: num, rem, and rev (initialized to 0).

4.Read the number to be reversed and store it in num.

5.Repeat the following steps while num is not 0:

6.Find the remainder rem = num % 10.

7.Update the reverse number: rev = rev * 10 + rem.

8.Reduce num by removing the last digit: num = num / 10.

9.Print the reversed number rev.

10.End the program.




## PROGRAM:
 ```
/*
Program to implement a Static method using Java
Developed by: Dinesh M
RegisterNumber: 212222040039

import java.util.*;
public class Main{
  public static void main(String[] args)
  
  {
    int num,rem,rev=0;
    Scanner input=new Scanner(System.in);
    num=input.nextInt();
    while(num!=0)
    {
      rem=num%10;
      rev=rev*10+rem;
      num=num/10;
    }
    System.out.print("Reversed number: "+rev);
  }
}
*/
```


## OUTPUT:
![Screenshot 2025-05-23 210334](https://github.com/user-attachments/assets/1a4475db-4613-4033-894b-4a00c2ec07ef)



## RESULT:
The program was successfully compiled and executed. It correctly reverses the given integer number.



