# Inheritance

## AIM:
To Write the java program Using Inheritance one class can acquire the properties of other classes.

 ## ALGORITHM:
 
 ### Step 1:
 Create the class and declare the main method so that the JVM will identify the main program to run.
 
 ### Step 2:
 Create another class and use the keyword EXTENDS to use the concept of INHERITANCE.
 
 ### Step 3:
 Print a statement to check whether the inner class is accessable or not.
 
 ### Step 4:
 If the extended class's statement is executed then,this program follows the concept of inheritance.
 
 ### Step 5:
 The program will be executed after the compilation and results are printed.
 
 ## PROGRAM:
 ```java
 package q1;

public class Main {
    public static void main(String[] args) {
        Bird c=new Bird();
        c.fly();
        c.walk();
        c.sing();
    }
}
//CLASS FILE: BIRD
public class Bird extends Animal{
    public void fly(){
        System.out.println("I m flying");
    }
    public void sing(){
        System.out.println(" "+"I m singing");
    }
}
//CLASS FILE: ANIMAL
public class Animal {
    public void walk(){
        System.out.println("I m walking");
    }
}
 ```
 
 ## OUTPUT:
 ![image](https://github.com/Aashima02/Inheritance/assets/93427086/f7b14ce7-a4c9-44be-8fb3-431662cf97c8)

 
 ## RESULT:
 Thus a java program is created using inheritance to accquire properties of other classes.
 
 
