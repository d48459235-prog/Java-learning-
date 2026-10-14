









Java Day 2: Variables, Data Types, and User Input

1. What is a Variable?

A variable is a named memory location used to store data in a program.

Syntax:

dataType variableName = value;

Example:

int age = 18;
String name = "Divya";

System.out.println(age);
System.out.println(name);

Output:

18
Divya

Explanation:

- "int" is the data type.
- "age" is the variable name.
- "18" is the value stored in the variable.
- "String" is used to store text.
- "System.out.println()" displays the output.

2. Java Data Types

Data types specify the kind of value a variable can store.

Data Type| Description| Example
"int"| Stores whole numbers| "int age = 18;"
"double"| Stores decimal numbers| "double price = 99.5;"
"char"| Stores a single character| "char grade = 'A';"
"boolean"| Stores "true" or "false"| "boolean isStudent = true;"
"String"| Stores text| "String city = "Mysore";"

Important: Use single quotes for a "char" value and double quotes for a "String" value.

3. Example Program Using Data Types

class Main {
    public static void main(String[] args) {
        int age = 18;
        double percentage = 85.5;
        char grade = 'A';
        boolean isStudent = true;
        String city = "Mysore";

        System.out.println(age);
        System.out.println(percentage);
        System.out.println(grade);
        System.out.println(isStudent);
        System.out.println(city);
    }
}

Output:

18
85.5
A
true
Mysore

4. Taking User Input Using Scanner

Java provides the "Scanner" class to read input from the user.

Example Program:

import java.util.Scanner;

class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter your name: ");
        String name = sc.nextLine();

        System.out.print("Enter your age: ");
        int age = sc.nextInt();

        System.out.println("Name: " + name);
        System.out.println("Age: " + age);

        sc.close();
    }
}

Sample Output:

Enter your name: Divya
Enter your age: 18
Name: Divya
Age: 18

Explanation:

- "import java.util.Scanner;" imports the Scanner class.
- "Scanner sc = new Scanner(System.in);" creates a Scanner object to read input.
- "sc.nextLine()" reads a line of text.
- "sc.nextInt()" reads an integer.
- "System.out.println()" displays the result.
- "sc.close()" closes the Scanner.

5. Key Takeaways

1. Variables store values in a program.
2. Data types define what kind of values can be stored.
3. "int", "double", "char", "boolean", and "String" are commonly used types.
4. The Scanner class helps us accept user input.
5. Java is case-sensitive, so uppercase and lowercase letters matter.

6. Practice Questions

1. Which data type is suitable for the value "12.5"?
2. Identify the variable name in "String city = "Mysore";".
3. What is the output of the following program?

int a = 10;
int b = 20;
System.out.println(a + b);

Day 2 completed — Java Variables, Data Types, and User Input.



















