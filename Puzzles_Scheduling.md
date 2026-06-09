# Logical Reasoning: Puzzles & Scheduling

## 1. Puzzle Types & Grids

Puzzles require you to organize unstructured statements into a structured layout. The choice of layout is critical:

### 1. Floor Puzzles
- **Grid Layout**: Draw a vertical table with floor numbers listed from top to bottom (e.g., 7, 6, 5, 4, 3, 2, 1).
- **Standard Assumption**: Floor 1 is the bottom floor and the top floor is the highest number.
- **Left-over variables**: Keep a list of unplaced people/attributes on the side.

### 2. Box Puzzles
- **Grid Layout**: Similar to floor puzzles but without fixed floor numbers (as the absolute positions are not always known at the start).
- **Strategy**: Draw relative stacks. If box A is 3 boxes above B, write: `A - [ ] - [ ] - B`.

### 3. Month & Day Scheduling
- **Grid Layout**: Write days (Mon to Sun) or months (Jan, Feb, etc.) chronologically as rows.
- **Key Hint (Days in Month)**: Pay attention to months with 30 days (April, June, September, November) versus 31 days. Many clues depend on this (e.g., "A has an exam in a month with 30 days").

---

## 2. Solving Workflow

1. **Draw the Skeleton**: Create your baseline table (Floors, Months, Days).
2. **Place Direct Clues**: Write definitive statements straight into the table (e.g., "T lives on the 4th floor").
3. **Branch Cases**: If a key clue has two possibilities (e.g., "P lives on an odd-numbered floor above T" $\to$ could be floor 5 or 7), draw **Case 1** and **Case 2** columns.
4. **Use Negative Clues**: Mark crossed-out variables next to rows (e.g., next to floor 3, write $\cancel{\text{Q}}$ if Q cannot live on floor 3).
5. **Link Relative Clues**: Look for variables that connect multiple statements.

---

## 3. Practice Problems

### Problem 1 (Floor Puzzle)
Seven people (A, B, C, D, E, F, G) live on seven different floors of a building. The bottom floor is 1 and the top floor is 7.
- G lives on an odd-numbered floor.
- Three people live between G and B.
- B lives on a floor immediately above A.
- C lives on an even-numbered floor immediately below F.
- D lives on a floor above E but below G.
Find the floor on which each person lives.

### Problem 2 (Month Scheduling)
Six persons (P, Q, R, S, T, U) have seminars in different months of the same year: January, March, April, June, August, and October.
- Q's seminar is in a month with 30 days.
- Only one person has a seminar between Q and T.
- P has a seminar immediately before U.
- R's seminar is in March.
- S's seminar is not in January.
Find the seminar month for each person.

---

## 4. Step-by-Step Solutions

### Solution 1
1. **Set up the baseline table** (Floors 7 to 1).
2. **Analyze the G and B clues**:
   - G is on an odd floor (1, 3, 5, or 7).
   - Three floors between G and B.
     - If $G = 7$, then $B = 3$. (Valid)
     - If $G = 5$, then $B = 1$. (Valid)
     - If $G = 3$, $B$ would have to be below or above, but we can't fit 3 floors in between.
     - If $G = 1$, then $B = 5$. (Valid)
3. **Analyze the B and A clue**:
   - B lives immediately above A.
     - If $B = 3$, then $A = 2$.
     - If $B = 1$, A cannot sit on floor 0 (doesn't exist). So $G=5, B=1$ is **Eliminated**.
     - If $B = 5$, then $A = 4$.
4. **Test Case 1 ($G = 7, B = 3, A = 2$)**:
   - Remaining floors: 6, 5, 4, 1.
   - Clue: C lives on an even floor immediately below F.
     - Even floors left: 6, 4.
     - If $C = 6$, F must be on 7 (occupied by G).
     - If $C = 4$, F must be on 5. So $F = 5, C = 4$.
     - Remaining floors for D and E: 6, 1.
   - Clue: D lives above E but below G.
     - Since $G = 7$, D can be on 6 and E on 1. Since $6 > 1$, D is above E, and both are below G. This matches perfectly!
     - Let's list this arrangement:
       - Floor 7: G
       - Floor 6: D
       - Floor 5: F
       - Floor 4: C
       - Floor 3: B
       - Floor 2: A
       - Floor 1: E
5. **Answer**: The floors from 7 to 1 are occupied by **G, D, F, C, B, A, E**.

### Solution 2
1. **List the months and their number of days**:
   - January (31)
   - March (31)
   - April (30)
   - June (30)
   - August (31)
   - October (31)
2. **Place the direct clues**:
   - R is in March.
   - Q is in a month with 30 days (April or June).
3. **Branch into Cases**:
   - **Case 1: Q is in April**
     - One person between Q and T $\implies$ T must be in January or June.
     - R is in March.
   - **Case 2: Q is in June**
     - One person between Q and T $\implies$ T must be in March (occupied by R) or August. So T must be in August.
4. **Evaluate Case 2 ($Q = \text{June}, T = \text{August}, R = \text{March}$)**:
   - Remaining months: January, April, October.
   - Clue: P is immediately before U.
     - The only consecutive empty months left are ... none! January, April, and October are isolated.
     - Hence, Case 2 is **Eliminated**.
5. **Evaluate Case 1 ($Q = \text{April}$)**:
   - Clue: P is immediately before U.
     - We need two consecutive empty months.
     - Since R is in March and Q is in April, the remaining months are January, June, August, October.
     - Consecutive months left: June and August (since July is not in our list, the next month in our scheduling list after June is August).
     - Let's check: If $P = \text{June}$ and $U = \text{August}$.
     - Remaining months: January, October.
     - Since $Q = \text{April}$, the slot for T (one person between Q and T) must be January. So $T = \text{January}$.
     - Remaining slot for S: October.
     - Check: S's seminar is not in January. (Matches: S is in October).
6. **Answer**:
   - **January**: T
   - **March**: R
   - **April**: Q
   - **June**: P
   - **August**: U
   - **October**: S
