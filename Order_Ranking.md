# Logical Reasoning: Order & Ranking

## 1. Key Formulas & Shortcuts

### 1. Finding Total Number of People
If the rank of a person is given from both ends (Left/Right or Top/Bottom):
$$\text{Total } (T) = \text{Rank from Left } (L) + \text{Rank from Right } (R) - 1$$
$$\text{Total } (T) = \text{Rank from Top } (T_{op}) + \text{Rank from Bottom } (B_{ot}) - 1$$

### 2. Finding Rank from Opposite End
$$L = T - R + 1$$
$$R = T - L + 1$$

### 3. Case of Position Interchange
Suppose A is $L_A$ from left and B is $R_B$ from right. They interchange their positions. Now, A becomes $L_{A\_new}$ from left:
- **Total People**:
  $$T = L_{A\_new} + R_B - 1$$
- **B's New Position from Right**:
  $$R_{B\_new} = R_B + (L_{A\_new} - L_A)$$
- **Number of people sitting between A and B**:
  $$\text{Between} = |L_{A\_new} - L_A| - 1$$

### 4. Mid-point Seating (Number of People Between)
If A's rank from left is $L_A$ and B's rank from right is $R_B$:
- **Case A: Non-overlapping (Normal Case)**
  - If $\text{Total } (T) > (L_A + R_B)$, then:
    $$\text{People Between} = T - (L_A + R_B)$$
- **Case B: Overlapping Case**
  - If $\text{Total } (T) < (L_A + R_B)$, then:
    $$\text{People Between} = (L_A + R_B) - T - 2$$

---

## 2. Practice Problems

### Problem 1
In a class of 45 students, A's rank is 15th from the top. What is A's rank from the bottom?

### Problem 2
In a row of boys, Karun is 17th from the left and Vishal is 19th from the right. If they interchange their positions, Karun becomes 24th from the left. How many boys are there in the row?

### Problem 3
In a row of 30 children, A is 12th from the left and B is 22nd from the right. How many children are sitting between A and B?

### Problem 4 (Comparison Based)
Five friends A, B, C, D, and E scored different marks in an examination.
- A scored more than B but less than C.
- D scored less than B but more than E.
Who scored the second highest marks?

### Problem 5 (Relative Positions)
In a row of girls facing North, Tanvi is 12th from the left end and Sunita is 18th from the right end. If there are 6 girls between them, and Sunita is to the right of Tanvi, how many girls are there in the row?

### Problem 6 (Max / Min Count)
In a row of children, P is 14th from the left and Q is 17th from the right. If there are 8 children between P and Q, find:
1. The maximum possible number of children in the row.
2. The minimum possible number of children in the row.

### Problem 7 (Interchange Position)
In a queue of 40 people, Manoj is 25th from the front and Kiran is 20th from the back. If they interchange their positions, what will be Kiran's new position from the back?

### Problem 8 (Mid-point Position)
In a row of 35 boys, Rahul is 15th from the right end and Amit is 11th from the left end. How many boys are sitting between them, and what is the position of the person sitting exactly in the middle of them from the left end?

### Problem 9 (Interchange with Between Count)
In a row of girls facing North, Reena is 10th from the left and Pinky is 21st from the right. If they interchange their positions, Reena becomes 15th from the left.
1. How many girls are there in the row?
2. What is Pinky's new position from the right?

### Problem 10 (Comparison and Ranks)
Six students P, Q, R, S, T, and U scored different ranks in a class test.
- P's rank is higher than Q's but lower than R's.
- S's rank is higher than T's but lower than U's.
- R's rank is lower than T's.
Who scored the highest rank and who scored the lowest rank?

---

## 3. Step-by-Step Solutions

### Solution 1
1. **Identify parameters**:
   - Total students $T = 45$.
   - Rank from top $T_{op} = 15$.
2. **Apply the formula**:
   $$B_{ot} = T - T_{op} + 1$$
   $$B_{ot} = 45 - 15 + 1 = 30 + 1 = 31$$
3. **Answer**: A's rank is **31st** from the bottom.

### Solution 2
1. **Identify parameters**:
   - Karun's initial left rank $L_{\text{old}} = 17$.
   - Vishal's right rank $R = 19$.
   - Karun's new left rank after interchange $L_{\text{new}} = 24$.
2. **Calculate Total using the interchange formula**:
   - After interchanging, Karun is sitting at Vishal's old spot (which was 19th from the right).
   - Thus, this spot's coordinates are 24th from Left and 19th from Right.
     $$T = L_{\text{new}} + R - 1$$
     $$T = 24 + 19 - 1 = 43 - 1 = 42$$
3. **Answer**: There are **42** boys in the row.

### Solution 3
1. **Identify parameters**:
   - Total $T = 30$.
   - A's left rank $L = 12$.
   - B's right rank $R = 22$.
2. **Determine if it is an overlapping case**:
   - Calculate $L + R = 12 + 22 = 34$.
   - Since $T(30) < L+R(34)$, this is an **overlapping case**.
3. **Apply the Overlapping formula**:
   $$\text{People Between} = (L + R) - T - 2$$
   $$\text{People Between} = (12 + 22) - 30 - 2 = 34 - 30 - 2 = 2$$
4. **Answer**: There are **2** children sitting between A and B.

### Solution 4
1. **Represent the inequalities**:
   - "A scored more than B but less than C" $\implies C > A > B$.
   - "D scored less than B but more than E" $\implies B > D > E$.
2. **Combine the relations**:
   - Combining both chains: $C > A > B > D > E$.
3. **Determine the ranking**:
   - Highest scorer: $C$.
   - Second highest scorer: $A$.
4. **Answer**: **A** scored the second highest marks.

### Solution 5
1. **Identify parameters**:
   - Tanvi's rank from left $L_{\text{Tanvi}} = 12$.
   - Sunita's rank from right $R_{\text{Sunita}} = 18$.
   - Number of girls between them $= 6$.
   - Sunita is to the right of Tanvi (non-overlapping arrangement).
2. **Calculate Total**:
   - Since they do not overlap, we simply sum their ranks and the people in between:
     $$T = L_{\text{Tanvi}} + \text{Between} + R_{\text{Sunita}}$$
     $$T = 12 + 6 + 18 = 36$$
3. **Answer**: There are **36** girls in the row.

### Solution 6
1. **Identify parameters**:
   - Rank of P from left $L_P = 14$.
   - Rank of Q from right $R_Q = 17$.
   - Children between P and Q $= 8$.
2. **Calculate Maximum (Non-overlapping case)**:
   - For maximum number of children, P and Q are placed without overlap.
     $$\text{Max} = L_P + R_Q + \text{Between} = 14 + 17 + 8 = 39$$
3. **Calculate Minimum (Overlapping case)**:
   - For minimum number of children, P and Q overlap.
     $$\text{Min} = L_P + R_Q - \text{Between} - 2 = 14 + 17 - 8 - 2 = 21$$
4. **Answer**: The maximum possible number of children is **39**, and the minimum is **21**.

### Solution 7
1. **Identify parameters**:
   - Total $T = 40$.
   - Manoj's initial front position $L_{\text{Manoj}} = 25$.
   - Kiran's initial back position $R_{\text{Kiran}} = 20$.
2. **Analyze the interchange**:
   - When they interchange positions, Kiran moves to Manoj's old spot.
   - Manoj's old spot was 25th from the front.
3. **Calculate Kiran's new position from the back**:
   - Kiran's new rank from front $L_{\text{Kiran\_new}} = 25$.
   - Rank from back:
     $$R_{\text{Kiran\_new}} = T - L_{\text{Kiran\_new}} + 1$$
     $$R_{\text{Kiran\_new}} = 40 - 25 + 1 = 16$$
4. **Answer**: Kiran is **16th** from the back.

### Solution 8
1. **Identify parameters**:
   - Total $T = 35$.
   - Rahul's rank from right $R_{\text{Rahul}} = 15$.
   - Amit's rank from left $L_{\text{Amit}} = 11$.
2. **Calculate the number of boys sitting between them**:
   - Sum of positions: $L + R = 11 + 15 = 26$.
   - Since $T(35) > 26$, it is a non-overlapping case.
   - $\text{Between} = T - (L + R) = 35 - 26 = 9$ boys.
3. **Calculate the middle position**:
   - Amit's position from left $= 11$.
   - Rahul's position from left $= T - R_{\text{Rahul}} + 1 = 35 - 15 + 1 = 21$.
   - The position exactly in the middle of 11 and 21 is:
     $$\text{Middle Position} = \frac{11 + 21}{2} = 16\text{th from left}$$
4. **Answer**: There are **9** boys sitting between them, and the person sitting exactly in the middle is **16th** from the left end.

### Solution 9
1. **Identify parameters**:
   - Reena's initial left rank $L = 10$.
   - Pinky's initial right rank $R = 21$.
   - Reena's new left rank after interchange $L_{\text{new}} = 15$.
2. **Calculate Total number of girls**:
   - After the interchange, Reena is sitting at Pinky's old spot, which is 21st from the right.
   - Using the formula $T = L_{\text{new}} + R - 1$:
     $$T = 15 + 21 - 1 = 35$$
3. **Calculate Pinky's new position from the right**:
   - Pinky moves to Reena's old spot, which is 10th from the left.
   - Using the formula $R_{\text{new}} = T - L + 1$:
     $$R_{\text{new}} = 35 - 10 + 1 = 26$$
     *(Alternatively, $R_{\text{new}} = R + (L_{\text{new}} - L) = 21 + (15 - 10) = 26$.)*
4. **Answer**: There are **35** girls in the row, and Pinky's new position is **26th** from the right.

### Solution 10
1. **Represent the rank relations (using '>' to mean 'higher/better rank than')**:
   - "P's rank is higher than Q's but lower than R's" $\implies R > P > Q$.
   - "S's rank is higher than T's but lower than U's" $\implies U > S > T$.
   - "R's rank is lower than T's" $\implies T > R$.
2. **Combine the relations**:
   - Since $U > S > T$, $T > R$, and $R > P > Q$, we can link the chains together:
     $$U > S > T > R > P > Q$$
3. **Identify highest and lowest**:
   - Highest rank is $U$, and lowest rank is $Q$.
4. **Answer**: **U** scored the highest rank, and **Q** scored the lowest rank.
