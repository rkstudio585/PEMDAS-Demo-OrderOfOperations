# PEMDAS-Demo-OrderOfOperations
 - Arithmetic Order of Operations Explained

This project demonstrates the impact of the arithmetic order of operations (PEMDAS) on a mathematical expression. By comparing two similar expressions, we see how a simple change can lead to a completely different result.

## Overview

In arithmetic, the **order of operations** determines the sequence in which calculations are performed in a mathematical expression. The standard rule, often remembered as **PEMDAS** (Parentheses, Exponents, Multiplication and Division (left to right), Addition and Subtraction (left to right)), helps ensure consistent and correct results.

In this project, we analyze two expressions:
1. **Before:** `(5 + 5) + 5 + (5 + (-5)) - 5 × 2`

   - ![before](before.jpg)
3. **After:** `(5 + 5) + 5 + (5 + (-5)) - 5`

   - ![after](after.jpg)

By examining these two expressions, we can see how removing a single multiplication operation changes the result.

---

## Expression Analysis

### 1. Before Expression

The expression in the "Before" example is:

(5 + 5) + 5 + (5 + (-5)) - 5 × 2

**Step-by-Step Evaluation:**

1. **Parentheses**:
   - `(5 + 5) = 10`
   - `(5 + (-5)) = 0`
   
   Now, the expression becomes:

10 + 5 + 0 - 5 × 2

2. **Multiplication**:
- `5 × 2 = 10`

Substituting this result, the expression now is:

10 + 5 + 0 - 10

3. **Addition and Subtraction (Left to Right)**:
- `10 + 5 = 15`
- `15 + 0 = 15`
- `15 - 10 = 5`

So, the final answer for the "Before" expression is:

Answer = 5

---

### 2. After Expression

The expression in the "After" example is:

(5 + 5) + 5 + (5 + (-5)) - 5

**Step-by-Step Evaluation:**

1. **Parentheses**:
   - `(5 + 5) = 10`
   - `(5 + (-5)) = 0`
   
   Now, the expression becomes:

10 + 5 + 0 - 5

2. **Addition and Subtraction (Left to Right)**:
- `10 + 5 = 15`
- `15 + 0 = 15`
- `15 - 5 = 10`

So, the final answer for the "After" expression is:

Answer = 10

---

## Key Takeaways

1. **Order of Operations (PEMDAS)**:
   - **PEMDAS** is essential for evaluating mathematical expressions correctly.
   - Multiplication and division are evaluated before addition and subtraction unless there are parentheses that specify otherwise.

2. **Impact of Multiplication**:
   - In the "Before" expression, the term `5 × 2` created a larger subtraction (10), resulting in a lower final answer (5).
   - By removing the `× 2` in the "After" expression, we only subtract 5, resulting in a higher answer (10).

3. **Small Changes, Big Difference**:
   - A simple change in the expression structure can lead to a significant difference in the outcome. This example illustrates the importance of paying attention to every component of a mathematical expression.

---

## Conclusion

This project illustrates the importance of **understanding and applying the order of operations** in arithmetic expressions. A small change, like removing a multiplication, can drastically alter the result. Always keep PEMDAS in mind when evaluating or writing mathematical expressions to ensure accuracy.

Feel free to experiment with other expressions to see how small adjustments affect the outcome. Arithmetic precision is crucial, especially in programming and mathematics!

---

## Additional Resources

- [Order of Operations (PEMDAS)](https://www.mathsisfun.com/operation-order-pemdas.html)
- [Understanding Parentheses and Operator Precedence](https://en.wikipedia.org/wiki/Order_of_operations)
- [Interactive PEMDAS Practice](https://www.khanacademy.org/math/algebra/x2f8bb11595b61c86:expanding-and-factoring-expressions/x2f8bb11595b61c86:order-of-operations/e/order_of_operations)

---
