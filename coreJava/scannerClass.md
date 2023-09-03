# Java Scanner

 **Scanner class in Java is found in the java.util package. Java provides various ways to read input from the keyboard, the java.util.Scanner class is one of them.**

**The Java Scanner class breaks the input into tokens using a delimiter which is whitespace by default. It provides many methods to read and parse various primitive values.**

**The Java Scanner class is widely used to parse text for strings and primitive types using a regular expression. It is the simplest way to get input in Java. By the help of Scanner in Java, we can get input from the user in primitive types such as int, long, double, byte, float, short, etc.**

**The Java Scanner class extends Object class and implements Iterator and Closeable interfaces.**

# How to get Java Scanner

To get the instance of Java Scanner which reads input from the user, we need to pass the input stream (System.in) in the constructor of Scanner class. 

For Example:

**Scanner in = new Scanner(System.in);**  

To get the instance of Java Scanner which parses the strings, we need to pass the strings in the constructor of Scanner class. 

For Example:

**Scanner in = new Scanner("Hello Javatpoint");** 
 
Example 

import java.util.*;  
public class ScannerExample {  
public static void main(String args[]){  
Scanner in = new Scanner(System.in);  
System.out.print("Enter your name: ");  
String name = in.nextLine();  
System.out.println("Name is: " + name);             
in.close();             
}  
}  

**Output:**

Enter your name: Dhinesh

Name is: Dhinesh
