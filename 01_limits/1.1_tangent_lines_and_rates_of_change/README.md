# **Tangent Lines and Rates of Change**

This section showcase the key concepts covered in the topic **Tangent Lines and Rates of Change** — foundational ideas for differential calculus.

---

### **Tangent Lines: Intuition and Definition**

A **tangent line** to the curve $y = f(x)$ at a point $x = a$ is the line that just "touches" the graph at $(a, f(a))$ and has the same direction as the curve at that point.

Formally, the **slope of the tangent line** at $x = a$ is defined as the limit of the slope of secant lines:

$$\text{Slope of tangent line at } x = a = \lim_{x \to a} \frac{f(x) - f(a)}{x - a}$$

Alternatively, using a small increment $h$:

$$\lim_{h \to 0} \frac{f(a + h) - f(a)}{h}$$

This expression is also called the **derivative** of $f$ at $a$, denoted by $f'(a)$.

---

### **Secant Lines and Average Rate of Change**

A **secant line** passes through two points on the graph: $(a, f(a))$ and $(x, f(x))$. Its slope is:

$$\text{Average Rate of Change} = \frac{f(x) - f(a)}{x - a}$$

This gives the average change in $f$ over the interval $[a, x]$. As $x$ approaches $a$, the secant slope becomes the slope of the tangent line i.e., the instantaneous rate of change.

**So yes:**

> **The slope of the secant line = the average rate of change over an interval.**

---

### Instantaneous Rate of Change

The **instantaneous rate of change** of $f$ at $x = a$ is:

$$\lim_{x \to a} \frac{f(x) - f(a)}{x - a}$$

This limit, if it exists, gives the slope of the tangent line to the graph at $x = a$, and represents the instantaneous rate at which $f$ is changing.

---

### **Velocity as a Rate of Change**

If $s(t)$ represents the position of an object at time $t$, then:

- **Average velocity over** $[a, t]$ is:
$$\frac{s(t) - s(a)}{t - a}$$
- **Instantaneous velocity at** $t = a$ is:

$$\lim_{t \to a} \frac{s(t) - s(a)}{t - a}$$

This is essentially applying the tangent line idea to motion. Velocity is the **instantaneous rate of change of position**.

---

### Example: Velocity from a Table

Given a table of average velocities (A.V.) as $t$ gets closer to 10 from both sides:

|$t$|A.V.|$t$|A.V.|
|---|---|---|---|
|10.5|-79.11658419|9.5|-72.92931693|
|10.1|-76.61966704|9.9|-75.38216890|
|10.01|-76.06188418|9.99|-75.93813418|
|10.001|-76.00618759|9.999|-75.99381259|
|10.0001|-76.00061875|9.9999|-75.99938125|

We can observe:

- As $t \to 10^+$, A.V. → approx. $-76$
- As $t \to 10^-$, A.V. → approx. $-76$

Hence:

$$\lim_{t \to 10} \frac{s(t) - s(10)}{t - 10} \approx -76$$

This is the **instantaneous velocity** at $t = 10$.

---

### Summary of Important Concepts

| Concept                      | Description                                                                |
| ---------------------------- | -------------------------------------------------------------------------- |
| Tangent Line                 | Touches the curve at a point, has same direction as curve at that point.   |
| Secant Line                  | Passes through two points on the curve; used to approximate tangent slope. |
| Average Rate of Change       | Slope of the secant line: $\frac{f(x) - f(a)}{x - a}$                      |
| Instantaneous Rate of Change | Slope of the tangent line (limit of average rate): $f'(a)$                 |
| Velocity                     | Rate of change of position $s(t)$; instantaneous velocity is $s'(t)$       |


---

### Final Notes

- Tangent lines represent **instant change** — the very core of what calculus measures.
- We can interpret derivative at a point as:
    > "How fast is $f(x)$ changing _right now_ at $x = a$?"
- Velocity problems are one of the earliest real-world examples of this concept.

