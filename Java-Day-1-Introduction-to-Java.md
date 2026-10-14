Java Day 1: Introduction to Java and Hello World Program

1. What is Java?

Java is a high-level, object-oriented programming language. It is widely used to develop web applications, mobile applications, desktop software, and enterprise applications.

Java was developed by James Gosling and his team at Sun Microsystems.

Features of Java

- Simple: Java has a clear and structured syntax.
- Object-Oriented: Java supports classes and objects.
- Platform Independent: Java programs can run on different operating systems using the Java Virtual Machine (JVM).
- Secure: Java provides features that help build secure applications.
- Robust: Java supports exception handling and memory management.
- Portable: Java bytecode can run on systems with a compatible JVM.

2. What is a Java Program?

A Java program is a set of instructions written in the Java programming language to perform a specific task.

3. First Java Program: Hello World

class Main {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}

Output

Hello, World!

4. Explanation of the Program

"class Main"

- "class" is a keyword used to define a class.
- "Main" is the name of the class.

"public static void main(String[] args)"

This is the main method of the Java program. Program execution starts from this method.

- "public": Allows the method to be accessible from outside the class.
- "static": Allows the method to be called without creating an object of the class.
- "void": Means the method does not return a value.
- "main": The method name recognized as the program entry point.
- "String[] args": Receives command-line arguments.

"System.out.println("Hello, World!");"

- "System": A built-in Java class.
- "out": Represents the standard output stream.
- "println()": Prints the text and moves to a new line.
- ""Hello, World!"": The text displayed on the screen.
- ";": Marks the end of the statement.

Curly Braces "{ }"

Curly braces define the beginning and ending of a class or a method body.

5. How to Run a Java Program

1. Write the Java code in a text editor or IDE.

2. Save the file as "Main.java".

3. Compile the program using:
   
   javac Main.java

4. Run the compiled program using:
   
   java Main

5. The output will be:
   
   Hello, World!

Note: The file name "Main.java" matches the class name "Main". This example uses a standard class-based Java program.

6. Practice Programs

Program 1: Print Your Name

class Main {
    public static void main(String[] args) {
        System.out.println("My name is Divya");
    }
}

Program 2: Print Three Lines

class Main {
    public static void main(String[] args) {
        System.out.println("I am learning Java.");
        System.out.println("This is Day 1.");
        System.out.println("My goal is to become a software engineer.");
    }
}

7. Key Takeaways

1. Java is an object-oriented programming language.
2. The JVM helps Java bytecode run on different platforms.
3. The "main()" method is the entry point of a standard Java application.
4. "System.out.println()" displays output.
5. Java statements usually end with a semicolon.
6. Java is case-sensitive.

Day 1 Completed

Topics covered: Introduction to Java, Java features, program structure, Hello World, and printing output.






































