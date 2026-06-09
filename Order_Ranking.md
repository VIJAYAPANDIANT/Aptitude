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
