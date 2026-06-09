# Quantitative Aptitude: Simple & Compound Interest

## 1. Concept Definitions & Explanations

- **Principal ($P$)**: The money borrowed or lent.
- **Interest ($I$)**: The extra money paid for using the borrowed money.
- **Simple Interest (SI)**: Interest calculated only on the original principal amount. The interest remains constant every year.
- **Compound Interest (CI)**: Interest calculated on the principal plus the accumulated interest of previous periods. It is "interest on interest."
- **Amount ($A$)**: The total money returned at the end of the time period ($A = P + I$).

---

## 2. Key Formulas & Shortcuts

### Simple Interest
- **SI Formula**:
  $$\text{SI} = \frac{P \times R \times T}{100}$$
  *where $R = \text{Rate of interest per annum}$, $T = \text{Time in years}$.*
- **Amount ($A$)**:
  $$A = P + \text{SI} = P \left( 1 + \frac{RT}{100} \right)$$

### Compound Interest
- **Amount compounding annually**:
  $$A = P \left(1 + \frac{R}{100}\right)^n$$
  *where $n = \text{number of years}$.*
- **Amount compounding half-yearly**:
  $$A = P \left(1 + \frac{R/2}{100}\right)^{2n} = P \left(1 + \frac{R}{200}\right)^{2n}$$
- **Amount compounding quarterly**:
  $$A = P \left(1 + \frac{R/4}{100}\right)^{4n} = P \left(1 + \frac{R}{400}\right)^{4n}$$
- **CI Formula**:
  $$\text{CI} = A - P = P \left[ \left(1 + \frac{R}{100}\right)^n - 1 \right]$$

### Shortcuts: Difference Between CI and SI
- **For 2 Years**:
  $$\text{Difference } (D_2) = P \left( \frac{R}{100} \right)^2$$
- **For 3 Years**:
  $$\text{Difference } (D_3) = P \left( \frac{R}{100} \right)^2 \left( \frac{300 + R}{100} \right)$$

### Installments (Equal annual payments)
- **Simple Interest Installments**: If a debt of Rs. $A$ is cleared in $n$ equal annual installments of Rs. $x$ each at $R\%$ per annum:
  $$A = n \cdot x + \frac{x \cdot R}{100} \times \frac{n(n-1)}{2}$$
- **Compound Interest Installments**: If a borrowed sum $P$ is paid back in $n$ equal annual installments of Rs. $x$ each at $R\%$ per annum:
  $$P = \frac{x}{\left(1 + \frac{R}{100}\right)^1} + \frac{x}{\left(1 + \frac{R}{100}\right)^2} + \dots + \frac{x}{\left(1 + \frac{R}{100}\right)^n}$$

---

## 3. Practice Problems

### Problem 1
The difference between Simple Interest and Compound Interest on a certain sum of money for 2 years at 10% per annum is Rs. 150. Find the principal sum.

### Problem 2
A sum of money doubles itself in 5 years at a certain rate of compound interest. In how many years will it become 8 times of itself at the same rate of interest?

### Problem 3
A loan of Rs. 10,250 is to be paid back in two equal annual installments at 5% per annum compound interest. Calculate the value of each installment.

---

## 4. Step-by-Step Solutions

### Solution 1
1. **Identify given parameters**:
   - Time $n = 2$ years.
   - Rate $R = 10\%$.
   - Difference $D_2 = \text{Rs. } 150$.
2. **Apply the 2-year difference formula**:
   $$D_2 = P \left( \frac{R}{100} \right)^2$$
   $$150 = P \left( \frac{10}{100} \right)^2$$
   $$150 = P \left( \frac{1}{10} \right)^2$$
   $$150 = P \times \frac{1}{100}$$
   $$P = 150 \times 100 = 15,000$$
3. **Answer**: The principal sum is **Rs. 15,000**.

### Solution 2
1. **Use the Compound Interest growth logic**:
   - Under compound interest, if money becomes $k$ times in $t$ years, it becomes $k^m$ times in $m \times t$ years.
2. **Apply to the problem**:
   - $P \to 2P$ in 5 years. (Here $k = 2$, $t = 5$).
   - We want it to become 8 times, which is $8 = 2^3$ times. (Here $m = 3$).
3. **Calculate the time**:
   - Time required $= m \times t = 3 \times 5 = 15$ years.
4. **Answer**: The sum will become 8 times in **15 years**.

### Solution 3
1. **Identify given parameters**:
   - Borrowed sum $P = 10,250$.
   - Rate $R = 5\%$.
   - Number of installments $n = 2$.
2. **Apply the CI Installment Formula**:
   $$P = \frac{x}{\left(1 + \frac{R}{100}\right)} + \frac{x}{\left(1 + \frac{R}{100}\right)^2}$$
   - Since $1 + \frac{R}{100} = 1 + \frac{5}{100} = 1.05 = \frac{21}{20}$:
   $$10,250 = \frac{x}{21/20} + \frac{x}{(21/20)^2}$$
   $$10,250 = \frac{20x}{21} + \frac{400x}{441}$$
3. **Solve for $x$**:
   - Find common denominator 441:
   $$10,250 = \frac{20 \times 21x + 400x}{441} = \frac{420x + 400x}{441} = \frac{820x}{441}$$
   $$x = \frac{10,250 \times 441}{820}$$
   - Simplify: $\frac{10,250}{820} = 12.5$.
   $$x = 12.5 \times 441 = 5,512.50$$
4. **Answer**: Each installment is **Rs. 5,512.50**.
