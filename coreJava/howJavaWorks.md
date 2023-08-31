Java Works
   Writing Source code:
   Developers with java source code using a text editor or an integrated Development envirionment(IDE).
   Java code written in a plain text and it's organised into classes,each containing methods and fields.

   Compilation:
   When the source code is ready, it needs to be compiled. Java source code is compiled into bytecode, which is a platform-independent intermediate representation. The Java compiler (javac) takes the source code and generates bytecode files with a .class extension.

   Bytecode:
   Bytecode is not machine code but rather a set of instructions that the Java Virtual Machine (JVM) can understand. This bytecode is designed to be platform-independent, allowing it to run on any system that has a compatible JVM.

   Java Virtual Machine (JVM):
   The JVM is an integral part of how Java works. It is responsible for interpreting and executing the bytecode. When you run a Java program, the JVM loads the bytecode files, performs Just-In-Time (JIT) compilation to native machine code (on modern JVMs), and executes the program.

   Class Loading:
   When a Java program is executed, the JVM loads classes as they are needed. The class loader subsystem is responsible for finding and loading classes from the classpath or other locations.

   Bytecode Verification:
   Before executing the bytecode, the JVM performs bytecode verification. This ensures that the bytecode adheres to certain safety and security rules, helping to prevent malicious or incorrect code from causing harm.

   Just-In-Time (JIT) Compilation:
   As the program runs, the JVM's JIT compiler analyzes the bytecode and translates it into native machine code for the host system's architecture. This step improves execution speed since native code can be executed more efficiently than interpreted bytecode.

   Execution:
   Once the bytecode is loaded, verified, and possibly JIT-compiled, the JVM executes the program. The program's methods are invoked, objects are created, and the code's logic is carried out.

   Memory Management:
   Java employs automatic memory management through garbage collection. The JVM monitors objects' usage and automatically reclaims memory from objects that are no longer referenced, preventing memory leaks.

   Exception Handling:
   Java has a robust exception handling mechanism. If an exception occurs during runtime, the JVM captures and handles it according to the exception handling code provided by the programmer.

   Termination:
   The program continues executing until it reaches the end of its main method or encounters an explicit exit statement. At this point, the program terminates, and the resources it acquired are released.

   Debugging and Profiling:
   During development, developers can use debugging tools and profilers to diagnose issues in their code and analyze its performance. These tools help in identifying and fixing bugs and optimizing code.

\\Hello World Program\\

  public class hello {

	public static void main(String[] args) {
		System.out.print("Hello World");

	}

  }