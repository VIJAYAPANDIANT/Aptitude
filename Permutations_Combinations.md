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

### Problem 4
In how many ways can a group of 5 men and 2 women be made out of a total of 7 men and 3 women?

### Problem 5
How many 4-digit numbers can be formed using the digits $1, 2, 3, 4, 5, 6, 7$ (without repetition) such that the numbers are divisible by 5?

### Problem 6
In how many different ways can the letters of the word "CORPORATION" be arranged so that the vowels always come together?

### Problem 7
A box contains 2 white balls, 3 black balls, and 4 red balls. In how many ways can 3 balls be drawn from the box if at least one black ball is to be included in the draw?

### Problem 8
In how many ways can 5 keys be arranged in a circular key ring?

### Problem 9
In how many ways can a team of 11 cricket players be chosen from 15 players, if one particular player is always included and another particular player is always excluded?

### Problem 10
Find the number of ways in which 4 boys and 4 girls can be seated in a row alternately.

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

### Solution 4
1. **Identify parameters**:
   - Total men $= 7$, choose 5: $7C_5$.
   - Total women $= 3$, choose 2: $3C_2$.
2. **Calculate combinations**:
   - $7C_5 = 7C_2 = \frac{7 \times 6}{2 \times 1} = 21$.
   - $3C_2 = 3C_1 = 3$.
3. **Apply the multiplication principle**:
   - Total ways $= 7C_5 \times 3C_2 = 21 \times 3 = 63$.
4. **Answer**: The group can be made in **63** ways.

### Solution 5
1. **Identify the constraint for divisibility by 5**:
   - A number is divisible by 5 if its last digit is 5 or 0.
   - Since the digits given are $1, 2, 3, 4, 5, 6, 7$, the units place must be filled by the digit **5** (1 way).
2. **Fill the remaining places**:
   - We need to form a 4-digit number.
   - The units place is filled. We have 3 more positions to fill (thousands, hundreds, tens).
   - Remaining digits available $= 6$ (excluding 5).
   - Number of ways to arrange 3 digits out of 6 is $6P_3$:
     $$6P_3 = 6 \times 5 \times 4 = 120 \text{ ways}$$
3. **Calculate total ways**:
   - Total ways $= 120 \times 1 = 120$.
4. **Answer**: There are **120** such numbers.

### Solution 6
1. **Analyze the letters of "CORPORATION"**:
   - Total letters $= 11$.
   - Vowels $= 5$ (O, O, A, I, O). Note that O is repeated 3 times.
   - Consonants $= 6$ (C, R, P, R, T, N). Note that R is repeated 2 times.
2. **Apply the grouping trick**:
   - Group all 5 vowels together: `(OOAIO)`.
   - Treat `(OOAIO)` as 1 unit.
   - Total units to arrange $= 6 \text{ consonants} + 1 \text{ vowel group} = 7$ units.
3. **Arrange the 7 units**:
   - The consonant R is repeated 2 times.
   - Number of ways to arrange these 7 units $= \frac{7!}{2!} = \frac{5040}{2} = 2520$.
4. **Arrange the internal elements of the vowel group**:
   - The group `(OOAIO)` has 5 letters where O is repeated 3 times.
   - Number of ways to arrange the vowels among themselves $= \frac{5!}{3!} = \frac{120}{6} = 20$.
5. **Calculate total arrangements**:
   - Total arrangements $= 2520 \times 20 = 50,400$.
6. **Answer**: The letters can be arranged in **50,400** ways.

### Solution 7
1. **Calculate total ways to draw 3 balls without constraints**:
   - Total balls $= 2 + 3 + 4 = 9$ balls.
   - Drawing 3 balls out of 9:
     $$9C_3 = \frac{9 \times 8 \times 7}{3 \times 2 \times 1} = 84 \text{ ways}$$
2. **Calculate ways to draw 3 balls with NO black balls**:
   - Total non-black balls $= 2 \text{ (white)} + 4 \text{ (red)} = 6$ balls.
   - Drawing 3 balls from these 6:
     $$6C_3 = \frac{6 \times 5 \times 4}{3 \times 2 \times 1} = 20 \text{ ways}$$
3. **Calculate ways with at least one black ball**:
   - $\text{Ways with at least 1 black} = \text{Total ways} - \text{Ways with no black}$
   - $\text{Ways with at least 1 black} = 84 - 20 = 64$ ways.
4. **Answer**: The draw can be done in **64** ways.

### Solution 8
1. **Identify circular permutation conditions**:
   - Number of objects (keys) $n = 5$.
   - In a key ring, clockwise and counterclockwise arrangements are not distinguishable because the key ring can be flipped over.
2. **Apply formula**:
   - $\text{Arrangements} = \frac{(n - 1)!}{2} = \frac{(5 - 1)!}{2} = \frac{4!}{2} = \frac{24}{2} = 12$.
3. **Answer**: The keys can be arranged in **12** ways.

### Solution 9
1. **Analyze the constraints**:
   - Total players $= 15$, choose 11.
   - 1 particular player is always included $\implies$ we must choose him, leaving 10 players to select.
   - 1 particular player is always excluded $\implies$ we cannot choose him, leaving $15 - 1 \text{ (included)} - 1 \text{ (excluded)} = 13$ players available.
2. **Calculate combinations**:
   - Number of ways $= 13C_{10} = 13C_3 = \frac{13 \times 12 \times 11}{3 \times 2 \times 1} = 286$ ways.
3. **Answer**: The team can be chosen in **286** ways.

### Solution 10
1. **Analyze the alternate seating constraint**:
   - There are 4 boys (B) and 4 girls (G).
   - There are two possible patterns: B G B G B G B G or G B G B G B G B.
2. **Calculate arrangements for each pattern**:
   - For B G B G B G B G: Boys can be arranged in $4! = 24$ ways; Girls can be arranged in $4! = 24$ ways.
   - Total for Pattern 1 $= 24 \times 24 = 576$ ways.
   - For G B G B G B G B: Boys can be arranged in $4! = 24$ ways; Girls can be arranged in $4! = 24$ ways.
   - Total for Pattern 2 $= 24 \times 24 = 576$ ways.
3. **Sum the combinations**:
   - Total ways $= 576 + 576 = 1152$ ways.
4. **Answer**: The boys and girls can be seated alternately in **1152** ways.
