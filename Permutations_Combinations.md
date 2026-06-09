# Quantitative Aptitude: Permutations & Combinations

## 1. Concept Definitions & Explanations

- **Factorial ($n!$)**: The product of all positive integers less than or equal to $n$.
  - $n! = n \times (n-1) \times (n-2) \times \dots \times 1$
  - *Note: $0! = 1$ and $1! = 1$.*
- **Permutation ($nPr$)**: An arrangement of a set of objects in a specific order. Order matters.
- **Combination ($nCr$)**: A selection of items from a larger set where order does not matter.
- **Multiplication Principle (AND Rule)**: If an event can occur in $m$ ways, and a second independent event can occur in $n$ ways, then both events can occur in $m \times n$ ways.
- **Addition Principle (OR Rule)**: If an event can occur in $m$ ways, and a second mutually exclusive event can occur in $n$ ways, then either of the events can occur in $m + n$ ways.

---

## 2. Key Formulas & Shortcuts

### Fundamental Formulas
- **Permutations Formula ($nPr$)**: Choosing and arranging $r$ objects out of $n$ distinct objects:
  $$nPr = \frac{n!}{(n-r)!}$$
- **Combinations Formula ($nCr$)**: Choosing $r$ objects out of $n$ distinct objects:
  $$nCr = \frac{n!}{r!(n-r)!}$$
- **Relationship**:
  $$nPr = r! \times nCr$$

### Important Properties
- $nC_0 = nC_n = 1$
- $nC_1 = n$
- $nCr = nC_{n-r}$ (e.g., $10C_8 = 10C_2$)

### Arrangements of Repeating Objects
If there are $n$ objects, where $p$ objects are of one type, $q$ are of another type, and $r$ are of a third type, the number of unique arrangements is:
$$\text{Total Arrangements} = \frac{n!}{p! \cdot q! \cdot r!}$$

### Circular Permutations
- If $n$ distinct objects are arranged in a circle where clockwise and counterclockwise orders are different:
  $$\text{Arrangements} = (n - 1)!$$
- If clockwise and counterclockwise orders are not distinguishable (e.g., beads on a necklace, flowers in a garland):
  $$\text{Arrangements} = \frac{(n - 1)!}{2}$$

---

## 3. Practice Problems

### Problem 1
In how many different ways can the letters of the word "LEADING" be arranged such that the vowels always come together?

### Problem 2
A committee of 5 members is to be formed from 6 men and 4 women. In how many ways can this be done if the committee must contain at least 3 men?

### Problem 3
In how many ways can 6 people be seated around a circular table?

---

## 4. Step-by-Step Solutions

### Solution 1
1. **Analyze the letters of the word "LEADING"**:
   - Total letters $= 7$ (L, E, A, D, I, N, G).
   - Vowels $= 3$ (E, A, I).
   - Consonants $= 4$ (L, D, N, G).
2. **Apply the "vowels together" grouping trick**:
   - Group the 3 vowels (E, A, I) together as a single unit or "super-letter": `(EAI)`.
   - Now, we have 5 units to arrange: `(EAI)`, `L`, `D`, `N`, `G`.
   - Number of ways to arrange these 5 units $= 5! = 120$.
3. **Arrange the internal elements**:
   - The 3 vowels within their group `(EAI)` can be arranged among themselves in $3! = 6$ ways.
4. **Calculate total arrangements**:
   - Total ways $= 5! \times 3! = 120 \times 6 = 720$.
5. **Answer**: The letters can be arranged in **720** ways.

### Solution 2
1. **Identify the constraints**:
   - We need to select 5 members from 6 Men (M) and 4 Women (W).
   - Constraint: "at least 3 men". This gives us 3 cases:
     - **Case 1**: 3 Men AND 2 Women
     - **Case 2**: 4 Men AND 1 Woman
     - **Case 3**: 5 Men AND 0 Women
2. **Calculate combinations for each case**:
   - **Case 1 (3M, 2W)**:
     $$6C_3 \times 4C_2 = \frac{6 \times 5 \times 4}{3 \times 2 \times 1} \times \frac{4 \times 3}{2 \times 1} = 20 \times 6 = 120$$
   - **Case 2 (4M, 1W)**:
     $$6C_4 \times 4C_1 = 6C_2 \times 4 = \frac{6 \times 5}{2 \times 1} \times 4 = 15 \times 4 = 60$$
   - **Case 3 (5M, 0W)**:
     $$6C_5 \times 4C_0 = 6 \times 1 = 6$$
3. **Sum the cases (OR rule)**:
   - Total combinations $= 120 + 60 + 6 = 186$.
4. **Answer**: There are **186** ways to form the committee.

### Solution 3
1. **Apply the Circular Permutation formula**:
   - Number of people $n = 6$.
   - Clockwise and counterclockwise seating arrangements are distinct.
   - $\text{Total seating arrangements} = (n - 1)! = (6 - 1)! = 5!$
2. **Calculate the factorial**:
   - $5! = 5 \times 4 \times 3 \times 2 \times 1 = 120$.
3. **Answer**: There are **120** ways.
