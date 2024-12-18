### Solutions to Extremum Problems

---

### **1. Maximize the profit function**

The profit function is:
\[
P(u) = -2u^2 + 50u - 300
\]

The maximum (or minimum) of a quadratic function occurs at the vertex, given by:
\[
u = -\frac{b}{2a}\]
where the function is in the form \( P(u) = au^2 + bu + c \).

Here:
\[
a = -2, \quad b = 50, \quad c = -300
\]
\[
u = -\frac{50}{2(-2)} = \frac{50}{4} = 12.5
\]
### **Final Answer**

- **The number of units that maximize profit** is \( 12.5 \).
---

## **2.Maximizing the Area of a Rectangle with a Fixed Perimeter**

#### Problem Setup

A rectangle has a length \( L \) and a width \( W \).

The total string is the perimeter, which is given as 10 meters:

\[
2L + 2W = 10 \quad \text{(Constraint Equation)}
\]

The area of the rectangle is:

\[
A = L \times W \quad \text{(Objective Function)}
\]

We aim to maximize \( A \), the area.

#### Solve the Constraint Equation

From the constraint equation:

\[
2L + 2W = 10 \quad \Rightarrow \quad L + W = 5
\]

Rearrange to express \( W \) in terms of \( L \):

\[
W = 5 - L
\]

#### Substitute \( W \) into the Area Formula

Substitute \( W = 5 - L \) into \( A = L \times W \):

\[
A = L \times (5 - L)
\]

Simplify:

\[
A = 5L - L^2
\]

This is a quadratic function:

\[
A(L) = -L^2 + 5L
\]

#### Find the Value of \( L \) That Maximizes \( A \)

The quadratic equation \( A(L) = -L^2 + 5L \) is a parabola that opens downward (since the coefficient of \( L^2 \) is negative). Its maximum value occurs at the vertex.

The formula for the vertex of a parabola \( ax^2 + bx + c \) is:

\[
L = \frac{-b}{2a}
\]

Here:

\[
a = -1, \quad b = 5, \quad c = 0
\]

Substitute:

\[
L = \frac{-5}{2(-1)} = \frac{5}{2} = 2.5
\]

So:

\[
L = 2.5 \, \text{meters}
\]

#### Find \( W \)

Using \( W = 5 - L \):

\[
W = 5 - 2.5 = 2.5 \, \text{meters}
\]

#### Verify the Area

The dimensions \( L = 2.5 \, \text{m} \) and \( W = 2.5 \, \text{m} \) form a square, and the area is:

\[
A = L \times W = 2.5 \times 2.5 = 6.25
\]
### **Final Answer**

- **The largest area** is \( 6.25m^2 \).
---

### 3.Finding the Extremum of \[ f(x) = x^2 + 3x - 5 \]

The function \( f(x) = x^2 + 3x - 5 \) does not have a minimum because **a** is positive. This means the parabola opens upwards:
- The function has a **minimum** value.
- The function does **not** have a maximum because it extends to \( +\infty \).

The extremum of \( f(x) \) is found by taking its derivative and setting it equal to zero:
\[
f'(x) = 2x + 3.
\]
Setting \( f'(x) = 0 \):
\[
2x + 3 = 0 \quad \implies \quad x = -\frac{3}{2}.
\]

The second derivative is \( f''(x) = 2 \), which is positive, indicating a **minimum**.

Thus, the function has a **minimum** at \( x = -\frac{3}{2} \). Substituting \( x = -\frac{3}{2} \) into \( f(x) \):
\[
f\left(-\frac{3}{2}\right) = \left(-\frac{3}{2}\right)^2 + 3\left(-\frac{3}{2}\right) - 5 = \frac{9}{4} - \frac{9}{2} - 5 = -\frac{29}{4}.
\]

### **Final Answer**

- **Local maximum** is \( +\infty \).
- **Local minimum** at \( x = 3 \) with value \( y = 8 \).
---

### 4.Finding Extremum of \[ f(x) = \frac{x^2 + 2x + 1}{x - 1} \]

#### **Derivative**
We compute the derivative using the quotient rule:
\[
f'(x) = \frac{(x - 3)(x + 1)}{(x - 1)^2}.
\]

#### **Critical Points**
To find critical points, set \( f'(x) = 0 \):
\[
(x - 3)(x + 1) = 0.
\]
The critical points are:
\[
x = -1 \quad \text{and} \quad x = 3.
\]

#### **Classify the Critical Points**
Analyze the sign of \( f'(x) \):
- At \( x = -1 \), \( f'(x) \) changes from positive to negative → **local maximum**.
- At \( x = 3 \), \( f'(x) \) changes from negative to positive → **local minimum**.

#### **Evaluate \( f(x) \) at Critical Points**
- **At \( x = -1 \):**
  \[
f(-1) = \frac{(-1 + 1)^2}{-1 - 1} = \frac{0}{-2} = 0.
  \]
  **Value: \( f(-1) = 0 \)**.

- **At \( x = 3 \):**
  \[
f(3) = \frac{(3 + 1)^2}{3 - 1} = \frac{4^2}{2} = \frac{16}{2} = 8.
  \]
  **Value: \( f(3) = 8 \)**.

### **Final Answer**
- **Local maximum** at \( x = -1 \) with value \( y = 0 \).
- **Local minimum** at \( x = 3 \) with value \( y = 8 \).
---