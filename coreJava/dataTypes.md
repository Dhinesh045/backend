Data Types in Java
   Data types specify the different sizes and values that can be stored in the variable. 
   There are two types of data types in Java:

Primitive data types - includes byte, short, int, long, float, double, boolean and char

Non-primitive data types - such as String, Arrays and Classes (you will learn more about these in a later chapter)
Example

int myNum = 5;               // Integer (whole number)

float myFloatNum = 5.99f;    // Floating point number

char myLetter = 'D';         // Character

boolean myBool = true;       // Boolean

String myText = "Hello";     // String

\\Numbers\\

Primitive number types are divided into two groups:

Integer types stores whole numbers, positive or negative (such as 123 or -456), without decimals. Valid types are byte, short, int and long. Which type you should use, depends on the numeric value.

Floating point types represents numbers with a fractional part, containing one or more decimals.
There are two types: float and double.

\\Integer Types\\

Byte

The byte data type can store whole numbers from -128 to 127. This can be used instead of int or other integer types to save memory when you are certain that the value will be within -128 and 127:

Example

byte myNum = 100;

System.out.println(myNum);

Short

The short data type can store whole numbers from -32768 to 32767:

Example

short myNum = 5000;

System.out.println(myNum);

Int
The int data type can store whole numbers from -2147483648 to 2147483647. In general, and in our tutorial, the int data type is the preferred data type when we create variables with a numeric value.

Example

int myNum = 100000;

System.out.println(myNum);

Long

The long data type can store whole numbers from -9223372036854775808 to 9223372036854775807. This is used when int is not large enough to store the value. Note that you should end the value with an "L":

Example

long myNum = 15000000000L;

System.out.println(myNum);

Floating Point Types

You should use a floating point type whenever you need a number with a decimal, such as 9.99 or 3.14515.

The float and double data types can store fractional numbers. Note that you should end the value with an "f" for floats and "d" for doubles:

Float Example

float myNum = 5.75f;

System.out.println(myNum);

Double Example

double myNum = 19.99d;

System.out.println(myNum);

!* Use float or double?

The precision of a floating point value indicates how many digits the value can have after the decimal point. The precision of float is only six or seven decimal digits, while double variables have a precision of about 15 digits. 
Therefore it is safer to use double for most calculations.

Example

float f1 = 35e3f;

double d1 = 12E4d;

System.out.println(f1);

System.out.println(d1);

Boolean Types

Very often in programming, you will need a data type that can only have one of two values, like:


TRUE / FALSE

For this, Java has a boolean data type, which can only take the values true or false:

Example

boolean isJavaFun = true;

boolean isFishTasty = false;

System.out.println(isJavaFun);     // Outputs true

System.out.println(isFishTasty);   // Outputs false

Characters
The char data type is used to store a single character. The character must be surrounded by single quotes, like 'A' or 'c':

Example
char myGrade = 'B';
System.out.println(myGrade);

Non-Primitive Data Types

Non-primitive data types are called reference types because they refer to objects.

The main difference between primitive and non-primitive data types are:

Primitive types are predefined (already defined) in Java. Non-primitive types are created by the programmer and is not defined by Java (except for String).
Non-primitive types can be used to call methods to perform certain operations, while primitive types cannot.

A primitive type has always a value, while non-primitive types can be null.

A primitive type starts with a lowercase letter, while non-primitive types starts with an uppercase letter.

Examples of non-primitive types are Strings, Arrays, Classes, Interface, etc. You will learn more about these in a later chapter.
