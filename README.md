# Lab: 7.0.4

**Objective:**

- Understand the concept and importance of methods with multiple parameters in Java development.
- Learn how to implement methods with multiple parameters using Java syntax.
- Explore practical applications of methods with multiple parameters in real-world Java projects.
- Identify common pitfalls and best practices when working with methods that have multiple parameters.
- Gain hands-on experience with a complete Java example that demonstrates methods with multiple parameters.

**Prerequisites:**

- Solid understanding of Java programming basics.
- Familiarity with method declaration and invocation in Java.
- Basic knowledge of control structures and data types in Java.

**What You'll Achieve:**

- Develop a solid understanding of methods with multiple parameters in Java.
- Implement practical examples that can be applied in real-world scenarios.
- Enhance your skills in method design and parameter handling.

**Assignment Details**

Create a Java program that simulates a basic grade calculator system. Implement the following methods:

1. `addSubject(String[] subjects, int[] credits, char[] grades, int index, String subject, int credit, char grade)`: Adds a new subject to the arrays.
2. `calculateGPA(int[] credits, char[] grades, int subjectCount)`: Calculates and returns the GPA.
3. `printSubjectDetails(String[] subjects, int[] credits, char[] grades, int subjectCount)`: Prints details of all subjects.
4. `getTotalCredits(int[] credits, int subjectCount)`: Calculates and returns the total credits.

In the main method, demonstrate the use of these methods by:

1. Creating arrays to store subject information (maximum 10 subjects)
2. Adding at least 3 subjects using the `addSubject` method 
3. Calculating and printing the GPA 
4. Printing all subject details 
5. Displaying the total credits

In the `main` method:

1. Prompt the user to enter a temperature value and its unit (C or F).
2. Convert the temperature to the other unit using the appropriate method.
3. Round both the original and converted temperatures to two decimal places.
4. Display the original temperature and its conversion.

**Example Output**

```
Added subject: Math (4 credits, grade A)
Added subject: History (3 credits, grade B)
Added subject: Science (4 credits, grade C)

GPA: 3.18

Subject Details:
Math (4 credits): A
History (3 credits): B
Science (4 credits): C

Total Credits: 11
```

**Starter Code**

The `GradeCalculator.java` file contains the following starter code:

```java
public class GradeCalculator {
    public static void main(String[] args) {
        String[] subjects = new String[10];
        int[] credits = new int[10];
        char[] grades = new char[10];
        int subjectCount = 0;

        // TODO: Add subjects, calculate GPA, print details, and show total credits
    }

    // TODO: Implement the required methods here
}

```

**Hints**

- Use arrays to store the information for each subject.
- When implementing `calculateGPA`, remember that A=4, B=3, C=2, D=1, F=0.
- Use a switch statement or if-else to convert letter grades to their numerical equivalents.
- Be careful not to exceed the array bounds when adding subjects.
- Consider using `String.format()` or `System.out.printf()` for formatting output.

**Submission Instructions**

1. Fork the repository
2. Clone your fork
3. Navigate into the repository
4. Implement the required methods in the `GradeCalculator.java` file
5. Test your implementation with various inputs
6. Git add, commit, and push to your fork
7. Submit a pull request
    - Set the title of the pull request to your first name and last name
    - In the comment, briefly explain your implementation approach and any challenges you faced

Remember, the goal is to learn and have fun! Don't hesitate to ask for help if you get stuck.