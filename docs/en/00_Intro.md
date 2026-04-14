```python?code_reference&code_event_index=2
from sympy import symbols, Eq, solve

x, y = symbols('x y')
eq1 = Eq(2*x + 3*y, 12)
eq2 = Eq(x - y, 1)

solution = solve((eq1, eq2), (x, y))
print(f"{solution=}")


```
```text?code_stdout&code_event_index=2
solution={x: 3, y: 2}

```
To find the values of $x$ and $y$ that satisfy the system of equations, we can use the **substitution method** or the **elimination method**. Here is the step-by-step solution using substitution:

### Given Equations:
1.  $2x + 3y = 12$
2.  $x - y = 1$

### Step 1: Isolate one variable
From the second equation, we can easily isolate $x$:
$$x = y + 1$$

### Step 2: Substitute into the other equation
Now, substitute this expression for $x$ into the first equation:
$$2(y + 1) + 3y = 12$$

### Step 3: Solve for $y$
Distribute the $2$ and combine like terms:
$$2y + 2 + 3y = 12$$
$$5y + 2 = 12$$
Subtract $2$ from both sides:
$$5y = 10$$
Divide by $5$:
$$y = 2$$

### Step 4: Solve for $x$
Plug the value of $y$ back into our equation for $x$:
$$x = 2 + 1$$
$$x = 3$$



[Image of solving systems of linear equations by graphing]


### Final Answer:
The solution to the system is:
**$x = 3$**
**$y = 2$**

### Verification:
* **Equation 1:** $2(3) + 3(2) = 6 + 6 = 12$ (Correct)
* **Equation 2:** $3 - 2 = 1$ (Correct)