# Ternary Operator in Java

## 📖 Overview
This Java program demonstrates the use of the **Ternary Operator (`? :`)**. The ternary operator is a shorthand way of writing an `if-else` statement. It evaluates a condition and returns one of two values based on whether the condition is `true` or `false`.

## 🚀 Features
- Demonstrates the use of the ternary operator.
- Compares two integer values.
- Assigns the larger value to another variable.
- Simple and beginner-friendly Java example.

## 🛠️ Technologies Used
- Java
- JDK 8 or later

## 📂 Project Structure

```text
TernaryOperator/
│── TernaryOperator.java
│── README.md
```

## 💻 Code

```java
public class TernaryOperator {

    public static void main(String args[]) {

        int x = 10, y = 12;
        int z;

        z = (x > y) ? x : y;

        System.out.println("Z = " + z);
    }
}
```

## ▶️ How to Run

1. Save the file as `TernaryOperator.java`.
2. Open a terminal in the project directory.
3. Compile the program:

```bash
javac TernaryOperator.java
```

4. Run the program:

```bash
java TernaryOperator
```

## 📌 Sample Output

```text
Z = 12
```

## 📚 Explanation

The ternary operator has the following syntax:

```java
condition ? expression1 : expression2;
```

- If the **condition is `true`**, `expression1` is executed.
- If the **condition is `false`**, `expression2` is executed.

In this program:

```java
z = (x > y) ? x : y;
```

- Since `10 > 12` is **false**, the value of `y` (12) is assigned to `z`.

## 🎯 Learning Outcome

This project helps beginners understand:
- How the ternary operator works in Java.
- How to replace simple `if-else` statements with a concise expression.
- How conditional expressions can simplify code.

## 📄 License

This project is open source and available under the MIT License.
