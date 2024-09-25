# Lesson 4: Conditional Statements in Python

## Objectives:
- Learn how to use `if`, `elif`, and `else` statements to make decisions in Python programs.
- Understand the flow of decision-making processes using conditions.

## Materials:
- Python installed on the computer or access to an online Python environment like Repl.it or Jupyter Notebook.

## Lesson Plan:

1. **Introduction to Conditional Statements:**
   - Explain how programs make decisions based on conditions:
     ```python
     if condition:
         # Code block that runs if the condition is True
     elif another_condition:
         # Code block that runs if the first condition is False and this condition is True
     else:
         # Code block that runs if none of the conditions are True
     ```
     **Key points:**
     - Conditions in Python evaluate to either `True` or `False`.
     - If the condition is true, the corresponding code block will be executed.

2. **Examples:**
   - Basic `if` statement:
     ```python
     age = 18

     if age >= 18:
         print("You are an adult.")
     else:
         print("You are a minor.")
     ```
     - Here, if the value of `age` is greater than or equal to 18, the message "You are an adult." is printed; otherwise, "You are a minor." is printed.

   - Using `elif` (else if):
     ```python
     grade = 85

     if grade >= 90:
         print("You got an A!")
     elif grade >= 80:
         print("You got a B!")
     else:
         print("You need to study more!")
     ```

3. **Practice Activity:**
   - Have students write a program that checks if a number is positive, negative, or zero using `if`, `elif`, and `else` statements.
     Example:
     ```python
     number = int(input("Enter a number: "))

     if number > 0:
         print("The number is positive.")
     elif number < 0:
         print("The number is negative.")
     else:
         print("The number is zero.")
     ```

4. **Homework:**
   - Write a program that asks a student for their exam score and prints "Passed" if the score is 50 or higher, otherwise prints "Failed."
     - **Bonus Task:** Extend the program to print different grades like A, B, C, or Fail based on score ranges (e.g., A for 90+, B for 80-89, etc.).

## Key Takeaways:
- Conditional statements allow the program to make decisions based on conditions.
- `if`, `elif`, and `else` are commonly used to structure these decisions.
