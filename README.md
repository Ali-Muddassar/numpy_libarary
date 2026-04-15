# NumPy Library Practice

## Description

A Jupyter notebook introducing NumPy arrays and fundamental operations. NumPy is the core library for numerical computing in Python and forms the foundation for data analysis with Pandas and machine learning with scikit-learn. Created as part of my data science learning journey with **@Codanics**.

---

## Topics Covered

| Topic | Description |
| :--- | :--- |
| **What is an Array?** | Understanding NumPy arrays vs Python lists |
| **Creating Arrays** | `np.array()`, `np.zeros()`, `np.ones()`, `np.full()`, `np.eye()` |
| **Array Attributes** | `shape`, `size`, `ndim`, `dtype`, `len()` |
| **Adding Dimensions** | Using `np.newaxis` to increase array dimensions |
| **Basic Operations** | Addition, subtraction, multiplication, division, exponentiation |
| **Vectorized Operations** | Performing operations on entire arrays without loops |

---

## Libraries Used

- `numpy` — Numerical computing and array operations

---

## Key Concepts Demonstrated

```python
import numpy as np

# From Python lists
a = np.array([1, 2, 3, 4, 5])

# Pre-initialized arrays
zeros = np.zeros((2, 5))      # 2x5 array of zeros
ones  = np.ones((2, 5))       # 2x5 array of ones
full  = np.full((2, 5), 7.5)  # 2x5 array filled with 7.5
eye   = np.eye(5)             # 5x5 identity matrix

# Array Attributes
arr.shape    # Dimensions (rows, columns)
arr.size     # Total number of elements
arr.ndim     # Number of dimensions
arr.dtype    # Data type of elements

# Adding Dimensions with np.newaxis
a  = np.arange(6)         # Shape: (6,)
a2 = a[np.newaxis, :]     # Shape: (1, 6)
a3 = a2[np.newaxis, :]    # Shape: (1, 1, 6)

# Vectorized Operations (element-wise, no loops needed)
a + b      # Addition
a - b      # Subtraction
a * b      # Multiplication
a / b      # Division
a ** 2     # Square each element
` ` `

---

## About Me

**Ali Muddassar**

[![GitHub](https://img.shields.io/badge/GitHub-Ali--Muddassar-181717?logo=github)](https://github.com/Ali-Muddassar)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ali%20Muddassar-0077B5?logo=linkedin)](https://www.linkedin.com/in/ali-muddassar-17466a3b7)

---

*Part of the **Python Ka Chilla** journey with @Codanics.*
```

> **Note:** Remove the spaces in the closing ` ` ` of the code block — I added them so it wouldn't break the outer markdown here. On GitHub it should be three backticks with no spaces: ` ``` `
