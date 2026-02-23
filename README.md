
## **Lab Report: Study of For Loops in Python**

**Student:** Vedant Trivedi

**PRN:** 25070123121

### **Aim**

To understand the syntax and application of `for` loops in Python, including the use of the `range()` function, nested loops for multi-dimensional data structures, and algorithmic logic for pattern generation and mathematical computations.

---

## **1. Basic Iteration (1 to 5 & Even Numbers)**

### **Theory**

The `for` loop in Python iterates over a sequence (list, tuple, string) or a range of numbers. The `range(start, stop, step)` function generates a sequence where the `stop` value is exclusive.

### **Algorithm**

1. Initialize the loop with a range.
2. For each iteration, assign the current value to the loop variable `i`.
3. Print the value of `i`.
4. (Optional) Use the `step` parameter to increment by values other than 1.

---

## **2. Sum of First N Numbers**

### **Theory**

This demonstrates an **accumulator pattern**. A variable is initialized to zero and updated within the loop to store the running total of a series.

### **Algorithm**

1. Take integer input  from the user.
2. Initialize `total = 0`.
3. Loop through the range  to .
4. In each step, add the current loop variable to `total` ().
5. Print the final value of `total`.

---

## **3. 3x3 Matrix Display**

### **Theory**

Matrices are represented as "lists of lists." To access individual elements, **nested loops** are required: the outer loop handles rows, and the inner loop handles columns.

### **Algorithm**

1. Define a 2D list `A`.
2. Outer loop: Iterate through index `i` (0 to 2) for rows.
3. Inner loop: Iterate through index `j` (0 to 2) for columns.
4. Print the element `A[i][j]` using `end=" "` to keep them on the same line.
5. Print a newline after the inner loop finishes to move to the next row.

---

## **4. Matrix Multiplication**

### **Theory**

Matrix multiplication  requires three nested loops. The element at  is the dot product of the -th row of  and the -th column of .

### **Algorithm**

1. Initialize two 3x3 matrices () and a result matrix with zeros.
2. Loop `i` (rows of A).
3. Loop `j` (columns of B).
4. Loop `k` (common dimension): Multiply `A[i][k]` with `B[k][j]` and add to `Result[i][j]`.
5. Print the resulting matrix.

---

## **5. All Possible Combinations of Three Digits**

### **Theory**

This uses **triple-nested loops** to generate all permutations. A conditional `if` statement acts as a filter to ensure that only unique digits are printed (no repetitions within a single combination).

### **Algorithm**

1. Store three digits in a list.
2. Run three nested loops, each iterating from index 0 to 2.
3. Inside the innermost loop, check if the three current indices are unique ().
4. If unique, print the elements at those indices.

---

## **6. Pattern Design (Right Angle Triangle & Pyramid)**

### **Theory**

Patterns utilize the relationship between the loop index and string multiplication. In Python, `'*' * 5` outputs `*****`.

### **Algorithm (Pyramid)**

1. Define the number of rows.
2. Loop from  to `rows`.
3. Calculate spaces: `rows - i`.
4. Calculate stars: `i` (with a trailing space for alignment).
5. Concatenate spaces and stars, then print.

---

## **Conclusion**

Through these exercises, I have successfully implemented various `for` loop structures in Python. I observed that:

* `range()` is a versatile tool for controlling iteration limits.
* Nested loops are essential for handling multi-dimensional data like matrices and permutations.
* Python's ability to perform string multiplication simplifies pattern generation compared to traditional iterative character printing.

---
