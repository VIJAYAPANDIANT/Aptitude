# Quantitative Aptitude: Number System

## 1. Concept Definitions & Explanations

- **Natural Numbers ($\mathbb{N}$)**: Counting numbers starting from 1. E.g., $1, 2, 3, 4, \dots$
- **Whole Numbers ($\mathbb{W}$)**: Natural numbers including zero. E.g., $0, 1, 2, 3, \dots$
- **Integers ($\mathbb{Z}$)**: Complete numbers (both positive, negative, and zero). E.g., $\dots, -3, -2, -1, 0, 1, 2, 3, \dots$
- **Rational Numbers**: Numbers that can be expressed in the form $\frac{p}{q}$ where $p$ and $q$ are integers and $q \neq 0$. E.g., $\frac{2}{3}, -5, 0.75$.
- **Irrational Numbers**: Numbers that cannot be expressed in the form $\frac{p}{q}$. E.g., $\sqrt{2}, \pi, e$.
- **Real Numbers**: The set of all rational and irrational numbers.
- **Prime Numbers**: Numbers greater than 1 that have only two factors: 1 and themselves. E.g., $2, 3, 5, 7, 11, 13, \dots$ (Note: 2 is the only even prime number).
- **Composite Numbers**: Numbers greater than 1 that are not prime. E.g., $4, 6, 8, 9, \dots$ (Note: 1 is neither prime nor composite).
- **Co-prime Numbers**: Two numbers are co-prime if their Highest Common Factor (HCF) is 1. E.g., $(8, 15)$.

---

## 2. Key Formulas & Shortcuts

### Sum of Series
1. **Sum of first $n$ natural numbers**:
   $$S_n = \frac{n(n+1)}{2}$$
2. **Sum of squares of first $n$ natural numbers**:
   $$S_n^2 = \frac{n(n+1)(2n+1)}{6}$$
3. **Sum of cubes of first $n$ natural numbers**:
   $$S_n^3 = \left[\frac{n(n+1)}{2}\right]^2$$
4. **Sum of first $n$ odd numbers**:
   $$S_{odd} = n^2$$
5. **Sum of first $n$ even numbers**:
   $$S_{even} = n(n+1)$$

### Progressions
- **Arithmetic Progression (AP)**:
  - $n^{\text{th}}$ term: $T_n = a + (n-1)d$
  - Sum of $n$ terms: $S_n = \frac{n}{2}[2a + (n-1)d] = \frac{n}{2}(a + l)$
  - *where $a = \text{first term}$, $d = \text{common difference}$, $l = \text{last term}$.*

- **Geometric Progression (GP)**:
  - $n^{\text{th}}$ term: $T_n = a \cdot r^{n-1}$
  - Sum of $n$ terms ($r \neq 1$): $S_n = \frac{a(r^n - 1)}{r - 1}$ for $r > 1$, or $S_n = \frac{a(1 - r^n)}{1 - r}$ for $r < 1$.
  - Sum of infinite terms ($|r| < 1$): $S_{\infty} = \frac{a}{1 - r}$
  - *where $a = \text{first term}$, $r = \text{common ratio}$.*

### Number of Factors
If a number $N$ is written in its prime factorized form:
$$N = p^a \cdot q^b \cdot r^c \dots$$ (where $p, q, r$ are prime numbers), then:
- **Total number of factors** $= (a+1)(b+1)(c+1)\dots$

---

## 3. Practice Problems

### Problem 1
Find the unit digit of $(287)^{562} \times (124)^{321}$.

### Problem 2
Find the sum of all natural numbers between 100 and 300 which are exactly divisible by 4.

### Problem 3
Find the total number of factors of 360 (excluding 1 and the number itself).

### Problem 4
A number when divided by 899 leaves a remainder 63. What will be the remainder when the same number is divided by 29?

### Problem 5
Find the remainder when $2^{31}$ is divided by 5.

### Problem 6
Find the number of zeroes at the end of the product $1 \times 2 \times 3 \times \dots \times 100$ (or $100!$).

### Problem 7
Find the sum of all terms of the infinite geometric series: $1 + \frac{1}{3} + \frac{1}{9} + \frac{1}{27} + \dots$

### Problem 8
The sum of a two-digit number and the number obtained by reversing its digits is 121. What is the sum of the digits of the number?

---

## 4. Step-by-Step Solutions

### Solution 1
1. **Analyze the cycles of unit digits**:
   - For base ending in $7$ ($287$): The unit digit cyclicity of $7$ is 4 ($7^1=7$, $7^2=9$, $7^3=3$, $7^4=1$, repeating).
     - Divide the exponent $562$ by $4$: $562 \div 4 = 140$ with a remainder of $2$.
     - Therefore, the unit digit of $(287)^{562}$ is same as $7^2$, which is $9$.
   - For base ending in $4$ ($124$): The unit digit cyclicity of $4$ is 2 ($4^{\text{odd}} = 4$, $4^{\text{even}} = 6$).
     - The exponent $321$ is odd.
     - Therefore, the unit digit of $(124)^{321}$ is $4$.
2. **Combine the results**:
   - Multiply the individual unit digits: $9 \times 4 = 36$.
   - The unit digit of the final product is **6**.

### Solution 2
1. **Identify the terms**:
   - The first number after 100 divisible by 4 is $104$. (Since "between" excludes 100 and 300).
   - The last number before 300 divisible by 4 is $296$.
   - This forms an Arithmetic Progression (AP) with first term $a = 104$, last term $l = 296$, and common difference $d = 4$.
2. **Find the number of terms ($n$)**:
   $$l = a + (n-1)d$$
   $$296 = 104 + (n-1)4$$
   $$192 = (n-1)4$$
   $$n-1 = 48 \implies n = 49$$
3. **Calculate the sum ($S_n$)**:
   $$S_n = \frac{n}{2}(a + l)$$
   $$S_{49} = \frac{49}{2}(104 + 296) = \frac{49}{2}(400) = 49 \times 200 = 9800$$
4. **Answer**: The sum is **9800**.

### Solution 3
1. **Prime Factorization of 360**:
   $$360 = 2^3 \times 3^2 \times 5^1$$
2. **Calculate Total Number of Factors**:
   $$\text{Total Factors} = (3 + 1)(2 + 1)(1 + 1) = 4 \times 3 \times 2 = 24$$
3. **Exclude 1 and the number itself**:
   $$\text{Required Factors} = 24 - 2 = 22$$
4. **Answer**: The number of factors is **22**.

### Solution 4
1. **Represent the number**:
   - Let the number be $N = 899k + 63$, where $k$ is an integer.
2. **Analyze divisibility by 29**:
   - Check if 899 is divisible by 29: $899 \div 29 = 31$.
   - Since 899 is a multiple of 29, the term $899k$ leaves a remainder of 0 when divided by 29.
3. **Find the remainder of the constant term**:
   - Divide 63 by 29:
     $$63 = 29 \times 2 + 5$$
   - The remainder is 5.
4. **Answer**: The remainder is **5**.

### Solution 5
1. **Analyze unit/remainder cycles**:
   - We need to find $2^{31} \pmod 5$.
   - Calculate powers of 2 modulo 5:
     - $2^1 \equiv 2 \pmod 5$
     - $2^2 \equiv 4 \pmod 5$
     - $2^3 \equiv 8 \equiv 3 \pmod 5$
     - $2^4 \equiv 16 \equiv 1 \pmod 5$
   - The cycle of remainders is $[2, 4, 3, 1]$ of length 4.
2. **Divide exponent by cycle length**:
     $$31 = 4 \times 7 + 3$$
   - The remainder is 3.
3. **Determine the result**:
   - $2^{31} \equiv 2^3 \equiv 3 \pmod 5$.
4. **Answer**: The remainder is **3**.

### Solution 6
1. **Identify the source of zeroes**:
   - Zeroes at the end of a factorial product are formed by the factors of 10, which are $2 \times 5$.
   - In any factorial, the prime factor 2 occurs more frequently than 5. Thus, the number of zeroes is determined by the number of times 5 divides $100!$.
2. **Apply Legendre's Formula**:
   $$\text{Number of factors of 5} = \lfloor \frac{100}{5} \rfloor + \lfloor \frac{100}{25} \rfloor + \lfloor \frac{100}{125} \rfloor + \dots$$
   $$\text{Number of factors of 5} = 20 + 4 + 0 = 24$$
3. **Answer**: The number of trailing zeroes is **24**.

### Solution 7
1. **Identify type of series**:
   - The series is $1 + \frac{1}{3} + \frac{1}{9} + \frac{1}{27} + \dots$
   - This is an infinite Geometric Progression (GP) where:
     - First term $a = 1$
     - Common ratio $r = \frac{1}{3}$
2. **Check convergence**:
   - Since $|r| = \frac{1}{3} < 1$, the series converges.
3. **Apply the sum formula**:
   $$S_{\infty} = \frac{a}{1 - r}$$
   $$S_{\infty} = \frac{1}{1 - 1/3} = \frac{1}{2/3} = \frac{3}{2} = 1.5$$
4. **Answer**: The sum of the series is **1.5** (or $\frac{3}{2}$).

### Solution 8
1. **Represent the two-digit number**:
   - Let the tens digit be $x$ and the units digit be $y$.
   - The value of the number is $10x + y$.
2. **Set up the reversed number**:
   - Reversing the digits gives the number $10y + x$.
3. **Form the equation**:
   - The sum of the numbers is 121:
     $$(10x + y) + (10y + x) = 121$$
     $$11x + 11y = 121$$
     $$11(x + y) = 121 \implies x + y = 11$$
4. **Answer**: The sum of the digits is **11**.
