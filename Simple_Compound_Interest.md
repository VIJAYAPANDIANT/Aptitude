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

### Problem 4
A sum of money at simple interest amounts to Rs. 815 in 3 years and to Rs. 854 in 4 years. Find the principal sum.

### Problem 5
At what rate percent per annum compound interest will a sum of Rs. 1,000 amount to Rs. 1,331 in 3 years?

### Problem 6
Find the compound interest on Rs. 10,000 for 1 year at 20% per annum compounding half-yearly.

### Problem 7
A sum of Rs. 12,000 is deposited at simple interest of 10% per annum. Another sum of Rs. 15,000 is deposited at simple interest of 12% per annum. Find the total interest earned after 3 years.

### Problem 8
A sum of money triples itself in 10 years at simple interest. Find the rate of interest per annum.

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

### Solution 4
1. **Analyze simple interest behavior**:
   - Simple interest is constant every year.
   - Sum in 3 years $= \text{Principal} + \text{SI for 3 years} = 815$.
   - Sum in 4 years $= \text{Principal} + \text{SI for 4 years} = 854$.
2. **Calculate interest for 1 year**:
   - Interest for 1 year $= 854 - 815 = \text{Rs. } 39$.
3. **Calculate Principal ($P$)**:
   - Interest for 3 years $= 39 \times 3 = \text{Rs. } 117$.
   - Principal $= \text{Amount in 3 years} - \text{SI for 3 years}$
     $$P = 815 - 117 = \text{Rs. } 698$$
4. **Answer**: The principal sum is **Rs. 698**.

### Solution 5
1. **Set up the variables**:
   - Principal $P = 1,000$.
   - Amount $A = 1,331$.
   - Time $n = 3$ years.
2. **Use the compound interest amount formula**:
   $$A = P \left(1 + \frac{R}{100}\right)^n$$
   $$1331 = 1000 \left(1 + \frac{R}{100}\right)^3$$
   $$\frac{1331}{1000} = \left(1 + \frac{R}{100}\right)^3$$
3. **Solve for $R$**:
   - Note that $\frac{1331}{1000} = \left(\frac{11}{10}\right)^3$.
   - Taking cube root on both sides:
     $$\frac{11}{10} = 1 + \frac{R}{100} \implies 1.1 = 1 + \frac{R}{100}$$
     $$\frac{R}{100} = 0.1 \implies R = 10\%$$
4. **Answer**: The rate of interest is **10% per annum**.

### Solution 6
1. **Identify the parameters for semi-annual compounding**:
   - Principal $P = 10,000$.
   - Annual Rate $R = 20\%$, so rate per half-year $R' = \frac{20}{2} = 10\%$.
   - Time $n = 1$ year, which contains $t = 2$ half-years.
2. **Calculate the final amount**:
   $$A = P \left(1 + \frac{R'}{100}\right)^t = 10,000 \left(1 + \frac{10}{100}\right)^2$$
   $$A = 10,000 \times (1.1)^2 = 10,000 \times 1.21 = 12,100$$
3. **Calculate compound interest**:
   $$\text{CI} = A - P = 12,100 - 10,000 = 2,100$$
4. **Answer**: The compound interest is **Rs. 2,100**.

### Solution 7
1. **Find interest from first deposit**:
   - $P_1 = 12,000, R_1 = 10\%, T_1 = 3$.
   - $\text{SI}_1 = \frac{12,000 \times 10 \times 3}{100} = 3,600$.
2. **Find interest from second deposit**:
   - $P_2 = 15,000, R_2 = 12\%, T_2 = 3$.
   - $\text{SI}_2 = \frac{15,000 \times 12 \times 3}{100} = 5,400$.
3. **Sum the interests**:
   - $\text{Total Interest} = \text{SI}_1 + \text{SI}_2 = 3,600 + 5,400 = 9,000$.
4. **Answer**: The total interest earned is **Rs. 9,000**.

### Solution 8
1. **Set up the variables**:
   - Let principal be $P$.
   - Since the money triples, Amount $A = 3P$.
   - Simple Interest $\text{SI} = A - P = 3P - P = 2P$.
2. **Apply the SI formula**:
   - Time $T = 10$ years.
   - $\text{SI} = \frac{P \times R \times T}{100}$
     $$2P = \frac{P \times R \times 10}{100}$$
     $$2 = \frac{R}{10} \implies R = 20\%$$
3. **Answer**: The rate of interest is **20% per annum**.
