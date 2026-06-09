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

### Problem 4
Evaluate using VBODMAS:
$$36 - [18 - \{14 - (15 - 4 \div 2 \times 2)\}]$$

### Problem 5
If $5^{a+b} = 3125$ and $5^{a-b} = 5$, find the value of $a^2 - b^2$.

### Problem 6
Simplify the expression:
$$\sqrt{5 + 2\sqrt{6}} + \sqrt{5 - 2\sqrt{6}}$$

### Problem 7
Evaluate the expression:
$$\frac{(2.3)^3 - 0.027}{(2.3)^2 + 0.69 + 0.09}$$

### Problem 8
Find the value of $x$ if:
$$\sqrt{2^x} = 64$$

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

### Solution 4
1. **Identify order of operations (VBODMAS)**:
   - Expression: $36 - [18 - \{14 - (15 - 4 \div 2 \times 2)\}]$.
2. **Solve the innermost parentheses `()`**:
   - Inside: $15 - 4 \div 2 \times 2$.
   - Perform Division first: $4 \div 2 = 2 \implies 15 - 2 \times 2$.
   - Perform Multiplication next: $2 \times 2 = 4 \implies 15 - 4 = 11$.
3. **Solve the braces `{}`**:
   - Inside: $14 - 11 = 3$.
4. **Solve the square brackets `[]`**:
   - Inside: $18 - 3 = 15$.
5. **Solve the final subtraction**:
   - $36 - 15 = 21$.
6. **Answer**: The value of the expression is **21**.

### Solution 5
1. **Analyze indices**:
   - We are given:
     - $5^{a+b} = 3125$. Since $3125 = 5^5$, we get $a + b = 5$.
     - $5^{a-b} = 5 = 5^1$, we get $a - b = 1$.
2. **Apply algebraic identity**:
   - We need to find $a^2 - b^2$.
   - Recall the identity: $a^2 - b^2 = (a + b)(a - b)$.
3. **Substitute the values**:
   - $a^2 - b^2 = 5 \times 1 = 5$.
4. **Answer**: The value of $a^2 - b^2$ is **5**.

### Solution 6
1. **Simplify each square root term**:
   - Let's express the terms inside the square root as perfect squares.
   - For $\sqrt{5 + 2\sqrt{6}}$:
     - We want to write $5 + 2\sqrt{6}$ in the form $(p + q)^2 = p^2 + q^2 + 2pq$.
     - Let $p = \sqrt{3}$ and $q = \sqrt{2}$.
     - Then $p^2 + q^2 = 3 + 2 = 5$, and $2pq = 2\sqrt{6}$.
     - Thus, $5 + 2\sqrt{6} = (\sqrt{3} + \sqrt{2})^2$.
     - So, $\sqrt{5 + 2\sqrt{6}} = \sqrt{3} + \sqrt{2}$.
   - Similarly, for $\sqrt{5 - 2\sqrt{6}}$:
     - $5 - 2\sqrt{6} = (\sqrt{3} - \sqrt{2})^2$.
     - So, $\sqrt{5 - 2\sqrt{6}} = \sqrt{3} - \sqrt{2}$ (since $\sqrt{3} > \sqrt{2}$).
2. **Add the simplified terms**:
   - $(\sqrt{3} + \sqrt{2}) + (\sqrt{3} - \sqrt{2}) = 2\sqrt{3}$.
3. **Answer**: The simplified value is **$2\sqrt{3}$**.

### Solution 7
1. **Identify algebraic pattern**:
   - Look at the numerator: $(2.3)^3 - 0.027$.
   - Since $0.027 = (0.3)^3$, the numerator is of the form $x^3 - y^3$, where $x = 2.3$ and $y = 0.3$.
   - Use identity: $x^3 - y^3 = (x - y)(x^2 + xy + y^2)$.
2. **Expand the terms**:
   - $(2.3)^3 - (0.3)^3 = (2.3 - 0.3)((2.3)^2 + 2.3 \times 0.3 + (0.3)^2)$.
   - Summing terms: $2.3 \times 0.3 = 0.69$, and $(0.3)^2 = 0.09$.
   - So the numerator $= 2.0 \times ((2.3)^2 + 0.69 + 0.09)$.
3. **Divide by the denominator**:
   - The expression is:
     $$\frac{2.0 \times ((2.3)^2 + 0.69 + 0.09)}{(2.3)^2 + 0.69 + 0.09} = 2.0$$
4. **Answer**: The value is **2** (or **2.0**).

### Solution 8
1. **Write with exponent notation**:
   - $\sqrt{2^x} = (2^x)^{1/2} = 2^{x/2}$.
2. **Convert the RHS to base 2**:
   - $64 = 2^6$.
3. **Equate the exponents**:
   - $2^{x/2} = 2^6 \implies \frac{x}{2} = 6 \implies x = 12$.
4. **Answer**: The value of $x$ is **12**.
