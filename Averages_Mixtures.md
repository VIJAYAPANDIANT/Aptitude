# Quantitative Aptitude: Averages & Mixtures

## 1. Concept Definitions & Explanations

- **Average (Arithmetic Mean)**: The sum of a set of values divided by the total number of values.
- **Weighted Average**: The average of a set of values where each value is assigned a different weight indicating its importance.
- **Alligation**: A rule that enables us to find the ratio in which two or more ingredients at given prices/strengths must be mixed to produce a mixture of a desired price/strength.

---

## 2. Key Formulas & Shortcuts

### Averages
- **Basic Formula**:
  $$\text{Average} = \frac{\text{Sum of Observations}}{\text{Number of Observations}}$$
- **Weighted Average**:
  $$\text{Weighted Average} = \frac{w_1 \cdot x_1 + w_2 \cdot x_2 + \dots + w_k \cdot x_k}{w_1 + w_2 + \dots + w_k}$$
  *where $w$ represents weights and $x$ represents corresponding values.*
- **Consecutive Numbers Average**:
  - The average of an Arithmetic Progression series is exactly equal to the middle term (if odd number of terms) or the average of the two middle terms (if even number of terms).
  - Also: $\text{Average} = \frac{\text{First Term} + \text{Last Term}}{2}$.

### Rule of Alligation
Let Cost Price of Cheaper ingredient be $C$, Cost Price of Dearer ingredient be $D$, and the Mean Price of the mixture be $M$.
$$\frac{\text{Quantity of Cheaper}}{\text{Quantity of Dearer}} = \frac{D - M}{M - C}$$

```
  Cheaper CP (C)          Dearer CP (D)
             \          /
              \        /
             Mean CP (M)
              /        \
             /          \
         (D - M)       (M - C)
```
Ratio of Cheaper to Dearer $= (D - M) : (M - C)$.

### Repeated Dilution (Liquid Replacement)
If a vessel contains $x$ units of a pure liquid, and $y$ units are drawn off and replaced by water, and this operation is repeated $n$ times:
$$\text{Pure Liquid remaining after } n \text{ operations} = x \left( 1 - \frac{y}{x} \right)^n$$

---

## 3. Practice Problems

### Problem 1
The average age of a class of 30 students is 15 years. If the teacher's age is included, the average age increases by 1 year. Find the age of the teacher.

### Problem 2
In what ratio must a grocer mix tea costing Rs. 180 per kg with tea costing Rs. 200 per kg so that the mixture is worth Rs. 188 per kg?

### Problem 3
A container contains 80 liters of pure milk. From this container, 8 liters of milk was taken out and replaced with water. This process was repeated two more times. How much pure milk is left in the container now?

### Problem 4
The average of 11 numbers is 60. If the average of the first six numbers is 58 and that of the last six numbers is 63, find the sixth number.

### Problem 5
A batsman has a certain average of runs for 11 innings. In the 12th inning, he makes a score of 90 runs and thereby increases his average by 5. Find his average after the 12th inning.

### Problem 6
A vessel contains 60 liters of a mixture of milk and water in the ratio $3 : 2$. How much water (in liters) must be added to this mixture so that the ratio of milk to water becomes $1 : 1$?

### Problem 7
In what ratio must water be mixed with milk to gain $16\frac{2}{3}\%$ by selling the mixture at cost price?

### Problem 8
A merchant has 1000 kg of sugar, part of which he sells at 8% profit and the rest at 18% profit. He gains 14% on the whole. Find the quantity sold at 18% profit.

### Problem 9
A library has an average of 510 visitors on Sundays and 240 on other days. Find the average number of visitors per day in a month of 30 days beginning with a Sunday.

### Problem 10
A vessel contains 40 liters of milk. 4 liters of milk is taken out and replaced by water. This process is repeated one more time. Find the ratio of milk to water in the final mixture.

---

## 4. Step-by-Step Solutions

### Solution 1
1. **Method 1: Sum Method**:
   - Total age of 30 students $= 30 \times 15 = 450$ years.
   - Total people including teacher $= 31$.
   - New average $= 15 + 1 = 16$ years.
   - Total age of 31 people $= 31 \times 16 = 496$ years.
   - Teacher's age $= 496 - 450 = 46$ years.
2. **Method 2: Deviation Shortcut**:
   - Teacher's Age $= \text{Old Average} + (\text{New Count} \times \text{Increase in Average})$
   - Teacher's Age $= 15 + (31 \times 1) = 15 + 31 = 46$ years.
3. **Answer**: The teacher's age is **46 years**.

### Solution 2
1. **Identify the variables**:
   - Cheaper CP ($C$) $= 180$
   - Dearer CP ($D$) $= 200$
   - Mean CP ($M$) $= 188$
2. **Apply the Rule of Alligation**:
   $$\frac{\text{Quantity of Cheaper}}{\text{Quantity of Dearer}} = \frac{D - M}{M - C} = \frac{200 - 188}{188 - 180} = \frac{12}{8} = \frac{3}{2}$$
3. **Answer**: The grocer must mix them in the ratio **$3 : 2$**.

### Solution 3
1. **Identify parameters**:
   - Initial quantity of pure milk $x = 80$ liters.
   - Quantity replaced in each step $y = 8$ liters.
   - Number of times process is performed $n = 3$ (1 initial + 2 repeats).
2. **Apply the Dilution Formula**:
   $$\text{Remaining Milk} = x \left( 1 - \frac{y}{x} \right)^n$$
   $$\text{Remaining Milk} = 80 \left( 1 - \frac{8}{80} \right)^3 = 80 \left( 1 - 0.1 \right)^3 = 80 \left( 0.9 \right)^3$$
   $$\text{Remaining Milk} = 80 \times 0.729 = 58.32 \text{ liters}$$
3. **Answer**: There are **58.32 liters** of pure milk left.

### Solution 4
1. **Understand the terms**:
   - Total sum of 11 numbers $= 11 \times 60 = 660$.
   - Sum of first 6 numbers $= 6 \times 58 = 348$.
   - Sum of last 6 numbers $= 6 \times 63 = 378$.
2. **Find the overlap**:
   - In the sum of the first six and last six numbers, the sixth number is counted twice.
   - Sum of (first 6 + last 6) $= 348 + 378 = 726$.
   - Sixth number $= \text{Sum of 12 numbers} - \text{Sum of 11 numbers} = 726 - 660 = 66$.
3. **Answer**: The sixth number is **66**.

### Solution 5
1. **Set up the variables**:
   - Let the average for 11 innings be $x$.
   - Total runs in 11 innings $= 11x$.
2. **Formulate equation with 12th inning**:
   - Score in 12th inning $= 90$ runs.
   - Total runs after 12 innings $= 11x + 90$.
   - New average after 12 innings $= x + 5$.
   - Total runs after 12 innings can also be written as $= 12(x + 5)$.
   - Therefore, $11x + 90 = 12(x + 5)$.
3. **Solve for $x$**:
   - $11x + 90 = 12x + 60$
   - $x = 30$ (average of 11 innings).
4. **Calculate new average**:
   - Average after 12th inning $= 30 + 5 = 35$ runs.
5. **Answer**: His average after the 12th inning is **35**.

### Solution 6
1. **Find initial quantities**:
   - Total mixture $= 60$ liters.
   - Ratio of milk to water $= 3 : 2$.
   - Quantity of milk $= 60 \times \frac{3}{5} = 36$ liters.
   - Quantity of water $= 60 \times \frac{2}{5} = 24$ liters.
2. **Formulate the target ratio**:
   - Let $w$ liters of water be added.
   - New quantity of water $= 24 + w$.
   - New ratio of milk to water $= 1 : 1$.
   - Therefore, $\frac{36}{24 + w} = \frac{1}{1} \implies 36 = 24 + w \implies w = 12$ liters.
3. **Answer**: The amount of water to be added is **12 liters**.

### Solution 7
1. **Understand CP and Selling Price**:
   - Let the Cost Price (CP) of 1 liter of pure milk be Rs. 1.
   - To gain $16\frac{2}{3}\%$ ($=\frac{50}{3}\% = \frac{1}{6}$ of CP) by selling at CP (Rs. 1 per liter):
     - The Selling Price (SP) of the mixture is Rs. 1 per liter.
     - Therefore, the CP of the mixture must be $\frac{\text{SP}}{1 + \text{Gain}\%} = \frac{1}{1 + 1/6} = \text{Rs. } \frac{6}{7}$ per liter.
2. **Use alligation or ratio**:
   - Cost of water $= 0$.
   - Cost of milk $= 1$.
   - Mean price $= \frac{6}{7}$.
   - Using Alligation:
     - Quantity of Water : Quantity of Milk $= (1 - 6/7) : (6/7 - 0) = \frac{1}{7} : \frac{6}{7} = 1 : 6$.
3. **Answer**: Water and milk must be mixed in the ratio **$1 : 6$**.

### Solution 8
1. **Identify the variables and apply Alligation**:
   - Profit on part 1 ($C$) $= 8\%$
   - Profit on part 2 ($D$) $= 18\%$
   - Average profit ($M$) $= 14\%$
   - Ratio of quantity sold at 8% to quantity sold at 18%:
     $$\frac{\text{Quantity at 8\%}}{\text{Quantity at 18\%}} = \frac{18 - 14}{14 - 8} = \frac{4}{6} = \frac{2}{3}$$
2. **Calculate the quantity sold at 18% profit**:
   - Total sugar $= 1000$ kg.
   - Quantity at 18% profit $= 1000 \times \frac{3}{2+3} = 1000 \times \frac{3}{5} = 600$ kg.
3. **Answer**: The quantity sold at 18% profit is **600 kg**.

### Solution 9
1. **Identify the number of Sundays and other days**:
   - The month of 30 days starts with a Sunday.
   - The Sundays fall on dates: 1st, 8th, 15th, 22nd, 29th (5 Sundays).
   - Remaining days $= 30 - 5 = 25$ days.
2. **Calculate total visitors**:
   - Visitors on Sundays $= 5 \times 510 = 2550$.
   - Visitors on other days $= 25 \times 240 = 6000$.
   - Total visitors $= 2550 + 6000 = 8550$.
3. **Calculate the average**:
   - Average per day $= \frac{8550}{30} = 285$.
4. **Answer**: The average number of visitors per day is **285**.

### Solution 10
1. **Apply the repeated dilution formula**:
   - Initial milk quantity $x = 40$ liters.
   - Replaced quantity in each operation $y = 4$ liters.
   - Operations $n = 2$.
   - Pure milk remaining $= x \left( 1 - \frac{y}{x} \right)^n = 40 \left( 1 - \frac{4}{40} \right)^2 = 40 \left( \frac{9}{10} \right)^2 = 40 \times 0.81 = 32.4$ liters.
2. **Find water quantity and ratio**:
   - Water quantity $= 40 - 32.4 = 7.6$ liters.
   - Ratio of milk to water $= 32.4 : 7.6 = 324 : 76 = 81 : 19$.
3. **Answer**: The ratio of milk to water in the final mixture is **$81 : 19$**.
