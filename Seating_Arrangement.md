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

### Problem 1 (Linear Row)
Five friends (P, Q, R, S, T) are sitting in a row facing North.
- S is sitting between T and Q.
- Q is immediate left of R.
- P is immediate left of T.
Who is sitting in the middle?

### Problem 2 (Circular Facing Center)
Six people (A, B, C, D, E, F) are sitting around a circular table facing the center.
- A is sitting opposite B.
- C is sitting between A and D.
- E is sitting to the immediate left of B.
- F is sitting to the immediate right of A.
Who is sitting opposite E?

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
