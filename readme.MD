# Go Programming Exercises - Basic Syntax and Control Flow

This repository contains a comprehensive set of beginner-friendly Go programming exercises designed to help students master basic syntax, control flow, and different data types.

## 📚 Table of Contents

- [Getting Started](#getting-started)
- [Integer Exercises](#integer-exercises)
- [String Exercises](#string-exercises)
- [Boolean Exercises](#boolean-exercises)
- [Float Exercises](#float-exercises)
- [Mixed Type Exercises](#mixed-type-exercises)
- [General Requirements](#general-requirements)
- [Submission Guidelines](#submission-guidelines)

## 🚀 Getting Started

Before starting these exercises, make sure you have:
- Go installed on your system (version 1.19 or later)
- A text editor or IDE of your choice
- Basic understanding of Go syntax

To run a Go program:
```bash
go run filename.go
```

## 🔢 Integer Exercises

### Exercise 1: Even/Odd Checker
**Difficulty:** ⭐

Write a program that prompts the user to enter an integer and determines whether the number is even or odd. Display an appropriate message for each case.

**Sample Input/Output:**
```
Enter a number: 7
7 is odd

Enter a number: 12
12 is even
```

**Skills Practiced:** Basic I/O, conditionals, modulo operator

---

### Exercise 2: Sum of Digits
**Difficulty:** ⭐⭐

Create a program that takes a positive integer as input and calculates the sum of its digits. For example, if the input is 1234, the output should be 10 (1+2+3+4).

**Requirements:**
- Handle multi-digit numbers
- Use loops to extract each digit
- Display the original number and the sum

**Skills Practiced:** Loops, arithmetic operations, digit extraction

---

### Exercise 3: Number Guessing Game
**Difficulty:** ⭐⭐

Implement a number guessing game where:
- The program generates a random number between 1 and 100
- The user has to guess the number
- After each guess, provide feedback: "Too high", "Too low", or "Correct!"
- Count and display the number of attempts when the user wins

**Skills Practiced:** Random number generation, loops, conditionals, user interaction

---

### Exercise 4: Multiplication Table
**Difficulty:** ⭐

Write a program that asks the user for a number and displays its multiplication table from 1 to 10.

**Sample Output for input 5:**
```
5 x 1 = 5
5 x 2 = 10
...
5 x 10 = 50
```

**Skills Practiced:** Loops, basic arithmetic, formatting output

## 🔤 String Exercises

### Exercise 5: Palindrome Checker
**Difficulty:** ⭐⭐

Create a program that checks if a given string is a palindrome (reads the same forwards and backwards). The program should ignore spaces and be case-insensitive.

**Test Cases:**
- "racecar" → true
- "A man a plan a canal Panama" → true
- "hello" → false

**Skills Practiced:** String manipulation, loops, conditionals, case handling

---

### Exercise 6: Character Frequency Counter
**Difficulty:** ⭐⭐⭐

Write a program that takes a string as input and counts the frequency of each character. Display the results in a readable format.

**Sample Input/Output:**
```
Enter a string: hello world
h: 1
e: 1
l: 3
o: 2
 : 1
w: 1
r: 1
d: 1
```

**Skills Practiced:** String iteration, maps/counting, data structures

---



### Exercise 7: String Reverser
**Difficulty:** ⭐⭐

Implement a program that reverses a string without using any built-in reverse functions. Use loops and string manipulation.

**Skills Practiced:** String manipulation, loops, indexing

---

### Exercise 8: Vowel Counter
**Difficulty:** ⭐⭐

Create a program that counts the number of vowels (a, e, i, o, u) in a given string. Make it case-insensitive and display both the count and which vowels were found.

**Skills Practiced:** String processing, conditionals, case handling

## ✅ Boolean Exercises

### Exercise 9: Eligibility Checker
**Difficulty:** ⭐

Write a program that determines various eligibilities based on age:
- Voting (18+)
- Driving (16+)
- Senior citizen benefits (65+)

The program should take an age as input and display all applicable eligibilities.

**Skills Practiced:** Boolean logic, conditionals, multiple conditions

---

### Exercise 10: Password Strength Validator
**Difficulty:** ⭐⭐⭐

Create a password strength checker that evaluates a password based on these criteria:
- At least 8 characters long
- Contains at least one uppercase letter
- Contains at least one lowercase letter
- Contains at least one digit
- Contains at least one special character (!@#$%^&*)

Display whether the password is weak, medium, or strong, and list which criteria are missing.

**Skills Practiced:** String analysis, boolean logic, complex conditionals

## 🔢 Float Exercises

### Exercise 11: Temperature Converter
**Difficulty:** ⭐⭐

Build a temperature conversion program that:
- Asks the user to choose conversion type (C to F, F to C, or both)
- Takes a temperature value as input
- Performs the conversion and displays the result with 2 decimal places

**Formulas:**
- Celsius to Fahrenheit: `F = (C × 9/5) + 32`
- Fahrenheit to Celsius: `C = (F - 32) × 5/9`

**Skills Practiced:** Float operations, formatting output, user menus

---

### Exercise 12: Simple Calculator
**Difficulty:** ⭐⭐

Create a calculator program that:
- Prompts for two numbers and an operation (+, -, *, /)
- Performs the calculation
- Handles division by zero
- Displays the result with appropriate precision

**Skills Practiced:** Float arithmetic, error handling, switch statements

---

### Exercise 13: Geometry Calculator
**Difficulty:** ⭐⭐⭐

Write a program that calculates area and perimeter for different shapes:
- Circle: given radius
- Rectangle: given length and width
- Triangle: given three sides

Let the user choose which shape to calculate and provide the appropriate inputs.

**Skills Practiced:** Mathematical calculations, user menus, multiple functions

---

### Exercise 14: BMI Calculator
**Difficulty:** ⭐⭐

Create a BMI (Body Mass Index) calculator that:
- Takes height (in meters) and weight (in kilograms) as input
- Calculates BMI using the formula: `BMI = weight / (height²)`
- Categorizes the result (Underweight, Normal, Overweight, Obese)
- Displays the BMI value and category

**BMI Categories:**
- Underweight: BMI < 18.5
- Normal: 18.5 ≤ BMI < 25
- Overweight: 25 ≤ BMI < 30
- Obese: BMI ≥ 30

**Skills Practiced:** Mathematical operations, categorization, float formatting

## 🔄 Mixed Type Exercises

### Exercise 15: Grade Calculator
**Difficulty:** ⭐⭐

Develop a grading system that:
- Takes a numeric score (0-100) as input
- Converts it to a letter grade (A, B, C, D, F)
- Displays both the numeric score and letter grade
- Handles invalid input (scores outside 0-100 range)

**Grading Scale:**
- A: 90-100
- B: 80-89
- C: 70-79
- D: 60-69
- F: Below 60

**Skills Practiced:** Input validation, switch/if statements, error handling

---

### Exercise 16: Time Converter
**Difficulty:** ⭐⭐

Write a program that converts seconds into a more readable format (hours, minutes, seconds). For example, 3665 seconds should display as "1 hour, 1 minute, 5 seconds".

**Skills Practiced:** Integer division, modulo operations, string formatting

---

### Exercise 17: Shopping Cart Calculator
**Difficulty:** ⭐⭐⭐

Create a shopping cart program that:
- Allows users to add items with their prices
- Calculates subtotal
- Applies tax (user-defined tax rate)
- Calculates final total
- Displays an itemized receipt

**Skills Practiced:** Arrays/slices, loops, float calculations, formatting

---

### Exercise 18: Loan Calculator
**Difficulty:** ⭐⭐⭐

Build a simple loan calculator that computes monthly payments given:
- Loan amount
- Annual interest rate
- Loan term (in years)

Use the standard loan payment formula and display the result.

**Skills Practiced:** Complex mathematical operations, financial calculations

## 📋 General Requirements

For all exercises, ensure your code includes:

### ✅ Code Quality
- **Clean Code**: Use meaningful variable names and proper indentation
- **Comments**: Add comments explaining complex logic
- **Functions**: Break down complex problems into smaller functions
- **Error Handling**: Handle edge cases and invalid inputs gracefully

### ✅ User Experience
- **Clear Prompts**: Provide clear instructions to users
- **Helpful Output**: Display results in a user-friendly format
- **Input Validation**: Check for valid input ranges and types
- **Error Messages**: Provide helpful error messages

### ✅ Testing
- **Sample Data**: Test with provided sample inputs
- **Edge Cases**: Test with boundary values (0, negative numbers, empty strings)
- **Invalid Input**: Test how your program handles wrong input types

## 📝 Submission Guidelines

### File Structure
```
exercises/
├── exercise01_even_odd.go
├── exercise02_sum_digits.go
├── exercise03_number_guessing.go
└── ...
```

### Code Template
```go
// Exercise [Number]: [Title]
// Description: [Brief description of what the program does]
// Author: [Your Name]
// Date: [Date]

package main

import "fmt"

func main() {
    // Your code here
}
```

### Documentation
- Include a comment block at the top of each file
- Add inline comments for complex logic
- Use descriptive variable and function names

### Testing
- Test each program with various inputs
- Include comments showing test cases you used
- Handle edge cases appropriately

## 🎯 Learning Objectives

By completing these exercises, students will:
- Master Go's basic syntax and data types
- Understand control flow structures (if/else, loops, switch)
- Practice input/output operations
- Learn proper error handling techniques
- Develop problem-solving skills
- Write clean, readable code
- Understand Go's approach to different data types

## 📚 Additional Resources

- [Go Tour](https://tour.golang.org/) - Interactive Go tutorial
- [Go Documentation](https://golang.org/doc/) - Official Go documentation
- [Effective Go](https://golang.org/doc/effective_go.html) - Go best practices

## 🏆 Progress Tracking

Track your progress by checking off completed exercises:

**Integer Exercises:**
- [ ] Exercise 1: Even/Odd Checker
- [ ] Exercise 2: Sum of Digits
- [ ] Exercise 3: Number Guessing Game
- [ ] Exercise 4: Multiplication Table

**String Exercises:**
- [ ] Exercise 5: Palindrome Checker
- [ ] Exercise 6: Character Frequency Counter
- [ ] Exercise 7: String Reverser
- [ ] Exercise 8: Vowel Counter

**Boolean Exercises:**
- [ ] Exercise 9: Eligibility Checker
- [ ] Exercise 10: Password Strength Validator

**Float Exercises:**
- [ ] Exercise 11: Temperature Converter
- [ ] Exercise 12: Simple Calculator
- [ ] Exercise 13: Geometry Calculator
- [ ] Exercise 14: BMI Calculator

**Mixed Type Exercises:**
- [ ] Exercise 15: Grade Calculator
- [ ] Exercise 16: Time Converter
- [ ] Exercise 17: Shopping Cart Calculator
- [ ] Exercise 18: Loan Calculator

---

**Happy Coding! 🚀**

Remember: The key to mastering programming is consistent practice. Start with easier exercises and gradually work your way up to more complex problems. Don't hesitate to experiment and try different approaches!