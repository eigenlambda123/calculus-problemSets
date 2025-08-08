# **One-Sided Limits**

This section explains **one-sided limits**, which tell us how a function behaves as we approach a point **from only one side** — either from the left or the right. These are essential when dealing with piecewise functions or discontinuities.

---

### **What is a One-Sided Limit?**

A **one-sided limit** looks at what value $f(x)$ approaches as $x$ gets close to a number $a$, but **only from one direction**.

- **Left-hand limit**:
  $$
  \lim_{x \to a^-} f(x)
  $$
  This means: what does $f(x)$ approach as $x$ gets close to $a$ **from the left** (values less than $a$)?

- **Right-hand limit**:
  $$
  \lim_{x \to a^+} f(x)
  $$
  This means: what does $f(x)$ approach as $x$ gets close to $a$ **from the right** (values greater than $a$)?

---

### **When Does the Limit Exist?**

The full (two-sided) limit
$$
\lim_{x \to a} f(x)
$$
exists **only if**:

- The left-hand limit $\lim_{x \to a^-} f(x)$ **exists**, and
- The right-hand limit $\lim_{x \to a^+} f(x)$ **exists**, and
- **Both are equal**.

If the one-sided limits are different, the two-sided limit **does not exist**.

---

### **Step-by-Step: Evaluating a One-Sided Limit**

1. **Pick $x$-values** that approach $a$ from **only one side**:
   - Left: values less than $a$ (e.g., $1.9$, $1.99$, $1.999$ if $a = 2$)
   - Right: values greater than $a$ (e.g., $2.1$, $2.01$, $2.001$)

2. **Evaluate $f(x)$** for those values

3. **Look for a pattern** in the outputs:
   - If they’re getting close to a number $L$, then that is your one-sided limit.

---

### **Example:**

Let’s evaluate the one-sided limits of the piecewise function:

$$
f(x) = 
\begin{cases}
x^2 & \text{if } x < 1 \\
3 & \text{if } x = 1 \\
2x + 1 & \text{if } x > 1
\end{cases}
$$

#### Left-hand limit:
$$
\lim_{x \to 1^-} f(x) = \lim_{x \to 1^-} x^2 = 1
$$

#### Right-hand limit:
$$
\lim_{x \to 1^+} f(x) = \lim_{x \to 1^+} (2x + 1) = 3
$$

Since the left and right limits **aren’t equal**, the full limit **does not exist**:

$$
\lim_{x \to 1} f(x) \text{ does not exist}
$$

---

### Summary Table

| Concept                           | Description                                                    |
| --------------------------------- | -------------------------------------------------------------- |
| One-Sided Limit                   | What $f(x)$ approaches from **one** side of $a$                |
| Left-hand limit ($x \to a^-$)     | Approaching $a$ from values **less than** $a$                  |
| Right-hand limit ($x \to a^+$)    | Approaching $a$ from values **greater than** $a$               |
| Full limit exists if:             | Both one-sided limits exist and are **equal**                  |
| Piecewise functions               | Often require checking one-sided limits at breakpoints         |
| Discontinuities                   | Often revealed by unequal one-sided limits                     |

---

### Final Notes

* One-sided limits are crucial for:
  - Analyzing **piecewise** and **discontinuous** functions
  - Understanding **step changes** and **jumps**
* Always test both sides before concluding a full limit exists
* Graphs can help visualize one-sided behaviors clearly
