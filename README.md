# 🐍 NumPy Mastery Portfolio

Welcome to my **NumPy Projects Repository**! This showcases my hands-on expertise in Python and NumPy, with practical examples of arrays, broadcasting, vectorization, reshaping, and multidimensional data manipulation.

---

## 📂 Repository Overview

| File Name | Focus Area | Highlights |
|-----------|------------|------------|
| Numpy intro.ipynb | NumPy Basics | Arrays, indexing, slicing, and basic arithmetic operations. |
| NUMPY.ipynb | Advanced Operations | Vectorized operations, statistical functions, and memory efficiency. |
| NUMPY LAST.ipynb | Comprehensive Examples | Real-life scenarios, type casting, and advanced functions. |
| Numpy broadcast.ipynb | Broadcasting | Scalar, row, and column broadcasting with shape prediction. |
| num Broadcasting.ipynb | Broadcasting Practice | Further examples demonstrating broadcasting rules and exceptions. |
| Part5.ipynb | Vectorization | Element-wise math, exponential, sine, square root, Celsius-Fahrenheit conversion. |
| Part6.ipynb | Array Arithmetic | Broadcasting, addition of vectors and scalars, shape handling. |
| Part7.ipynb | Reshape & Flatten | Reshaping arrays, flatten vs ravel, memory vs copy, multidimensional views. |

---

## 🚀 Skills Demonstrated

- **Array Creation & Manipulation:** 1D, 2D, 3D arrays  
- **Vectorized Operations:** Fast, memory-efficient computations  
- **Broadcasting:** Scalar, row, and column broadcasting; handling incompatible shapes  
- **Reshape, Flatten & Ravel:** Converting dimensions, understanding views vs copies  
- **Subsetting & Slicing:** Extracting data from arrays of any dimension  
- **Type Casting:** Using `.astype()` for precision and memory optimization  
- **Built-in Array Functions:** `zeros`, `ones`, `eye`, `full`, `random` arrays  
- **Real-world Applications:** Mathematical computations, data preprocessing, and transformations  

---

## 📊 Visual Examples

### Vectorization Example

```python
import numpy as np

A = np.random.randint(1,100,size=5)
B = np.random.randint(1,70,size=5)

AB = A + B        # element-wise addition
sqrt_A = np.sqrt(A)  # square root

A = [43, 57, 33, 22, 80]
B = [48, 18, 60, 25, 16]
AB = [91, 75, 93, 47, 96]
sqrt_A = [6.557, 7.550, 5.745, 4.690, 8.944]
## Broadcasting Example
A = np.array([[1,4,3],[2,3,4],[4,5,6]])
B = np.array([1,2,3])
C = np.array([[1],[2],[3]])

print(A + 10)     # Scalar broadcasting
print(A + B)      # Row broadcasting
print(A + C)      # Column broadcasting
Output Example:
Scalar: [[11 14 13] [12 13 14] [14 15 16]]
Row:    [[ 2  6  6] [ 3  5  7] [ 5  7  9]]
Col:    [[ 2  5  4] [ 4  5  6] [ 7  8  9]]

🌟 Why This Portfolio is Unique

This portfolio is more than just a collection of NumPy notebooks—it demonstrates practical mastery, logical progression, and real-world problem-solving:

1.Structured Learning Path:

Starts from NumPy basics → progresses to advanced operations → then to broadcasting, reshaping, and vectorization.

Shows a clear step-by-step growth in skills, making it easy for recruiters to understand your competency.

2.Hands-On Practical Examples:

Each file contains real-life scenarios and examples, not just theoretical explanations.

Includes array manipulations, type casting, mathematical computations, and data transformations.

3.Deep Understanding of Broadcasting & Memory:

Demonstrates scalar, row, and column broadcasting.

Shows clear understanding of flatten vs ravel, views vs copies, and memory optimization—a skill many candidates overlook.

4.Vectorized Operations Expertise:

Efficient element-wise computations using NumPy, highlighting performance-conscious coding, which is critical for data analysis and machine learning workflows.

5.Comprehensive Coverage of Multidimensional Arrays:

From 1D to 3D arrays, including subsetting, slicing, reshaping, and advanced indexing.

Shows capability to work with complex datasets, preparing you for real-world data scenarios.

6.Readable & Well-Documented Code:

Each notebook is self-explanatory, with clear examples, outputs, and explanations.

Makes it easy for recruiters or hiring managers to verify skills quickly.

7.Problem-Solving Mindset:

Includes broadcasting exceptions and edge cases, showing analytical thinking and debugging skills.

Bottom Line: This portfolio reflects not only technical proficiency in NumPy but also practical problem-solving, efficiency, and a professional approach to data manipulation—all qualities highly valued in data analyst or data science roles.
