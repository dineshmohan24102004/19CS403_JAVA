# Ex.No:6(D) PACKAGES
## AIM:
  To implement and demonstrate hierarchical inheritance in Java using a parent class Media and two child classes Magazine and Channel, with constructors showcasing inheritance relationships.
 
## ALGORITHM :
1.Start.

2.Define a base class Media with a constructor that prints "Parent Class is Media".

3.Define a subclass Magazine that extends Media:

4.Use super() to call the constructor of Media.

5.Print "Magazine is the one of the Child of Media Class".

6.Define another subclass Channel that also extends Media:

7.Use super() to call the constructor of Media.

8.Print "Channel is the one of the Child of Media Class".

9.In the main method:

10.Create an object of Magazine to invoke its constructor and the inherited constructor.

11.Create an object of Channel to do the same.

12.End.


## PROGRAM:
 ```
/*
Program to implement a Packages using Java
Developed by: Dinesh M
RegisterNumber:212222040039
class Media{
    Media(){
        System.out.println("Parent Class is Media");
    }
}
class Magazine extends Media{
    Magazine(){
        super();
        System.out.println("Magazine is the one of the Child of Media Class");
    }
}
class Channel extends Media{
    Channel(){
        super();
        System.out.println("Channel is the one of the Child of Media Class");
    }
}
public class Main{
    public static void main(String argv[]){
        Magazine m = new Magazine();
        Channel c = new Channel();
    }
}
*/
```









## OUTPUT:
![Screenshot 2025-05-23 232621](https://github.com/user-attachments/assets/1b81b773-7c53-447d-b7e3-b01bfc58c2d5)



## RESULT:
The program successfully demonstrates hierarchical inheritance in Java where two different child classes inherit from a common parent class and invoke the parent constructor using super().

