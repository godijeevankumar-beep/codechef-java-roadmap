# Code Blocks with Curly Braces in Java

## 📖 Overview

Code blocks in Java are enclosed within curly braces `{}`. They are used to group statements together and define the scope of classes, methods, loops, and conditional statements. Proper use of code blocks makes programs organized, readable, and easier to maintain.

---

## 💻 Source Code

```java
class Codechef {
    public static void main(String[] args) {

        // Execute the first block
        {
            System.out.println("Executing Block 1");
        }

        // Execute the second block
        {
            System.out.println("Executing Block 2");
        }
    }
}
```

---

## 🖥️ Output

```
Executing Block 1
Executing Block 2
```

---

## 📝 Explanation

### What is a Code Block?

A code block is a group of statements enclosed within curly braces `{}`. It allows multiple statements to be executed together.

### Class Block

```java
class Codechef {

}
```

Defines the body of the Java class.

### Method Block

```java
public static void main(String[] args) {

}
```

Defines the `main()` method where the program starts execution.

### Nested Code Blocks

```java
{
    System.out.println("Executing Block 1");
}

{
    System.out.println("Executing Block 2");
}
```

These are two separate blocks inside the `main()` method. They execute one after another.

---

## 📚 Key Points

- Curly braces `{}` define code blocks.
- Every Java class uses a code block.
- Every method uses a code block.
- Code blocks help organize statements.
- Nested blocks improve logical grouping.

---

## 🎯 Practice Exercise

Create a Java program with **three** separate code blocks and print:

```
Executing Block A
Executing Block B
Executing Block C
```

---

⭐ **Source:** CodeChef Java Roadmap
