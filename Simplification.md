# Quantitative Aptitude: Simplification

## 1. VBODMAS Rule

When solving mathematical expressions, operations must be performed in the following order of precedence:

1. **V - Vinculum (Bar Bracket)**: Represented by a line over terms, e.g., $\overline{3 - 2}$. Solve this first.
2. **B - Brackets**: Solve in order: Parentheses `()`, Braces `{}` then Square Brackets `[]`.
3. **O - Of**: Equivalent to multiplication but evaluated before division. E.g., $10 \text{ of } 5 = 10 \times 5 = 50$.
4. **D - Division** ($/$)
5. **M - Multiplication** ($\times$)
6. **A - Addition** ($+$)
7. **S - Subtraction** ($-$)

---

## 2. Laws of Indices & Surds

### Laws of Indices
If $a, b$ are real numbers and $m, n$ are rational numbers:
1. $a^m \times a^n = a^{m+n}$
2. $\frac{a^m}{a^n} = a^{m-n}$
3. $(a^m)^n = a^{mn}$
4. $(ab)^n = a^n \cdot b^n$
5. $\left( \frac{a}{b} \right)^n = \frac{a^n}{b^n}$
6. $a^{-n} = \frac{1}{a^n}$
7. $a^0 = 1$ (for $a \neq 0$)

### Laws of Surds
A surd is an irrational root of a rational number, e.g., $\sqrt{2}, \sqrt[3]{5}$.
1. $\sqrt[n]{a} = a^{1/n}$
2. $\sqrt[n]{ab} = \sqrt[n]{a} \cdot \sqrt[n]{b}$
3. $\sqrt[n]{\frac{a}{b}} = \frac{\sqrt[n]{a}}{\sqrt[n]{b}}$
4. $(\sqrt[n]{a})^n = a$
5. $\sqrt[m]{\sqrt[n]{a}} = \sqrt[mn]{a}$

### Conjugate and Rationalization
To rationalize a denominator of the form $a \pm \sqrt{b}$, multiply the numerator and denominator by its conjugate $a \mp \sqrt{b}$:
$$\frac{1}{a + \sqrt{b}} = \frac{a - \sqrt{b}}{(a + \sqrt{b})(a - \sqrt{b})} = \frac{a - \sqrt{b}}{a^2 - b}$$

---

## 3. Practice Problems

### Problem 1
Simplify the expression:
$$108 \div 36 \text{ of } \frac{1}{4} + \frac{2}{5} \times 3\frac{1}{4}$$

### Problem 2
Find the value of $x$ if:
$$3^{x-1} + 3^{x+1} = 90$$

### Problem 3
Simplify by rationalizing:
$$\frac{5 + \sqrt{3}}{5 - \sqrt{3}}$$

---

## 4. Step-by-Step Solutions

### Solution 1
1. **Convert mixed fraction**:
   - $3\frac{1}{4} = \frac{13}{4}$.
   - The expression becomes: $108 \div 36 \text{ of } \frac{1}{4} + \frac{2}{5} \times \frac{13}{4}$.
2. **Evaluate "of" first**:
   - $36 \text{ of } \frac{1}{4} = 36 \times \frac{1}{4} = 9$.
   - The expression becomes: $108 \div 9 + \frac{2}{5} \times \frac{13}{4}$.
3. **Evaluate Division**:
   - $108 \div 9 = 12$.
   - The expression becomes: $12 + \frac{2}{5} \times \frac{13}{4}$.
4. **Evaluate Multiplication**:
   - $\frac{2}{5} \times \frac{13}{4} = \frac{1 \times 13}{5 \times 2} = \frac{13}{10} = 1.3$.
5. **Evaluate Addition**:
   - $12 + 1.3 = 13.3$ (or $13\frac{3}{10}$).
6. **Answer**: The simplified value is **$13.3$**.

### Solution 2
1. **Factor out $3^{x-1}$ from the left side**:
   - Rewrite terms: $3^{x+1} = 3^{x-1} \times 3^2 = 9 \times 3^{x-1}$.
   $$3^{x-1} + 9 \cdot 3^{x-1} = 90$$
   $$3^{x-1} (1 + 9) = 90$$
   $$10 \cdot 3^{x-1} = 90$$
2. **Divide by 10**:
   $$3^{x-1} = 9$$
3. **Express 9 as base 3**:
   $$3^{x-1} = 3^2$$
4. **Equate the exponents**:
   $$x - 1 = 2 \implies x = 3$$
5. **Answer**: The value of $x$ is **3**.

### Solution 3
1. **Identify conjugate**:
   - Denominator is $5 - \sqrt{3}$.
   - Conjugate is $5 + \sqrt{3}$.
2. **Multiply numerator and denominator by the conjugate**:
   $$\frac{5 + \sqrt{3}}{5 - \sqrt{3}} \times \frac{5 + \sqrt{3}}{5 + \sqrt{3}} = \frac{(5 + \sqrt{3})^2}{5^2 - (\sqrt{3})^2}$$
3. **Expand the terms**:
   - Numerator: $(5 + \sqrt{3})^2 = 5^2 + (\sqrt{3})^2 + 2(5)(\sqrt{3}) = 25 + 3 + 10\sqrt{3} = 28 + 10\sqrt{3}$.
   - Denominator: $25 - 3 = 22$.
4. **Simplify the fraction**:
   $$\frac{28 + 10\sqrt{3}}{22} = \frac{2(14 + 5\sqrt{3})}{22} = \frac{14 + 5\sqrt{3}}{11}$$
5. **Answer**: The simplified value is **$\frac{14 + 5\sqrt{3}}{11}$**.
