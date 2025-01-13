

# Basics of Java Programming

## Overview
This folder contains the essential Java programming exercises I have completed as part of my learning journey. These exercises focus on the basic syntax and concepts of Java, such as printing output, using comments, and understanding the structure of a Java program.

## Concepts Covered
The exercises in this folder are designed to introduce the following basic concepts:
- **Printing output** using `System.out.println()`.
- **Using comments** for documentation and code clarity.
- **Understanding Java program structure** including classes and methods.

## Folder Structure

```
Basics/
│
├── HelloWorld.java
├── CommentOutCode.java
├── GeeksForGeeks.java
└── README.md
```

### Files in the Folder:
1. **HelloWorld.java**: The classic "Hello World" program to print a simple message.
2. **CommentOutCode.java**: An exercise demonstrating how to comment out code to prevent it from executing.
3. **GeeksForGeeks.java**: A program where comments are used to change the output from "Hello World" to "GeeksForGeeks".

## Exercises Completed

### 1. **Hello World Program**

**Objective**: Print "Hello World" to the console.

```java
import java.util.*;
import java.lang.*;
import java.io.*;

class GFG {
    public static void main (String[] args) {
        System.out.println("Hello World");  // Prints Hello World
    }
}
```

**Explanation**: This is a simple Java program to demonstrate how to output text to the console using `System.out.println()`. This is often the first program when learning a new programming language.

### 2. **Using Comments in Code**

**Objective**: Comment out the line that prints the value of `b`.

```java
import java.util.*;
import java.lang.*;
import java.io.*;

class GFG {
    public static void main(String[] args) {
        int b = 10;
        // System.out.println(b);  // Commented out this line
        System.out.println("Value of b is commented out");
    }
}
```

**Explanation**: In this exercise, I learned how to use comments in Java to disable specific parts of the code. The `System.out.println(b)` line is commented out to prevent it from executing, while the program still outputs a message.

### 3. **Printing "GeeksForGeeks"**

**Objective**: Comment out the code that prints "Hello World" and print "GeeksForGeeks" instead.

```java
import java.util.*;

class GFG {
    public static void main(String args[]) {
        // Prints Hello World
        // System.out.println("Hello World");
        // Prints GeeksForGeeks
        System.out.println("GeeksForGeeks");
    }
}
```

**Explanation**: This example demonstrates how to use comments to control which parts of the code are executed. The line that prints "Hello World" is commented out, and instead, "GeeksForGeeks" is printed to the console.

## Conclusion
This folder includes the very basics of Java programming, including how to print output and how to comment code for clarity or to temporarily disable code. These foundational concepts are essential for writing clean and understandable code in Java.

