# **The Limit**

This section outlines how to estimate a limit numerically by constructing a table of function values — a key approach when learning limits intuitively.

---

### **What is a Limit?**

The **limit** of a function \$f(x)\$ as \$x\$ approaches a number \$a\$ is the value that \$f(x)\$ gets closer and closer to as \$x\$ gets closer and closer to \$a\$ — from both sides.

Formally:

$$
\lim_{x \to a} f(x) = L
$$

This means: as \$x\$ gets arbitrarily close to \$a\$ (but not equal to \$a\$), the values of \$f(x)\$ approach \$L\$.

---

### **Numerical Estimation of Limits**

When a function is complicated, undefined at \$x = a\$, or difficult to simplify algebraically, we can **estimate the limit using a table of values**.

We approach \$a\$ from both sides:

* **From the left**: pick values less than \$a\$
* **From the right**: pick values greater than \$a\$

If the function values \$f(x)\$ from both directions get close to the same number \$L\$, then:

$$
\lim_{x \to a} f(x) = L
$$

---

### **Step-by-Step: Finding a Limit Using a Table**

1. **Pick values of \$x\$ that approach \$a\$ from both sides**
   Example: if \$a = 2\$, use values like

   * From the left: \$1.9\$, \$1.99\$, \$1.999\$
   * From the right: \$2.1\$, \$2.01\$, \$2.001\$

2. **Compute \$f(x)\$ for each value**

3. **Look for a trend**
   If \$f(x)\$ values approach the same number from both sides, that number is likely the limit.

4. **Conclude**
   If the values from both sides approach the same number \$L\$, write:

   $$
   \lim_{x \to a} f(x) = L
   $$

   If they approach different values, the limit **does not exist**.

---

### **Example:**

Let’s estimate:

$$
\lim_{x \to 2} \frac{x^2 - 4}{x - 2}
$$

Note: The function is undefined at \$x = 2\$ because the denominator becomes \$0\$.

#### Table of Values

| \$x\$ | \$f(x)\$                               |
| ----- | -------------------------------------- |
| 1.9   | \$\frac{(1.9)^2 - 4}{1.9 - 2} = -3.9\$ |
| 1.99  | \$\approx -3.99\$                      |
| 1.999 | \$\approx -3.999\$                     |
| 2.001 | \$\approx -4.001\$                     |
| 2.01  | \$\approx -4.01\$                      |
| 2.1   | \$\approx -4.1\$                       |

We observe:

* From the left: \$f(x) \to -4\$
* From the right: \$f(x) \to -4\$

Hence:

$$
\lim_{x \to 2} \frac{x^2 - 4}{x - 2} = -4
$$

---

### Summary Table

| Concept                          | Description                                                          |
| -------------------------------- | -------------------------------------------------------------------- |
| Limit                            | The value \$f(x)\$ approaches as \$x\$ gets close to \$a\$           |
| Table Method                     | Estimate limit by plugging in values near \$a\$                      |
| Left-hand limit (\$x \to a^-\$)  | Values of \$f(x)\$ as \$x\$ approaches \$a\$ from the left           |
| Right-hand limit (\$x \to a^+\$) | Values of \$f(x)\$ as \$x\$ approaches \$a\$ from the right          |
| Limit exists if:                 | Both left and right-hand limits exist and are equal                  |
| Undefined point                  | \$f(a)\$ may be undefined — we only care what happens as \$x \to a\$ |

---

### Final Notes

* This method is especially helpful when:

  * The function is not defined at \$x = a\$
  * You can’t simplify algebraically
* However, it gives **numerical estimates**, not exact values — useful for intuition, verification, or approximating when algebra is tricky.

