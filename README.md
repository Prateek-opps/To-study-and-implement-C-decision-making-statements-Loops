# 📘 C++ Programs Collection

This repository contains a variety of C++ programs that demonstrate foundational programming concepts such as loops, conditionals, pattern printing, and input/output handling. These programs are excellent for beginners to develop a strong understanding of control flow and syntax in C++.

---

## 🔹 Program 1: Print Numbers 1 to 20

**🎯 Theory:**
A `while` loop is a control structure that repeatedly executes a block of code as long as a specified condition remains true.

**📌 Algorithm:**
1. Initialize a counter `i = 0`.
2. While `i < 20`, do:
   - Print `i + 1` followed by a space.
   - Increment `i`.
   - Print a newline.

Output:-
1
2 
3 
4 
5 
6 
7 
8 
9 
10 
11 
12 
13 
14 
15 
16 
17 
18 
19 
20 


**✅ Conclusion:**
Introduces the use of `while` loops and basic output formatting.

---

## 🔹 Program 2: Number Triangle

**🎯 Theory:**
Nested loops allow iteration over multiple dimensions (like rows and columns). Here, they're used to print increasing numbers in a triangle pattern.

**📌 Algorithm:**
1. Input the number of rows.
2. Initialize a counter `num = 1`.
3. Loop over rows (i from 1 to n):
   - For each row, print `i` numbers starting from `num`.
   - Increment `num` accordingly.

Output:-

Enter number of rows: 6

1 

2 3 

4 5 6 

7 8 9 10 

11 12 13 14 15 

16 17 18 19 20 21 

**✅ Conclusion:**
Helps understand nested loops and control of variables inside loop bodies.

---

## 🔹 Program 3: Diamond Star Pattern

**🎯 Theory:**
Pattern printing requires understanding how to manipulate spacing and symbols using nested loops. Symmetric shapes involve reversing patterns.

**📌 Algorithm:**
1. Set `n = 7` for the total width.
2. Loop to print upper half of diamond:
   - Print increasing spaces and decreasing stars.
3. Loop to print lower half:
   - Reverse the logic of the upper half.

Output:-

* * * * * * * 
  * * * * * 
    * * * 
      * 
    * * * 
  * * * * * 
* * * * * * * 

**✅ Conclusion:**
Demonstrates loop nesting, symmetry, and output formatting.

---

## 🔹 Program 4: Left-Aligned Triangle of Stars

**🎯 Theory:**
Basic triangle patterns can be printed by controlling the number of stars in each row based on the row number.

**📌 Algorithm:**
1. Set `n = 5`.
2. Loop `i` from 1 to `n`.
   - Loop `j` from 1 to `i`.
   - Print stars.

**✅ Conclusion:**
Teaches how to print increasing patterns using simple nested loops.

---

## 🔹 Program 5: Nested Loop with Labels

**🎯 Theory:**
Nested loops can be used to iterate over multiple levels. Each loop can perform independent tasks.

**📌 Algorithm:**
1. Loop `i` from 1 to 2 (outer loop).
   - Print "Outer" with `i`.
   - Loop `j` from 1 to 3 (inner loop).
     - Print "Inner" with `j`.

**✅ Conclusion:**
Clarifies how inner loops work within outer loops.

---

## 🔹 Program 6: Right-Aligned Triangle of Stars

**🎯 Theory:**
To align triangles to the right, we print spaces before stars. The number of spaces decreases as stars increase.

**📌 Algorithm:**
1. Set `n = 5`.
2. Loop `i` from 1 to `n`:
   - Print `n - i` spaces.
   - Print `i` stars.

**✅ Conclusion:**
Combines spacing and pattern logic for formatted output.

---

## 🔹 Program 7: Print Even Numbers from 0 to 10

**🎯 Theory:**
The modulus operator (`%`) is used to determine divisibility. Even numbers have no remainder when divided by 2.

**📌 Algorithm:**
1. Loop from `i = 0` to `10`.
2. If `i % 2 == 0`, print `i`.

**✅ Conclusion:**
Demonstrates use of conditional statements inside loops.

---

## 🔹 Program 8: Password Authentication System

**🎯 Theory:**
Programs can control access using conditionals and loops. Limited attempts add basic security.

**📌 Algorithm:**
1. Set correct password as a constant.
2. Allow up to 3 user attempts.
3. If correct, unlock system.
4. Else, decrement attempt and retry or lock system.

**✅ Conclusion:**
Practices input validation, `while` loops, and conditionals.

---

## 🔹 Program 9: Reverse an Integer

**🎯 Theory:**
Numbers can be reversed by extracting digits using modulo and forming a new number by multiplying the result by 10 and adding each digit.

**📌 Algorithm:**
1. Set `reversed = 0`.
2. While number > 0:
   - Get last digit using `% 10`.
   - Update reversed number.
   - Remove digit from original number using `/ 10`.

**✅ Conclusion:**
Teaches number manipulation using loops and arithmetic operations.

---

## 🔹 Program 10: Print "SIT" 6 Times

**🎯 Theory:**
Loops are used to execute repeated tasks efficiently.

**📌 Algorithm:**
1. Loop from 0 to 5.
2. Print `"SIT"` each iteration.

**✅ Conclusion:**
Simple use of loop for repeated output.

---

## 📚 Final Summary

These programs collectively introduce:

- ✅ **Loops** (`for`, `while`)
- ✅ **Nested Loops**
- ✅ **Conditionals** (`if`, `else`)
- ✅ **User Input and Output**
- ✅ **Pattern Printing**
- ✅ **Basic Authentication Logic**
- ✅ **Mathematical Computation**

They are essential for anyone beginning with C++ and looking to develop logical thinking and problem-solving through code.

---


