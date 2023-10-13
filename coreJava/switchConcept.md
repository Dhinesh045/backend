# Java Switch Statements #

Instead of writing many if..else statements, you can use the switch statement.
The switch statement selects one of many code blocks to be executed:

**Syntax**

switch(expression) {

case x:

break;

case y:

break;

default:

}


### This is how it works: ###

The switch expression is evaluated once.

The value of the expression is compared with the values of each case.

If there is a match, the associated block of code is executed.

The break and default keywords are optional, and will be described later in this chapter.

**Example**

int day = 4;

switch (day) {

case 1:

System.out.println("Monday");

break;

case 2:

System.out.println("Tuesday");

break;

case 3:

System.out.println("Wednesday");

break;

case 4:

System.out.println("Thursday");

break;

case 5:

System.out.println("Friday");

break;

}
// Outputs "Thursday" (day 4)

