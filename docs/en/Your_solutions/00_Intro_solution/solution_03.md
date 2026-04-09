```python?code_reference&code_event_index=2
# Original variables
m1 = 1.0
m2 = 1.0
r = 1.0
G = 1.0

# Initial force
F1 = G * (m1 * m2) / (r**2)

# New variables
m1_new = 0.5 * m1
m2_new = 0.5 * m2
r_new = 2.0 * r

# New force
F2 = G * (m1_new * m2_new) / (r_new**2)

factor = F2 / F1
print(f"Initial Force: {F1}")
print(f"New Force: {F2}")
print(f"Factor: {factor}")

```
```text?code_stdout&code_event_index=2
Initial Force: 1.0
New Force: 0.0625
Factor: 0.0625

```
To determine the factor by which the gravitational force $F$ changes, we compare the initial state to the final state after the variables have been modified.

### 1. Initial State
The original gravitational force is given by:
$$F_1 = G \frac{m_1 m_2}{r^2}$$

### 2. Final State (with modifications)
According to the problem:
* The new distance is $r' = 2r$ (doubled).
* The new masses are $m_1' = \frac{1}{2}m_1$ and $m_2' = \frac{1}{2}m_2$ (halved).

Now, we substitute these new values into the formula for the new force $F_2$:
$$F_2 = G \frac{m_1' m_2'}{(r')^2}$$
$$F_2 = G \frac{(\frac{1}{2}m_1) (\frac{1}{2}m_2)}{(2r)^2}$$



[Image of Newton's law of universal gravitation diagram]


### 3. Simplifying the Expression
We can simplify the numerator and denominator separately:
* **Numerator:** $\frac{1}{2}m_1 \cdot \frac{1}{2}m_2 = \frac{1}{4} m_1 m_2$
* **Denominator:** $(2r)^2 = 4r^2$

Substitute these back into the equation:
$$F_2 = G \frac{\frac{1}{4} m_1 m_2}{4r^2}$$
$$F_2 = \left( \frac{1/4}{4} \right) \cdot G \frac{m_1 m_2}{r^2}$$
$$F_2 = \frac{1}{16} \cdot G \frac{m_1 m_2}{r^2}$$

### 4. Comparison
Since $F_1 = G \frac{m_1 m_2}{r^2}$, we can write:
$$F_2 = \frac{1}{16} F_1$$

**Final Answer:**
The gravitational force $F$ decreases by a factor of **$1/16$** (or $0.0625$).