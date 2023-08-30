Java Variables
        A variable is container which holds the value while the java program executed. A variable is assigned with a datatype.
        Variable is a name of memory location.there are three types of variables in java: local, instance and static.

        A variable is the name of a reserved area allocated in memory. In other words, it is a name of the memory location.
        It is a combination of "vary + able" which means its value can be changed.

   Types of Variables
      There are three types of variables in Java:

        local variable
        instance variable
        static variable

    \\Local Variable
        A variable declared inside the body of the method is called local variable. You can use this variable only within that method and the other methods in the class aren't even aware that the variable exists.
        A local variable cannot be defined with "static" keyword.

     \\Instance Variable
        A variable declared inside the class but outside the body of the method, is called an instance variable. It is not declared as static.
        It is called an instance variable because its value is instance-specific and is not shared among instances.

      \\Static variable
        A variable that is declared as static is called a static variable. It cannot be local. You can create a single copy of the static variable and share it among all the instances of the class.
        Memory allocation for static variables happens only once when the class is loaded in the memory.

       \* Codes*\

        class Variable
        {
               int a=10; /*INSTANCE VARIABLE*/
        	   static int c=30;
        	   public static void main(String args[])
        	   {
        	            int b=20;/*LOCAL VARIABLE*/
        				Variable v=new Variable();
        				System.out.println("Instance Variable="+v.a);
        				System.out.println("local Variable="+b);
        				System.out.println("Static Variable="+c);

        }
        	    }