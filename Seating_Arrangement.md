# Logical Reasoning: Seating Arrangement

## 1. Concept Definitions & Explanations

- **Linear Arrangement**: Arranging people or objects in a straight line (single row or multiple parallel rows).
- **Circular Arrangement**: Arranging people around a circle (facing towards the center or away from the center).
- **Facing Directions**:
  - **Facing North**: Your left is the arrangement's Left ($\leftarrow$), and your right is the arrangement's Right ($\rightarrow$).
  - **Facing South**: The arrangement's Left is to your right ($\rightarrow$), and the arrangement's Right is to your left ($\leftarrow$).
  - **Circular (Facing Center)**:
    - **Clockwise movement** represents moving to the **Left** of a person.
    - **Counter-clockwise movement** represents moving to the **Right** of a person.
  - **Circular (Facing Outwards)**:
    - **Clockwise movement** represents moving to the **Right** of a person.
    - **Counter-clockwise movement** represents moving to the **Left** of a person.

---

## 2. Strategy & Solving Tips

1. **Identify Solid Clues**: Start placing elements that have fixed positions (e.g., "A sits at the extreme right end" or "B sits third to the left of C").
2. **Handle Conditional/Relative Clues**: Keep track of clues like "D is not an immediate neighbor of E" in a side scratchnote.
3. **Double-check Directions**: In circular arrangements, mentally put yourself in the position of the person facing center/outside to determine their left and right correctly.
4. **Draw Multiple Cases**: If a clue has two possibilities, draw both side-by-side (Case 1 and Case 2) and eliminate the invalid one as more clues are read.

---

## 3. Practice Problems

### Problem 3 (Linear Two Rows)
Twelve people are sitting in two parallel rows containing six people each, in such a way that there is an equal distance between adjacent persons. In Row 1, P, Q, R, S, T, and V are seated and all of them are facing South. In Row 2, A, B, C, D, E, and F are seated and all of them are facing North.
- A sits third to the right of D. Neither A nor D sits at extreme ends of the row.
- T faces D.
- V sits second to the left of T.
- Only two people sit between V and R.
- B sits second to the right of C. C does not face T or V.
- F is not an immediate neighbor of B.
- P sits third to the left of Q.
Who sits opposite E?

### Problem 4 (Circular Arrangement - Inward Facing)
Eight friends A, B, C, D, E, F, G, and H sit around a circular table facing the center.
- B sits third to the right of F.
- Only two people sit between B and G.
- A sits second to the left of D. D is not an immediate neighbor of B or G.
- C sits third to the right of H.
- E is not an immediate neighbor of G.
Who sits third to the left of C?

### Problem 5 (Linear - Single Row facing North)
Eight people A, B, C, D, E, F, G, and H sit in a row facing North.
- A sits fourth to the right of E.
- E sits at one of the extreme ends of the row.
- H sits third to the left of C.
- C is not an immediate neighbor of A or E.
- F sits second to the right of B.
- D sits to the immediate left of G.
Who sits to the immediate left of D?

### Problem 6 (Square Table)
Eight people P, Q, R, S, T, U, V, and W are sitting around a square table in such a way that four of them sit at four corners of the square while four sit in the middle of each of the four sides. Those who sit at the four corners face the center while those who sit in the middle of the sides face outside.
- P sits third to the right of S. S faces the center.
- Q sits third to the left of U. U does not sit in the middle of the sides.
- Only one person sits between Q and V.
- V is not an immediate neighbor of S.
- T sits second to the right of W. W faces the center.
- R is not an immediate neighbor of P.
Who sits opposite T?

### Problem 7 (Linear Row with facing directions)
Eight friends A, B, C, D, E, F, G, and H sit in a straight line. Some face North and some face South.
- A sits third to the right of F.
- F sits at one of the extreme ends of the row.
- D sits third to the left of A.
- B sits second to the right of C. C is not an immediate neighbor of F or A.
- E sits second to the left of G. G faces North.
- Immediate neighbors of A face the same direction.
- F and D face opposite directions.
- Both the immediate neighbors of D face South.
- H faces North.
Who sits to the immediate left of B?

---

## 4. Step-by-Step Solutions

### Solution 1
1. **Analyze the clues**:
   - Clue 1: S is between T and Q. This means the block is either `T - S - Q` or `Q - S - T`.
   - Clue 2: Q is immediate left of R. This gives the block `Q - R`.
   - Clue 3: P is immediate left of T. This gives the block `P - T`.
2. **Synthesize the blocks**:
   - From `Q - R` and the `T - S - Q` block:
     - If we choose `T - S - Q`, adding R gives: `T - S - Q - R`.
     - Now, we add P to the immediate left of T: `P - T - S - Q - R`.
     - This arrangement has 5 people, which matches the problem description.
3. **Verify the order**:
   - Sequence: `P, T, S, Q, R` (left to right, all facing North).
   - Let's check conditions:
     - S is between T and Q? Yes (`T - S - Q`).
     - Q is immediate left of R? Yes.
     - P is immediate left of T? Yes.
4. **Identify the middle seat**:
   - The middle seat (3rd from either end) is occupied by **S**.
5. **Answer**: **S** is sitting in the middle.

### Solution 2
1. **Represent the circular arrangement**:
   - Six seats numbered 1 to 6 in a circle clockwise.
   - Let's place A at Seat 1 (top).
   - Since A is opposite B, B is at Seat 4 (bottom).
2. **Place other elements**:
   - Clue: F is to the immediate right of A.
     - Facing center, the right of A (Seat 1) is counter-clockwise, which is Seat 6. So, F is at Seat 6.
   - Clue: E is to the immediate left of B.
     - Facing center, the left of B (Seat 4) is clockwise, which is Seat 5. So, E is at Seat 5.
   - Clue: C is sitting between A and D.
     - The empty seats left are Seat 2 and Seat 3.
     - For C to be between A (Seat 1) and D, C must be at Seat 2, and D must be at Seat 3.
3. **Write down the full clockwise configuration**:
   - Seat 1: A
   - Seat 2: C
   - Seat 3: D
   - Seat 4: B
   - Seat 5: E
   - Seat 6: F
4. **Identify who is opposite E**:
   - The seat opposite E (Seat 5) is Seat 2.
   - Seat 2 is occupied by **C**.
5. **Answer**: **C** is sitting opposite E.

### Solution 3
1. **Establish Row Layouts**:
   - Row 1 (facing South, left to right is positions 6 to 1 from our perspective): P, Q, R, S, T, V.
   - Row 2 (facing North, left to right is positions 1 to 6 from our perspective): A, B, C, D, E, F.
2. **Place A and D**:
   - A sits third to the right of D, and neither sits at extreme ends.
   - Since they are not at 1 or 6, D must be at position 2, and A must be at position 5 (since 2 + 3 = 5).
3. **Place T and V**:
   - T faces D, so T is at Row 1 position 2.
   - V sits second to the left of T. Row 1 faces South, so left of T is towards position 4. So V is at Row 1 position 4.
4. **Place R**:
   - Only two people sit between V and R. With V at 4, R must be at 1.
5. **Place C and B**:
   - B sits second to the right of C. C does not face T (2) or V (4).
   - In Row 2, empty spots are 1, 3, 4, 6. Since C cannot face T (2) or V (4), and B sits second to the right of C (C + 2 = B), the only valid positions are C at 1 and B at 3.
6. **Place F and E**:
   - F is not an immediate neighbor of B (3). So F cannot be at 4. Thus F must be at 6.
   - The remaining spot in Row 2 is 4, which is filled by E.
7. **Place Q and P**:
   - P sits third to the left of Q. In Row 1 (South-facing), left of Q is towards higher position numbers. The empty spots in Row 1 are 3, 5, 6.
   - If Q is at 3, P is at 6.
   - The remaining spot 5 in Row 1 is filled by S.
8. **Final Arrangement**:
   - Row 1 (South): R (1), T (2), Q (3), V (4), S (5), P (6)
   - Row 2 (North): C (1), D (2), B (3), E (4), A (5), F (6)
9. **Identify who sits opposite E**:
   - Position 4 in Row 2 (E) is opposite position 4 in Row 1 (V).
10. **Answer**: **V** sits opposite E.

### Solution 4
1. **Place F and B**:
   - Let F be at position 1. B sits third to the right of F (counter-clockwise), so B is at position 4.
2. **Place G**:
   - Only two people sit between B (4) and G. G must be at position 7.
3. **Place D and A**:
   - A sits second to the left of D (clockwise). D is not a neighbor of B (4) or G (7).
   - This rules out D at positions 3, 5, 6, 8.
   - So D must be at position 2. Thus, A sits second to the left of D, placing A at position 8.
4. **Place C and H**:
   - C sits third to the right of H (H + 3 = C counter-clockwise).
   - The available empty positions are 3, 5, 6.
   - If H is at 3, C is at 6.
   - If H is at 5, C would be at 8 (occupied).
   - If H is at 6, C would be at 1 (occupied).
   - So H is at position 3, and C is at position 6.
5. **Place E**:
   - The remaining position 5 is occupied by E.
   - E (5) is not a neighbor of G (7), which matches the clue.
6. **Final Clockwise Arrangement**:
   - 1: F, 2: D, 3: H, 4: B, 5: E, 6: C, 7: G, 8: A
7. **Find third to the left of C**:
   - Left of C (6) facing center is clockwise: 6 -> 5 -> 4 -> 3.
   - Position 3 is occupied by H.
8. **Answer**: **H** sits third to the left of C.

### Solution 5
1. **Place E and A**:
   - E sits at one of the extreme ends. Let's place E at position 1.
   - A sits fourth to the right of E. Since they face North, right is to the right. So A is at position 5.
2. **Place H and C**:
   - H sits third to the left of C.
   - C is not an immediate neighbor of A (5) or E (1). So C cannot be at 2, 4, 6.
   - If C is at 7, H is at 4.
   - If C is at 8, H is at 5 (occupied).
   - So C is at 7 and H is at 4.
3. **Place B and F**:
   - F sits second to the right of B (B + 2 = F).
   - The empty positions are 2, 3, 6, 8.
   - For B + 2 = F, the only valid pair is B at 6 and F at 8.
4. **Place D and G**:
   - D sits to the immediate left of G.
   - The remaining empty positions are 2 and 3.
   - So D must be at 2 and G must be at 3.
5. **Final Arrangement (Left to Right)**:
   - E (1), D (2), G (3), H (4), A (5), B (6), C (7), F (8)
6. **Identify who sits to the immediate left of D**:
   - Since all face North, the immediate left of D (2) is E (1).
7. **Answer**: **E** sits to the immediate left of D.

### Solution 6
1. **Establish the layout**:
   - Corners (face center): 1, 3, 5, 7.
   - Sides (face outside): 2, 4, 6, 8.
2. **Place S and P**:
   - S faces center, so place S at corner 1.
   - P sits third to the right of S. Right of S (facing center) is counter-clockwise: 1 -> 2 -> 3 -> 4. So P is at side 4.
3. **Place U and Q**:
   - U does not sit at the side, so U is at a corner: 3, 5, or 7.
   - Q sits third to the left of U (clockwise).
   - If U is at 3: Q is at 8.
   - If U is at 5: Q is at 2.
   - If U is at 7: Q is at 4 (occupied by P).
4. **Place V**:
   - Only one person sits between Q and V. V is not an immediate neighbor of S (1), so V cannot be at 2 or 8.
   - If Q is at 8: V could be at 6 or 2. Since V cannot be at 2, V is at 6.
   - If Q is at 2: V could be at 4 (occupied) or 8 (not allowed as neighbor of S).
   - Therefore, Q is at 8, U is at 3, and V is at 6.
5. **Place W and T**:
   - W faces center (corner). Available corners are 5 and 7.
   - T sits second to the right of W (counter-clockwise).
   - If W is at 5: T is at 7.
   - If W is at 7: T is at 1 (occupied by S).
   - So W is at 5 and T is at 7.
6. **Place R**:
   - The only remaining position is 2, which is occupied by R. R is not a neighbor of P (4).
7. **Final Clockwise Arrangement**:
   - 1: S, 2: R, 3: U, 4: P, 5: W, 6: V, 7: T, 8: Q
8. **Identify who sits opposite T**:
   - Corner 7 (T) is opposite Corner 3 (U).
9. **Answer**: **U** sits opposite T.

### Solution 7
1. **Place F and A**:
   - F sits at one of the extreme ends. Let's place F at 1.
   - A sits third to the right of F, so F must face North and A is at 4.
2. **Place D**:
   - D sits third to the left of A. Since A is at 4, D must be at 7, and A must face South.
3. **Place C and B**:
   - B sits second to the right of C. C is not adjacent to F (1) or A (4). So C cannot be at 2, 3, 5.
   - The available positions for C are 6 or 8.
   - If C is at 8: C must face South so that B is at 6.
   - If C is at 6: C must face North so that B is at 8.
4. **Analyze the G and E clue**:
   - E sits second to the left of G. G faces North, so E must be at position G - 2.
   - Let's check both cases:
     - **Case 1 (C at 8, B at 6)**: Empty spots are 2, 3, 5. For G - 2 = E, G must be at 5 and E at 3. The remaining position 2 is filled by H.
     - **Case 2 (C at 6, B at 8)**: Empty spots are 2, 3, 5. For G - 2 = E, G must be at 5 and E at 3. Remaining position 2 is filled by H.
5. **D's neighbors direction clue**:
   - "Both the immediate neighbors of D face South."
   - In Case 2, D is at 7, so its neighbors are C (6) and B (8). But in Case 2, C faces North. Thus, Case 2 is eliminated.
   - In Case 1, neighbors of D (7) are B (6) and C (8). Both face South. This works!
6. **Determine remaining directions**:
   - F faces North (1).
   - H faces North (2).
   - E faces North (3) because immediate neighbors of A (4) face the same direction, and G (5) faces North.
   - A faces South (4).
   - G faces North (5).
   - B faces South (6).
   - D faces South (7) because F (North) and D face opposite directions.
   - C faces South (8).
7. **Identify who sits to the immediate left of B**:
   - B is at 6 facing South. Immediate left of B is to the right (position 7), which is occupied by D.
8. **Answer**: **D** sits to the immediate left of B.
