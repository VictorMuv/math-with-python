# Math with Python Bootcamp

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VictorMuv/math-with-python/)

## Course Philosophy

This bootcamp bridges algebra concepts with Python programming, showing how computational thinking enhances mathematical problem-solving.

## How This Course Works

### Traditional Python Files (.py)
Normally, Python code lives in `.py` files. Here's what happens when you run one:
1. **Writing**: You create a file like `solve_equation.py`
2. **Execution**: The Python interpreter:
   - Reads your code line by line
   - Converts it to bytecode
   - Executes the instructions
3. **Example**:
   ```python
   # solve_equation.py
   def solve_linear(a, b):
       return -b/a
   
   print(solve_linear(2, 4))  # Output: -2.0
   Run via terminal: python solve_equation.py

Why We're Using Google Colab
For this course, we'll use Google Colab because:

No setup required (runs in browser)

Free access to computing resources

Interactive notebooks combine code and explanations

Easy to share and collaborate

Learning Approach
Each lesson follows this pattern:

Algebra concept introduction

Traditional pencil-and-paper solution

Python implementation

Advantages of computational approach

Practical challenge

Getting Started
Open any notebook in Google Colab using the badge above

Make a copy (File → Save a copy in Drive)

Follow along with the examples

Complete the challenges

Course Structure
1. Python Foundations
Variables as algebraic variables

Operators as mathematical operators

Control flow for equation solving

Functions as reusable solution templates

2. Algebra Applications
Linear equations

Inequalities

Systems of equations

Polynomial operations

Example Lesson: Variables and Equations
Algebraic Approach
Solve for x:
3x + 5 = 20
Steps:

Subtract 5: 3x = 15

Divide by 3: x = 5
# Represent the equation
coefficient = 3
constant = 5
result = 20

# Solve
x = (result - constant) / coefficient
print(f"Solution: x = {x}")  # Output: Solution: x = 5.0

# Verification
print(3*x + 5 == 20)  # Output: True
Why Python Wins
Immediate verification

Handles decimal coefficients easily

Template for similar problems

Challenge
Create a Python solution for:
5x - 3 = 22
Bonus: Make it a function that works for any equation of form ax + b = c

How to Proceed
Start with 1_python_foundations/1_variables_datatypes.ipynb

Complete all exercises

Check your solutions against algebra work

Move to next concept when comfortable

Contribution Guidelines
Found a bug or have improvement?

Fork the repository

Create a branch

Submit a pull request

## Implementing This Structure

### 1. Update Your README.md
1. Go to your repository
2. Click on README.md → Edit (pencil icon)
3. Paste the above content
4. Commit changes with message "Comprehensive README update"

### 2. Create a Lesson Template

For each lesson notebook (`*.ipynb`), follow this structure:

```python
{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Lesson Title\n",
    "## Connecting Algebra to Python\n",
    "\n",
    "### Traditional Approach\n",
    "Explanation of the algebra concept\n",
    "\n",
    "### Python Implementation\n",
    "```python\n",
    "# PEP 8 compliant code\n",
    "def algebraic_solution(params):\n",
    "    \"\"\"\n",
    "    Properly documented function\n",
    "    \"\"\"\n",
    "    return solution\n",
    "```\n",
    "\n",
    "### Advantages\n",
    "- Benefit 1\n",
    "- Benefit 2\n",
    "\n",
    "### Challenge\n",
    "Problem statement\n",
    "```python\n",
    "# Student's workspace\n",
    "# They should write solution here\n",
    "```"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# Example solution (collapsed by default in notebook)\n",
    "def challenge_solution():\n",
    "    pass"
   ]
  }
 ],
 "metadata": {}
}
