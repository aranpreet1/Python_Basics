# Class Brief: Session 01 - Python Basics & Intro to Lists

**Date:** August 18, 2026  
**Instructor:** Gaurav Singh | Saras AI Institute  

---

## 🎯 Overview
Welcome to Session 01! This class laid the foundation for our Python journey. We explored the Google Colab environment, understood how Python categorizes data, learned to manipulate that data using operators and variables, and took our first look at organizing multiple pieces of data using Lists.

---

## 📚 What We Covered & Concept Review

### 1. Google Colab Environment
Before writing code, we need to know our workspace. Colab runs Python in your browser using "cells."
* **Shortcuts to remember:** 
  * `Shift + Enter`: Run the current cell and move to the next.
  * `Ctrl + Enter`: Run the current cell and stay on it.
  * `A` / `B`: Insert a new code cell **A**bove or **B**elow the current one.
* **Outputting Data:** In Colab, you don't need a special command to see your result. Just type the value, variable, or expression on the last line of your code cell, and Colab will display the output automatically.

### 2. Data Types & Core Functions
Data comes in different shapes. Python needs to know what kind of data it's looking at to process it correctly.
* **Types:** `Integer` (whole numbers), `Float` (decimals), `String` (text), `Boolean` (True/False).
* **Strings:** Can be declared using `'single'`, `"double"`, or `'''triple'''` quotes.
* **Core Functions:**
  ```python
  # type() tells you what kind of data you are working with
  
  type(10)
  # Colab Output: int

  type(10.5)     
  # Colab Output: float
  ```

### 3. Operators: Math & Logic
Operators allow us to perform calculations and make decisions.
* **Arithmetic:** `+`, `-`, `*`, `/`. 
  * *Crucial rule:* Division (`/`) **always** returns a Float, even if the numbers divide evenly (e.g., `10 / 2` becomes `5.0`).
* **Comparison:** `>`, `<`, `>=`, `<=`, `==` (Equal to), `!=` (Not equal to).
  ```python
  # Checking equality
  10 == 5 
  # Colab Output: False 
  ```

### 4. Variables: Storing Data
Variables act as labeled containers for our data. They make our code dynamic, reusable, and easy to read.
* **Assignment (`=`):** Stores the value on the right inside the variable on the left.
* **Overwriting:** If you assign a new value to an existing variable name, the old value is erased.
* **Compound Assignment:** Shorthand ways to update variables (`+=`, `-=`, `*=`, `/=`).
  ```python
  # Complex assignment
  final_value = 45 * 3 - 90 / 34 
  
  # Overwriting a variable
  score = 10
  score = 20 # 'score' is now 20
  
  # Shorthand assignment
  score += 5 # Same as: score = score + 5
  
  # Seeing the result in Colab
  score
  # Colab Output: 25
  ```

---

## 💡 Extra Tips & Best Practices
* **Variables don't remember formulas, just the final answer:** When you run `x = 10 + 5`, Python calculates `15` and stores it. The variable `x` doesn't know how it got the number `15`. 
* **`=` vs `==` (The most common beginner error):** 
  * Use a single `=` to **TELL** Python something. (`age = 25` -> "Python, age is now 25.")
  * Use double `==` to **ASK** Python something. (`age == 25` -> "Python, is the age 25?")
* **Meaningful Names:** Avoid variables like `a`, `b`, or `x`. Use descriptive names like `total_price` or `movie_title`. It makes debugging much easier.
* **Read Your Errors:** If your Colab cell throws an error, don't panic. Read the bottom line of the error message first—it usually tells you exactly what went wrong (like a typo or a missing bracket).

---

## 📖 Additional Resources
* [Python Data Types (W3Schools)](https://www.w3schools.com/python/python_datatypes.asp) - *Great visual breakdown of basic types.*
* [Python Operators Documentation](https://docs.python.org/3/tutorial/introduction.html#using-python-as-a-calculator) - *Official guide to math and logic in Python.*
* [Python Tutor](https://pythontutor.com/) - *An amazing visual tool. Paste your code here to watch how Python creates and overwrites variables step-by-step.*

---


* **Task 1:** Create a new Colab notebook. Define a list of your 5 favorite numbers.
* **Task 2:** Use Python functions to find the sum, the maximum, and the minimum of your list.
* **Task 3:** Try assigning the result of `sum()` to a new variable, and output it by typing the variable name at the bottom of the cell!