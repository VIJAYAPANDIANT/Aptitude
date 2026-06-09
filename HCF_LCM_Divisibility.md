# Quantitative Aptitude: HCF, LCM & Divisibility

## 1. Concept Definitions & Explanations

- **Highest Common Factor (HCF / GCD)**: The largest positive integer that divides two or more integers without leaving a remainder.
- **Least Common Multiple (LCM)**: The smallest positive integer that is divisible by two or more numbers.
- **Co-Prime Numbers**: Numbers whose HCF is $1$.

### Divisibility Rules
- **Divisibility by 2**: The unit digit must be even ($0, 2, 4, 6, 8$).
- **Divisibility by 3**: The sum of all digits must be divisible by 3.
- **Divisibility by 4**: The number formed by the last two digits must be divisible by 4.
- **Divisibility by 5**: The unit digit must be either 0 or 5.
- **Divisibility by 6**: The number must be divisible by both 2 and 3.
- **Divisibility by 8**: The number formed by the last three digits must be divisible by 8.
- **Divisibility by 9**: The sum of all digits must be divisible by 9.
- **Divisibility by 10**: The unit digit must be 0.
- **Divisibility by 11**: The difference between the sum of digits at odd positions and the sum of digits at even positions must be either 0 or a multiple of 11.

---

## 2. Key Formulas & Shortcuts

### Fundamental Formula
$$\text{Product of two numbers (a } \times \text{ b)} = \text{HCF}(a, b) \times \text{LCM}(a, b)$$
*Note: This formula holds true only for two numbers.*

### HCF & LCM of Fractions
- **HCF of Fractions** $= \frac{\text{HCF of Numerators}}{\text{LCM of Denominators}}$
- **LCM of Fractions** $= \frac{\text{LCM of Numerators}}{\text{HCF of Denominators}}$

### Remainder Applications
1. **Case 1**: Find the greatest number that divides $x, y, z$ leaving the same remainder $r$ in each case:
   $$\text{Required Number} = \text{HCF of } |x-y|, |y-z|, |z-x|$$
2. **Case 2**: Find the least number which when divided by $x, y, z$ leaves remainder $r$ in each case:
   $$\text{Required Number} = \text{LCM}(x, y, z) + r$$
3. **Case 3**: Find the least number which when divided by $x, y, z$ leaves remainders $a, b, c$ respectively:
   - Calculate $(x-a) = (y-b) = (z-c) = k$.
   $$\text{Required Number} = \text{LCM}(x, y, z) - k$$

---

## 3. Practice Problems

### Problem 1
Find the HCF and LCM of $\frac{2}{3}, \frac{8}{9},$ and $\frac{16}{81}$.

### Problem 2
Find the smallest 4-digit number which when divided by 12, 15, 18, and 27 leaves a remainder of 5 in each case.

### Problem 3
If the number $5432Y7$ is divisible by 9, find the digit $Y$.

### Problem 4
Three bells toll together at intervals of 9, 12, and 15 minutes respectively. If they toll together now, after how many hours will they toll together next?

### Problem 5
Find the greatest number that will divide 148, 246, and 623 leaving remainders 4, 6, and 11 respectively.

### Problem 6
What is the least number of square tiles required to pave the floor of a room of length 15 m 17 cm and breadth 9 m 2 cm?

### Problem 7
If a number $34X68Y$ is divisible by 90, find the values of $X$ and $Y$.

### Problem 8
The HCF and LCM of two numbers are 12 and 720 respectively. If one of the numbers is 144, find the other number.

---

## 4. Step-by-Step Solutions

### Solution 1
1. **Identify fractions**: $\frac{2}{3}, \frac{8}{9}, \frac{16}{81}$.
2. **To find HCF**:
   $$\text{HCF} = \frac{\text{HCF}(2, 8, 16)}{\text{LCM}(3, 9, 81)}$$
   - HCF of numerators (2, 8, 16) is $2$.
   - LCM of denominators (3, 9, 81) is $81$.
   - Hence, $\text{HCF} = \frac{2}{81}$.
3. **To find LCM**:
   $$\text{LCM} = \frac{\text{LCM}(2, 8, 16)}{\text{HCF}(3, 9, 81)}$$
   - LCM of numerators (2, 8, 16) is $16$.
   - HCF of denominators (3, 9, 81) is $3$.
   - Hence, $\text{LCM} = \frac{16}{3}$.
4. **Answer**: $\text{HCF} = \frac{2}{81}$, $\text{LCM} = \frac{16}{3}$.

### Solution 2
1. **Find LCM of divisors**:
   - Divisors are 12, 15, 18, and 27.
   - Prime factorization:
     - $12 = 2^2 \times 3$
     - $15 = 3 \times 5$
     - $18 = 2 \times 3^2$
     - $27 = 3^3$
   - $\text{LCM} = 2^2 \times 3^3 \times 5 = 4 \times 27 \times 5 = 540$.
2. **Find the smallest 4-digit number**:
   - The smallest 4-digit number is 1000.
   - Divide 1000 by 540: $1000 \div 540 = 1$ with a remainder of 460.
   - The smallest 4-digit multiple of 540 is: $1000 + (540 - 460) = 1080$.
3. **Apply the remainder condition**:
   - The required number leaves remainder 5.
   - $\text{Required Number} = 1080 + 5 = 1085$.
4. **Answer**: The number is **1085**.

### Solution 3
1. **Apply the Divisibility Rule for 9**:
   - Sum of digits $= 5 + 4 + 3 + 2 + Y + 7 = 21 + Y$.
2. **Find $Y$**:
   - For $(21 + Y)$ to be divisible by 9, the closest multiple of 9 greater than or equal to 21 is 27.
   - $21 + Y = 27 \implies Y = 6$.
3. **Answer**: The digit $Y$ is **6**.

### Solution 4
1. **Find the LCM of the toll intervals**:
   - The intervals are 9, 12, and 15 minutes.
   - Prime Factorization:
     - $9 = 3^2$
     - $12 = 2^2 \times 3$
     - $15 = 3 \times 5$
   - $\text{LCM} = 2^2 \times 3^2 \times 5 = 4 \times 9 \times 5 = 180$ minutes.
2. **Convert minutes to hours**:
   - $180 \div 60 = 3$ hours.
3. **Answer**: The bells will toll together next after **3 hours**.

### Solution 5
1. **Formulate the target values**:
   - The greatest divisor must divide $148, 246, 623$ leaving remainders $4, 6, 11$.
   - Thus, the divisor exactly divides $(148 - 4) = 144$, $(246 - 6) = 240$, and $(623 - 11) = 612$.
2. **Find the HCF of the differences**:
   - $\text{HCF}(144, 240, 612)$
   - Prime factorizations:
     - $144 = 2^4 \times 3^2$
     - $240 = 2^4 \times 3^1 \times 5$
     - $612 = 2^2 \times 3^2 \times 17$
   - Common factors are $2^2 \times 3^1 = 12$.
3. **Answer**: The greatest number is **12**.

### Solution 6
1. **Convert units to centimeters**:
   - $\text{Length} = 15 \text{ m } 17 \text{ cm} = 1517$ cm.
   - $\text{Breadth} = 9 \text{ m } 2 \text{ cm} = 902$ cm.
2. **Find the largest square tile size (HCF)**:
   - Use Euclidean Algorithm for $\text{HCF}(1517, 902)$:
     - $1517 = 902 \times 1 + 615$
     - $902 = 615 \times 1 + 287$
     - $615 = 287 \times 2 + 41$
     - $287 = 41 \times 7 + 0$
   - $\text{HCF} = 41$ cm. So, the side of the largest possible square tile is 41 cm.
3. **Calculate total number of tiles**:
   - $\text{Number of tiles} = \frac{\text{Area of Floor}}{\text{Area of 1 Tile}} = \frac{1517 \times 902}{41 \times 41}$
   - Simplify: $\frac{1517}{41} = 37$ and $\frac{902}{41} = 22$.
   - $\text{Tiles} = 37 \times 22 = 814$.
4. **Answer**: The least number of square tiles required is **814**.

### Solution 7
1. **Analyze Divisibility by 90**:
   - A number is divisible by 90 if it is divisible by both 9 and 10 (since 9 and 10 are co-prime).
2. **Apply Divisibility by 10**:
   - For $34X68Y$ to be divisible by 10, the unit digit $Y$ must be $0$.
3. **Apply Divisibility by 9**:
   - For $34X680$ to be divisible by 9, the sum of the digits must be divisible by 9:
     $$\text{Sum} = 3 + 4 + X + 6 + 8 + 0 = 21 + X$$
   - The closest multiple of 9 greater than or equal to 21 is 27.
     $$21 + X = 27 \implies X = 6$$
4. **Answer**: $X = 6$ and $Y = 0$.

### Solution 8
1. **Apply the fundamental property of numbers**:
   $$\text{First Number} \times \text{Second Number} = \text{HCF} \times \text{LCM}$$
2. **Substitute given values**:
   - Let the second number be $N$.
     $$144 \times N = 12 \times 720$$
3. **Solve for $N$**:
     $$N = \frac{12 \times 720}{144} = \frac{720}{12} = 60$$
4. **Answer**: The other number is **60**.
