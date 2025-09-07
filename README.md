# Lab 05

In this lab you will practice writing Java code to **input user data**.

Same as the previous labs, you need to set up your workspace (class and main() method).

## Let's get started!

First, let's look at the name of our .java file in the `src/` directory and name our class accordingly and remember to make it `public`. Next, **create your main() method inside your class**.

Now let the fun begin!

### Getting user input

To get user input in Java you must first import the **Scanner** class from the `java.util` package. Importing packages in Java must be done at the start of your code.

```java
import java.util.Scanner;

// Your code should start here.
```

Next, you must create a Scanner object inside of your main() method. This object will be used to get all of your user input regardless of their data type.

Creating an object in Java is done a bit differently than in C++. In Java, all objects are declared dynamically.

```java
		// Inside main() method.
		Scanner scanner = new Scanner(System.in);
```

But how do we user the scanner object to get user input?

Scanner has many built-in methods read user input depending on the type of data we're expecting (ex: String, int, double, etc.).

| **Method** | **Description** |
| ---- | ---- |
| nextBoolean() | Reads a <code style="color : darkorange">boolean</code> value from the user |
| nextByte() | Reads a <code style="color : darkorange">byte</code> value from the user |
| nextDouble() | Reads a <code style="color : darkorange">double</code> value from the user |
| nextFloat() | Reads a <code style="color : darkorange">float</code> value from the user |
| nextInt() | Reads an <code style="color : darkorange">int</code> value from the user |
| nextLine() | Reads a <code style="color : darkorange">String</code> value from the user |
| nextShort() | Reads a <code style="color : darkorange">short</code> value from the user |

The code snippet below shows how to input a float from the user.

```java
		// Inside main() method.
		float num = scanner.nextFloat();
```

For more information on getting user input in Java, visit: https://www.w3schools.com/java/java_user_input.asp

## Your program

### User Input - Medical Form

For this assignment you will practice getting user input in Java. 

Declare a `Scanner` object to be able to get information from the user.

Assume you are hired by the hospital Texas General and they've tasked you to create a program to collect user information to save paper.

1. Get and store the user's name. (Store as text)
2. Get and store the user's age. (Store as a whole number)
3. Get and store the user's weight. (Store it as a real number)
4. Get and store if the user is a smoker. (Store it as either true or false)
5. Output all of the information back to the user.

<br>

**Grading Criteria:**
| Criteria | Points |
|---|---|
| Used the correct input method to get the user’s name (as text), age (as a whole number), weight (as a real number), and smoker status (either true or false). | 60 |
| Used a clear prompt message to get the user’s input | 10 |
| File and class are named Input | 20 |
| Class is public | 10 |

[How to Submit Assignments to GitHub](https://joselitoguardado.dev/3326/How_to_Submit_Assignments_to_GitHub.pdf)
