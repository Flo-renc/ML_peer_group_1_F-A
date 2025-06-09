
# 📘 alumath-Group1

A simple Python library for **matrix multiplication**, developed as part of a group assignment on advanced linear algebra.

## 🔧 Installation

To install the package from [PyPI](https://pypi.org/), run the following command:

```bash
pip install alumath-Group1==0.1.0
```

> ⚠️ Requires Python 3.6 or later.

---

## ✅ Usage Example

Once installed, use it in your Python code as follows:

### 💡 Matrix Multiplication

```python
from alumath_Group1 import multiply_matrices

A = [[1, 2], [3, 4]]
B = [[5, 6], [7, 8]]

result = multiply_matrices(A, B)

print("Matrix Multiplication Result:")
print(result)
```

### 🟢 Expected Output:

```
Matrix Multiplication Result:
[[19, 22], [43, 50]]
```

---

## 🚫 Error Handling

If the matrices have incompatible dimensions, the library will raise an error:

```python
A = [[1, 2], [3, 4]]
B = [[5, 6]]  # Invalid shape

result = multiply_matrices(A, B)  # Raises ValueError
```

### ❌ Output:

```
ValueError: Incompatible dimensions for matrix multiplication
```

---

## 🧪 Advanced Test (Optional)

You can test the library with larger matrices:

```python
from alumath_Group1 import multiply_matrices

A = [[1, 2, 3], [4, 5, 6]]
B = [[7, 8], [9, 10], [11, 12]]

result = multiply_matrices(A, B)

print("Advanced Multiplication Result:")
for row in result:
    print(row)
```

### ✅ Output:

```
Advanced Multiplication Result:
[58, 64]
[139, 154]
```

---

## 👨‍🏫 Testing Instructions

1. Open terminal or command prompt.
2. Run `pip install alumath-Group1==0.1.0`.
3. Run any of the example Python codes above.
4. You should see the correct output or error handling depending on input.

---

## 👥 Authors

This library was developed by Group 1 as part of a **Principal Component Analysis** assignment focused on matrix algebra.

---

## 📄 License

This project is licensed for academic purposes only.
