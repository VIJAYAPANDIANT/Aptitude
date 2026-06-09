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

### Problem 4
How many terms are there in the Arithmetic Progression: $20, 25, 30, \dots, 135$?

### Problem 5
Find the sum of all natural numbers between 100 and 300 which are exactly divisible by 4.

### Problem 6
If the 3rd and 6th terms of a Geometric Progression are 12 and 96 respectively, find the first term and the common ratio.

### Problem 7
Insert three arithmetic means between 3 and 19.

### Problem 8
Find the sum of the first 10 terms of the geometric series: $2, 6, 18, 54, \dots$

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

### Solution 4
1. **Identify the progression variables**:
   - First term $a = 20$.
   - Common difference $d = 25 - 20 = 5$.
   - Last term $t_n = 135$.
2. **Apply the $n^{\text{th}}$ term formula**:
   - $t_n = a + (n - 1)d$
   - $135 = 20 + (n - 1)5$
   - $115 = (n - 1)5 \implies n - 1 = 23 \implies n = 24$.
3. **Answer**: There are **24** terms in the progression.

### Solution 5
1. **Find the first and last term in the range**:
   - The natural numbers between 100 and 300 divisible by 4 are $104, 108, 112, \dots, 296$.
   - First term $a = 104$.
   - Common difference $d = 4$.
   - Last term $l = 296$.
2. **Find the number of terms ($n$)**:
   - $l = a + (n - 1)d \implies 296 = 104 + (n - 1)4$
   - $192 = 4(n - 1) \implies n - 1 = 48 \implies n = 49$.
3. **Calculate the sum ($S_n$)**:
   - $S_n = \frac{n}{2}(a + l) = \frac{49}{2}(104 + 296) = \frac{49}{2}(400) = 49 \times 200 = 9800$.
4. **Answer**: The sum of the numbers is **9,800**.

### Solution 6
1. **Set up the GP term equations**:
   - $t_n = a \cdot r^{n-1}$.
   - $t_3 = a \cdot r^2 = 12$.
   - $t_6 = a \cdot r^5 = 96$.
2. **Find common ratio $r$ by dividing the equations**:
   - $\frac{a \cdot r^5}{a \cdot r^2} = \frac{96}{12}$
   - $r^3 = 8 \implies r = 2$.
3. **Find the first term $a$**:
   - $a \cdot (2)^2 = 12 \implies 4a = 12 \implies a = 3$.
4. **Answer**: The first term is **3** and the common ratio is **2**.

### Solution 7
1. **Understand insertion of AMs**:
   - Let the three arithmetic means be $A_1, A_2, A_3$ between 3 and 19.
   - The sequence $3, A_1, A_2, A_3, 19$ forms an Arithmetic Progression.
2. **Find the common difference $d$**:
   - Total terms $n = 5$.
   - First term $a = 3$, last term $t_5 = 19$.
   - $t_5 = a + 4d \implies 19 = 3 + 4d \implies 16 = 4d \implies d = 4$.
3. **Calculate the means**:
   - $A_1 = a + d = 3 + 4 = 7$
   - $A_2 = a + 2d = 3 + 8 = 11$
   - $A_3 = a + 3d = 3 + 12 = 15$
4. **Answer**: The three arithmetic means are **7, 11, and 15**.

### Solution 8
1. **Identify the GP parameters**:
   - First term $a = 2$.
   - Common ratio $r = \frac{6}{2} = 3$.
   - Number of terms $n = 10$.
2. **Apply GP sum formula (since $r > 1$)**:
   - $S_n = \frac{a(r^n - 1)}{r - 1}$
   - $S_{10} = \frac{2(3^{10} - 1)}{3 - 1} = \frac{2(3^{10} - 1)}{2} = 3^{10} - 1$.
3. **Calculate $3^{10}$**:
   - $3^{10} = 59049$.
   - $S_{10} = 59049 - 1 = 59048$.
4. **Answer**: The sum of the first 10 terms is **59,048**.
