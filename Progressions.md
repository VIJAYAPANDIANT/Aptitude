# Quantitative Aptitude: Progressions

## 1. Concept Definitions & Explanations

- **Arithmetic Progression (AP)**: A sequence where the difference between consecutive terms is constant. E.g., $3, 7, 11, 15, \dots$ (common difference $d = 4$).
- **Geometric Progression (GP)**: A sequence where the ratio of consecutive terms is constant. E.g., $2, 6, 18, 54, \dots$ (common ratio $r = 3$).
- **Harmonic Progression (HP)**: A sequence of numbers whose reciprocals form an Arithmetic Progression. E.g., $\frac{1}{2}, \frac{1}{5}, \frac{1}{8}, \frac{1}{11}, \dots$ (reciprocals $2, 5, 8, 11, \dots$ form an AP).

---

## 2. Key Formulas & Shortcuts

### Arithmetic Progression (AP)
Let $a = \text{first term}$, $d = \text{common difference}$.
- **$n^{\text{th}}$ term ($t_n$)**:
  $$t_n = a + (n-1)d$$
- **Sum of first $n$ terms ($S_n$)**:
  $$S_n = \frac{n}{2}[2a + (n-1)d] = \frac{n}{2}(a + l)$$ *(where $l$ is the last term)*
- **Arithmetic Mean (AM)** between two numbers $a$ and $b$:
  $$\text{AM} = \frac{a + b}{2}$$

### Geometric Progression (GP)
Let $a = \text{first term}$, $r = \text{common ratio}$.
- **$n^{\text{th}}$ term ($t_n$)**:
  $$t_n = a \cdot r^{n-1}$$
- **Sum of first $n$ terms ($S_n$)**:
  $$S_n = \frac{a(r^n - 1)}{r - 1} \text{ (if } r > 1\text{), or } S_n = \frac{a(1 - r^n)}{1 - r} \text{ (if } r < 1\text{)}$$
- **Sum of an Infinite GP ($S_{\infty}$)** (for $-1 < r < 1$):
  $$S_{\infty} = \frac{a}{1 - r}$$
- **Geometric Mean (GM)** between two numbers $a$ and $b$:
  $$\text{GM} = \sqrt{a \cdot b}$$

### Harmonic Progression (HP)
- **$n^{\text{th}}$ term ($t_n$)**:
  $$t_n = \frac{1}{a + (n-1)d}$$ *(where $a$ and $d$ belong to the corresponding reciprocal AP)*
- **Harmonic Mean (HM)** between two numbers $a$ and $b$:
  $$\text{HM} = \frac{2ab}{a+b}$$

### Relation between Means (AM, GM, HM)
- **Mathematical Relation**:
  $$\text{GM}^2 = \text{AM} \times \text{HM}$$
- **Inequality**:
  $$\text{AM} \ge \text{GM} \ge \text{HM}$$ *(equality holds only if all numbers in the set are identical)*

---

## 3. Practice Problems

### Problem 1
Find the $15^{\text{th}}$ term of the Harmonic Progression: $\frac{1}{3}, \frac{1}{7}, \frac{1}{11}, \frac{1}{15}, \dots$

### Problem 2
Find the sum of the infinite geometric series: $9 - 3 + 1 - \frac{1}{3} + \dots$

### Problem 3
The arithmetic mean of two numbers is 10 and their geometric mean is 8. Find the numbers.

---

## 4. Step-by-Step Solutions

### Solution 1
1. **Identify the reciprocal sequence**:
   - The terms of the HP are $\frac{1}{3}, \frac{1}{7}, \frac{1}{11}, \frac{1}{15}, \dots$
   - The reciprocals are $3, 7, 11, 15, \dots$
2. **Verify and analyze the reciprocal AP**:
   - First term $a = 3$.
   - Common difference $d = 7 - 3 = 4$.
3. **Find the $15^{\text{th}}$ term of the AP**:
   $$t_{15} = a + (15-1)d = 3 + 14(4) = 3 + 56 = 59$$
4. **Reciprocate to find the HP term**:
   $$\text{HP term } t_{15} = \frac{1}{59}$$
5. **Answer**: The $15^{\text{th}}$ term is **$\frac{1}{59}$**.

### Solution 2
1. **Identify parameters of the GP**:
   - Series: $9, -3, 1, -\frac{1}{3}, \dots$
   - First term $a = 9$.
   - Common ratio $r = \frac{-3}{9} = -\frac{1}{3}$.
2. **Check for convergence**:
   - Since $|r| = |-\frac{1}{3}| = \frac{1}{3} < 1$, the infinite sum converges.
3. **Apply the Infinite GP Sum Formula**:
   $$S_{\infty} = \frac{a}{1 - r} = \frac{9}{1 - (-1/3)} = \frac{9}{1 + 1/3} = \frac{9}{4/3} = 9 \times \frac{3}{4} = \frac{27}{4} = 6.75$$
4. **Answer**: The sum of the infinite series is **$6.75$** (or $\frac{27}{4}$).

### Solution 3
1. **Set up the mean equations**:
   - Let the two numbers be $x$ and $y$.
   - $\text{AM} = \frac{x+y}{2} = 10 \implies x + y = 20$.
   - $\text{GM} = \sqrt{xy} = 8 \implies xy = 64$.
2. **Solve the quadratic equation system**:
   - From $x+y=20$, we can express $y = 20 - x$.
   - Substitute into $xy = 64$:
     $$x(20 - x) = 64$$
     $$20x - x^2 = 64 \implies x^2 - 20x + 64 = 0$$
3. **Factor the quadratic equation**:
   $$(x - 16)(x - 4) = 0 \implies x = 16 \text{ or } x = 4$$
   - If $x=16$, then $y=4$. If $x=4$, then $y=16$.
4. **Answer**: The two numbers are **16 and 4**.
