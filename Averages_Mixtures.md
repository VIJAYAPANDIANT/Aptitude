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
