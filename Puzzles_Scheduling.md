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

### Problem 3 (Box Stack Puzzle)
Seven boxes A, B, C, D, E, F, and G are kept one above another in a stack.
- Box C is kept immediately above box A.
- Only two boxes are kept between box A and box B. Box B is kept below box A.
- Only three boxes are kept between box D and box G. Box D is kept above box G.
- Box E is kept immediately below box G.
- Box F is not at the top of the stack.
Find the order of the boxes from top to bottom.

### Problem 4 (Day Scheduling)
Seven people P, Q, R, S, T, U, and V attend lectures on seven different days of the week, starting from Monday to Sunday.
- Q attends on Wednesday.
- Only one person attends between Q and V.
- S attends immediately before T, but not on Monday.
- S attends on a day after Q.
- Only two people attend between T and P.
- R attends before U but after V.
Find the day on which each person attends their lecture.

### Problem 5 (Month & City Scheduling)
Five friends A, B, C, D, and E travel to five different cities (Delhi, Mumbai, Kolkata, Chennai, Bangalore) in five different months (January, April, July, September, December) of the same year.
- B goes to Mumbai in July.
- A travels in a month immediately before E. E does not go to Bangalore.
- The one who goes to Delhi travels in December.
- C travels to Kolkata in April.
- D travels to Bangalore.
Find who travels to Chennai and in which month.

### Problem 6 (Linear Placement with Subjects)
Six professors P, Q, R, S, T, and U sit in a row facing North and teach different subjects: Physics, Chemistry, Maths, Biology, History, and English.
- R teaches Maths and sits at one of the extreme ends of the row.
- Only two people sit between R and P, who teaches Physics.
- U teaches Chemistry and sits second to the right of P.
- S teaches Biology and sits to the immediate left of Q, who teaches English.
Find the subject taught by T and T's position from the left end.

### Problem 7 (Month Scheduling - 30/31 Days)
Three couples (A-B, C-D, E-F) go on vacation in three different months: April, July, and August of the same year.
- A and B go in a month with 30 days.
- C and D go in a month immediately after E and F.
Find which couple goes on vacation in August.

### Problem 8 (Floor Puzzle)
Six people A, B, C, D, E, and F live on six different floors of a building (floor 1 is the bottom floor, and floor 6 is the top floor).
- A lives on an even-numbered floor.
- Only two people live between A and B.
- B does not live on the bottom floor.
- C lives on floor number 4.
- C lives immediately above D.
- E lives on a floor above F.
Find the floor on which each person lives.

### Problem 9 (Day Scheduling)
Seven people P, Q, R, S, T, U, and V attend lectures on seven different days of the week, starting from Monday to Sunday.
- Q attends on Tuesday.
- V attends on Sunday.
- Three people attend between Q and U.
- P attends immediately after R.
- S attends on a day before T.
- T attends on Friday.
Find the day on which each person attends their lecture.

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

### Solution 3
1. **Represent relative positions**:
   - Clue 1: C is immediately above A $\to$ `C - A`.
   - Clue 2: Two boxes between A and B, and B is below A $\to$ `C - A - [ ] - [ ] - B` (occupies 5 spots).
   - Clue 3: Three boxes between D and G, and D is above G $\to$ `D - [ ] - [ ] - [ ] - G` (occupies 5 spots).
   - Clue 4: E is immediately below G $\to$ `D - [ ] - [ ] - [ ] - G - E` (occupies 6 spots).
2. **Combine the blocks in a 7-box stack**:
   - If we place the 6-spot block `D - [ ] - [ ] - [ ] - G - E` starting at position 1 (top):
     - Position 1: D, Position 5: G, Position 6: E.
     - Try placing the 5-spot block `C - A - [ ] - [ ] - B`:
       - If C is at 3 and A is at 4, then B must be at 7. This fits perfectly!
   - Now the stack is:
     - 1: D
     - 2: (Empty)
     - 3: C
     - 4: A
     - 5: G
     - 6: E
     - 7: B
3. **Place the remaining box**:
   - The remaining box F must go to the only empty slot at position 2.
   - Check: F is not at the top. (Correct, D is at 1).
4. **Answer**: The order from top to bottom is **D, F, C, A, G, E, B**.

### Solution 4
1. **Set up the days baseline**: Monday to Sunday.
2. **Place direct clues**:
   - Q is on Wednesday.
   - Only one person between Q and V. So V is either on Monday or Friday.
   - S is immediately before T (`S - T`), S is after Q, and S is not on Monday.
   - R is before U but after V.
3. **Branch into Cases**:
   - **Case 1: V is on Monday**
     - Since R is after V, R and U must be scheduled on days after Monday.
     - Since S is after Q (Wed) and `S - T` are consecutive, S can be on Thursday, Friday, or Saturday.
     - Let's test S on Thursday, T on Friday:
       - Clue: Only two people between T (Fri) and P $\implies$ P must be on Tuesday.
       - The remaining empty days are Saturday and Sunday.
       - Clue: R is before U $\implies$ R is on Saturday, U is on Sunday.
       - Check: R (Sat) is after V (Mon). (True)
       - All conditions are met!
   - **Case 2: V is on Friday**
     - S must be after Q (Wed). If S is on Saturday, T is on Sunday.
     - Two people between T (Sun) and P $\implies$ P is on Thursday.
     - The remaining empty days are Monday, Tuesday, Thursday.
     - Since R is after V (Fri), R must be on Saturday or Sunday (but both are occupied). Hence, Case 2 is eliminated.
4. **Answer**:
   - **Monday**: V
   - **Tuesday**: P
   - **Wednesday**: Q
   - **Thursday**: S
   - **Friday**: T
   - **Saturday**: R
   - **Sunday**: U

### Solution 5
1. **List months chronologically**: January, April, July, September, December.
2. **Place direct clues**:
   - B goes to Mumbai in July.
   - C goes to Kolkata in April.
   - December traveler goes to Delhi.
3. **Determine A and E's months**:
   - A travels in a month immediately before E.
   - The empty months are January, September, and December.
   - The only consecutive empty months left are September and December.
   - So, A travels in September, and E travels in December.
   - Since E travels in December, E goes to Delhi.
4. **Determine D's details**:
   - The remaining person D must travel in January.
   - D goes to Bangalore.
5. **Determine A's city**:
   - The remaining city is Chennai, which must be visited by A in September.
6. **Answer**: **A** travels to **Chennai** in **September**.

### Solution 6
1. **Set up the positions**: 1 to 6 (left to right).
2. **Place R and P**:
   - R teaches Maths and sits at one of the extreme ends (1 or 6).
   - Case 1: R is at 1.
     - Only two people sit between R (1) and P $\implies$ P is at 4.
     - U sits second to the right of P $\implies$ U is at 6 (but 6 is vacant, so U is at 6).
     - S sits to the immediate left of Q $\implies$ S and Q are adjacent. Since 1, 4, 6 are occupied, empty spots are 2, 3, 5. So S must be at 2 and Q at 3.
     - The remaining spot 5 is occupied by T.
3. **Match teachers with subjects**:
   - Position 1: R (Maths)
   - Position 2: S (Biology)
   - Position 3: Q (English)
   - Position 4: P (Physics)
   - Position 5: T (History)
   - Position 6: U (Chemistry)
4. **Answer**: T teaches **History** and sits at the **5th position** from the left end.

### Solution 7
1. **Analyze month lengths**:
   - April: 30 days
   - July: 31 days
   - August: 31 days
2. **Place A and B**:
   - A and B go in a month with 30 days $\implies$ April.
3. **Place remaining couples**:
   - C and D go immediately after E and F.
   - The remaining months are July and August. August is immediately after July.
   - Thus, E and F go in July, and C and D go in August.
4. **Answer**: **C and D** go on vacation in August.

### Solution 8
1. **Set up the floors baseline**: Floors 6 down to 1.
2. **Analyze A and B's positions**:
   - A lives on an even-numbered floor (2, 4, or 6).
   - Only two people live between A and B.
   - B does not live on floor 1.
     - If A is on floor 4: B must be on floor 1 (but B cannot be on floor 1). So A is not on floor 4.
     - If A is on floor 6: B must be on floor 3.
     - If A is on floor 2: B must be on floor 5.
3. **Place C and D**:
   - C lives on floor number 4.
   - C lives immediately above D, so D is on floor 3.
   - Since floor 3 is occupied by D, A cannot be on floor 6 (which would have forced B onto floor 3).
   - Therefore, A must be on floor 2, and B must be on floor 5.
4. **Place E and F**:
   - The remaining empty floors are floor 6 and floor 1.
   - E lives on a floor above F, so E must be on floor 6, and F must be on floor 1.
5. **Final Floor Arrangement**:
   - Floor 6: E
   - Floor 5: B
   - Floor 4: C
   - Floor 3: D
   - Floor 2: A
   - Floor 1: F
6. **Answer**: From floors 6 to 1, the order is **E, B, C, D, A, F**.

### Solution 9
1. **Set up the days baseline**: Monday to Sunday (1 to 7).
2. **Place direct clues**:
   - Q is on Tuesday (2).
   - V is on Sunday (7).
   - T is on Friday (5).
3. **Place U**:
   - Three people attend between Q (2) and U.
   - Counting days: 3, 4, 5 are the three days between, so U must be on Saturday (6).
4. **Place R and P**:
   - P attends immediately after R (`R - P`).
   - The remaining empty days are Monday (1), Wednesday (3), and Thursday (4).
   - The only consecutive empty days are Wednesday (3) and Thursday (4).
   - Thus, R is on Wednesday (3), and P is on Thursday (4).
5. **Place S**:
   - The only remaining day is Monday (1), which must be occupied by S.
   - Check: S (Monday) attends on a day before T (Friday). This is correct.
6. **Final Schedule**:
   - Monday: S
   - Tuesday: Q
   - Wednesday: R
   - Thursday: P
   - Friday: T
   - Saturday: U
   - Sunday: V
7. **Answer**: The lecture schedule is **S (Mon), Q (Tue), R (Wed), P (Thu), T (Fri), U (Sat), V (Sun)**.
