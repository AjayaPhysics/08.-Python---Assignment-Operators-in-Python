# 08.-Python---Assignment-Operators-in-Python
Here's a detailed explanation and examples of Assignment Operators in Python for your GitHub repository.
# Python Course: Assignment Operators

This repository is part of a complete Python course, designed to explain fundamental concepts and their practical applications. This section focuses on **Assignment Operators**.

## Overview

Assignment operators are used in Python to assign values to variables. These operators range from the basic `=` operator to more complex ones that combine arithmetic and bitwise operations with assignment.

## List of Assignment Operators

| Operator | Description                              | Example                         |
|----------|------------------------------------------|---------------------------------|
| `=`      | Assigns the right-hand value to a variable | `x = 5`                         |
| `+=`     | Adds the right-hand operand to the left-hand operand and assigns the result to the left-hand operand | `x += 3` (same as `x = x + 3`) |
| `-=`     | Subtracts the right-hand operand from the left-hand operand and assigns the result to the left-hand operand | `x -= 2` (same as `x = x - 2`) |
| `*=`     | Multiplies the left-hand operand by the right-hand operand and assigns the result to the left-hand operand | `x *= 4` (same as `x = x * 4`) |
| `/=`     | Divides the left-hand operand by the right-hand operand and assigns the result to the left-hand operand | `x /= 2` (same as `x = x / 2`) |
| `//=`    | Performs floor division and assigns the result | `x //= 2` (same as `x = x // 2`) |
| `%=`     | Performs modulus operation and assigns the result | `x %= 3` (same as `x = x % 3`) |
| `**=`    | Raises the left-hand operand to the power of the right-hand operand and assigns the result | `x **= 2` (same as `x = x ** 2`) |
| `&=`     | Performs bitwise AND operation and assigns the result | `x &= 3` (same as `x = x & 3`) |
| `|=`     | Performs bitwise OR operation and assigns the result | `x |= 2` (same as `x = x | 2`) |
| `^=`     | Performs bitwise XOR operation and assigns the result | `x ^= 4` (same as `x = x ^ 4`) |
| `>>=`    | Performs right shift and assigns the result | `x >>= 1` (same as `x = x >> 1`) |
| `<<=`    | Performs left shift and assigns the result | `x <<= 1` (same as `x = x << 1`) |

## Explanation and Examples

Each operator is explained with clear examples to demonstrate its use. Refer to the `assignment_operators.py` file in this repository for complete code samples.

### Example: Add and Assign (`+=`)

```python
x = 5
x += 3
print(x)  # Output: 8
