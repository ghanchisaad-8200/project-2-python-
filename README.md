# Pattern Generator and Number Analyzer

## Project Description

Pattern Generator and Number Analyzer is a beginner-level Python project developed to practice fundamental programming concepts such as loops, conditional statements, functions, nested loops, and menu-driven programming.

The program provides two main features:
- Generate a right-angled triangle pattern.
- Analyze a range of numbers by checking whether each number is odd or even and calculating the total sum.

---

## Features

### 1. Pattern Generator
- Generates a right-angled triangle using `*`.
- Takes the number of rows as user input.
- Uses nested `for` loops.

### 2. Number Analyzer
- Accepts a starting number and an ending number.
- Displays whether each number is Odd or Even.
- Calculates the sum of all numbers in the given range.
- Uses the `range()` function and loops.

### 3. Menu-Driven Interface
- Generate Pattern
- Analyze Numbers
- Exit Program

### 4. Input Validation
- Prevents invalid row values.
- Ensures the ending number is greater than or equal to the starting number.
- Displays appropriate error messages.

---

## Programming Concepts Used

- Variables
- User Input (`input()`)
- Output (`print()`)
- Data Types
- Conditional Statements (`if`, `elif`, `else`)
- `for` Loop
- `while` Loop
- Nested Loops
- `range()` Function
- `break`
- `continue`
- `pass`

---

## Project Structure

```
project-folder/
│
├── project.py
├── README.md
```

---

## How to Run

1. Install Python 3.x.
2. Download or clone the project.
3. Open the project folder.
4. Run the program:

```bash
python project.py
```

---

## Sample Output

```
Welcome to the Pattern Generator and Number Analyzer

1. Generate a Pattern
2. Analyze a Range of Numbers
3. Exit

Enter your choice: 1

Enter number of rows: 5

*
**
***
****
*****
```

```
Enter your choice: 2

Enter start of range: 10
Enter end of range: 15

10 is Even
11 is Odd
12 is Even
13 is Odd
14 is Even
15 is Odd

Sum of all numbers: 75
```

---

## Future Improvements

- Add more pattern designs.
- Find prime numbers.
- Display multiplication tables.
- Save results to a text file.
- Improve the user interface.

---

## Author

**Name:** Saad Ghanchi

**Course:** Python – Data Science

---

## License

This project is created for educational purposes only.
