# Ex.No:6(A)  INNER CLASS
## AIM:
To create a Java program that uses an inner class ValidateCredentials within the outer class Login to access and display the private member variables userName and password.

## ALGORITHM :
1.Start.

2.Define a class Login with private string variables userName and password.

3.Initialize these variables using a constructor in Login.

4.Create an inner class ValidateCredentials inside the Login class.

5.Define a method validate() in ValidateCredentials that prints the userName and password of the outer class.

6.In the main method, create an instance of the Login class with sample username and password.

7.Using the Login instance, create an instance of the inner class ValidateCredentials.

8.Call the validate() method to display the username and password.

9.End.






## PROGRAM:
 ```
/*
Program to implement a Inner Class using Java
Developed by: Dinesh M
RegisterNumber:  212222040039

public class Login {

    private String userName;
    private String password;
    public Login(String userName, String password) {
        this.userName = userName;
        this.password = password;
    }
    public class ValidateCredentials {
        public void validate() {
            System.out.println(userName+" "+password);
        }
    }
    public static void main(String[] args) {
        Login login = new Login("EMP123", "John 24800.0");
        Login.ValidateCredentials validator = login.new ValidateCredentials();
        validator.validate();
    }
}
*/
```









## OUTPUT:
![Screenshot 2025-05-23 231447](https://github.com/user-attachments/assets/5baf1bdf-fe93-4f24-b61c-a9807dfe6fff)



## RESULT:
The program successfully demonstrates the use of an inner class to access and display private members of its outer class, printing the username and password passed during object creation.

