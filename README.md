# fundamentals-java

Personal notes on Java basics - variables, data types, input/output, operators, if-else, loops, and arrays.

## 1. Variables
Variables are containers for storing data.

```java
int age = 17;
String name = "Budi";
double height = 165.5;
boolean passed = true;
```

2. Data Types

· int – integer numbers (10, 20)
· double – decimal numbers (3.14)
· String – text ("Andi")
· char – single character ('A')
· boolean – true or false

3. User Input

Using Scanner class:

```java
import java.util.Scanner;

Scanner input = new Scanner(System.in);
System.out.print("Enter your name: ");
String name = input.nextLine();
```

4. Output

```java
System.out.println("Hello World");
System.out.print("Hello");
```

5. Operators

Arithmetic operators: +, -, *, /, %

```java
int a = 10;
int b = 5;
int result = a + b; // 15
```

6. If-Else (Conditional Logic)

```java
int score = 80;

if (score >= 75) {
    System.out.println("Passed");
} else {
    System.out.println("Failed");
}
```

7. Loops

```java
for (int i = 1; i <= 5; i++) {
    System.out.println(i);
}
```

8. Arrays

```java
int[] numbers = {10, 20, 30};
System.out.println(numbers[0]); // 10
```

Prerequisites

· Java JDK installed
· Any code editor (IntelliJ IDEA, Eclipse, VS Code, or even Notepad)

How to Run

1. Save the code in a .java file
2. Compile: javac FileName.java
3. Run: java FileName

Author

Faris

