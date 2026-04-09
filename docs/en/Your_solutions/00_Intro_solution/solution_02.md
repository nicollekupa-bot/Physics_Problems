```python?code_reference&code_event_index=2
import numpy as np

# Coefficients matrix
A = np.array([[2, 3], [1, -1]])
# Constants vector
B = np.array([12, 1])

# Solve the system
solution = np.linalg.solve(A, B)
x, y = solution

print(f"x = {x}")
print(f"y = {y}")

```
```text?code_stdout&code_event_index=2
x = 3.0
y = 2.0

```
To find the values of $x$ and $y$ that satisfy both equations, we can use the substitution method or the elimination method.

### Method 1: Substitution
From the second equation, we can express $x$ in terms of $y$:
$$x - y = 1 \implies x = y + 1$$

Now, substitute this expression for $x$ into the first equation:
$$2(y + 1) + 3y = 12$$
$$2y + 2 + 3y = 12$$
$$5y + 2 = 12$$
$$5y = 10$$
$$y = 2$$

Now, substitute $y = 2$ back into the expression for $x$:
$$x = 2 + 1 = 3$$

### Method 2: Elimination
Multiply the second equation by 3 to align the $y$ terms:
$$3(x - y) = 3(1) \implies 3x - 3y = 3$$

Now, add this to the first equation:
$$(2x + 3y) + (3x - 3y) = 12 + 3$$
$$5x = 15$$
$$x = 3$$

Substitute $x = 3$ into the original second equation:
$$3 - y = 1$$
$$y = 2$$



[Image of a system of linear equations graph]


**Final Answer:**
The solution to the system is $x = 3$ and $y = 2$.