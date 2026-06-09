# Logical Reasoning: Data Sufficiency

## 1. Standard Options Layout

In Data Sufficiency questions, you are given a question followed by two statements. You must decide whether the statements contain enough information to answer the question. You do not need to find the final numerical answer; you only need to determine if it *can* be found.

The standard multiple-choice options are:
- **Option A**: Statement (1) alone is sufficient to answer the question, but statement (2) alone is not.
- **Option B**: Statement (2) alone is sufficient to answer the question, but statement (1) alone is not.
- **Option C**: Both statements (1) and (2) together are sufficient to answer the question, but neither statement alone is sufficient.
- **Option D**: Each statement alone is sufficient to answer the question.
- **Option E**: Statements (1) and (2) together are not sufficient to answer the question (additional data is needed).

---

## 2. Solving Workflow (Flowchart)

```
                    Evaluate Statement (1) alone
                            /          \
                     Sufficient     Not Sufficient
                        /                  \
         Evaluate Statement (2) alone     Evaluate Statement (2) alone
                /           \                 /            \
          Sufficient   Not Sufficient   Sufficient    Not Sufficient
             /                 \             /                \
         [Option D]        [Option A]    [Option B]     Combine (1) & (2)
                                                           /          \
                                                     Sufficient    Not Sufficient
                                                        /                  \
                                                    [Option C]         [Option E]
```

### Critical Rules
- **Yes/No Questions**: If a question asks a "Yes/No" question (e.g., "Is $x$ odd?"), a statement is sufficient if it allows you to answer with a definite **"Yes"** OR a definite **"No"**. If the answer is "maybe" or "sometimes yes, sometimes no", the statement is not sufficient.
- **Uniqueness**: If a question asks for a value (e.g., "What is the age of Ravi?"), a statement is only sufficient if it yields a **single, unique value**. If it yields multiple values (e.g., "Ravi is either 24 or 25"), it is not sufficient.

---

## 3. Practice Problems

### Problem 1 (Arithmetic)
What is the present age of Ravi?
- **Statement (1)**: Ravi's present age is 4 times his son's age.
- **Statement (2)**: 5 years hence, Ravi's age will be 3 times his son's age.

### Problem 2 (Logical)
Among P, Q, R, S, and T, who is the tallest?
- **Statement (1)**: R is taller than P and T, but shorter than Q.
- **Statement (2)**: S is shorter than Q.

### Problem 3 (Number Theory)
Is $x$ an odd integer?
- **Statement (1)**: $x/2$ is not an integer.
- **Statement (2)**: $2x$ is an even integer.

### Problem 4 (Blood Relations)
How is A related to B?
- **Statement (1)**: C is B's sister and A's daughter.
- **Statement (2)**: D is A's wife and B's mother.

### Problem 5 (Direction Sense)
In which direction is Point P with respect to Point Q?
- **Statement (1)**: P is 5 m North of R, which is 8 m East of S.
- **Statement (2)**: Q is 5 m South of T, which is 8 m West of S.

### Problem 6 (Averages)
What is the average weight of a group of 10 people?
- **Statement (1)**: If two people of weight 60 kg and 70 kg leave the group, the average weight of the remaining people decreases by 1 kg.
- **Statement (2)**: If two new people of weight 50 kg and 60 kg join the group, the average weight of the new group increases by 0.5 kg.

### Problem 7 (Coding-Decoding)
What is the code for the word "bright" in a code language?
- **Statement (1)**: "sky is bright" is written as "pi la ko" and "sun is hot" is written as "ko ze mu".
- **Statement (2)**: "bright sun shines" is written as "pi mu ra" and "shines like star" is written as "ra de ga".

---

## 4. Step-by-Step Solutions

### Solution 1
1. **Evaluate Statement (1) alone**:
   - Let Ravi's age be $R$ and son's age be $S$.
   - $R = 4S$.
   - This single equation has two variables. We cannot find a unique value for $R$.
   - **Statement (1) is NOT sufficient**.
2. **Evaluate Statement (2) alone**:
   - 5 years hence: $(R + 5) = 3(S + 5)$.
   - Again, one equation with two variables. We cannot find a unique value for $R$.
   - **Statement (2) is NOT sufficient**.
3. **Combine Statements (1) and (2)**:
   - We now have a system of two independent linear equations:
     1. $R = 4S$
     2. $R + 5 = 3S + 15 \implies R - 3S = 10$
   - Substitute (1) into (2):
     $4S - 3S = 10 \implies S = 10$.
     $R = 4(10) = 40$.
   - Combining the statements gives a unique value for Ravi's age (40 years).
   - **Combined statements are sufficient**.
4. **Answer**: **Option C** (Both statements together are sufficient).

### Solution 2
1. **Evaluate Statement (1) alone**:
   - "R is taller than P and T, but shorter than Q" $\implies Q > R > (P, T)$.
   - We don't have any information about S. S could be the tallest, or shortest.
   - **Statement (1) is NOT sufficient**.
2. **Evaluate Statement (2) alone**:
   - "S is shorter than Q" $\implies Q > S$.
   - We don't know anything about P, R, or T.
   - **Statement (2) is NOT sufficient**.
3. **Combine Statements (1) and (2)**:
   - From (1): $Q > R$, $Q > P$, $Q > T$.
   - From (2): $Q > S$.
   - Combining these, we know that Q is taller than R, P, T, and S.
   - Since Q is taller than all other four individuals, Q must be the tallest.
   - We get a unique answer (Q is the tallest).
   - **Combined statements are sufficient**.
4. **Answer**: **Option C** (Both statements together are sufficient).

### Solution 3
1. **Evaluate Statement (1) alone**:
   - $x/2$ is not an integer $\implies x$ is not an even integer.
   - However, $x$ could be an odd integer (e.g., $x=3$, $3/2=1.5$) or a fraction (e.g., $x=1.5$, $1.5/2=0.75$).
   - We cannot definitively say if $x$ is an odd integer.
   - **Statement (1) is NOT sufficient**.
2. **Evaluate Statement (2) alone**:
   - $2x$ is an even integer $\implies 2x = 2k$ (where $k$ is an integer) $\implies x = k$.
   - This tells us $x$ is an integer, but it can be odd (e.g., $x=3 \implies 2x=6$) or even (e.g., $x=2 \implies 2x=4$).
   - **Statement (2) is NOT sufficient**.
3. **Combine Statements (1) and (2)**:
   - From Statement (2), we know $x$ is an integer.
   - From Statement (1), we know $x/2$ is not an integer.
   - An integer $x$ whose half is not an integer must be an odd integer (since even integers divided by 2 result in integers).
   - Thus, we get a definitive "Yes, $x$ is an odd integer."
   - **Combined statements are sufficient**.
4. **Answer**: **Option C** (Both statements together are sufficient).

### Solution 4
1. **Evaluate Statement (1) alone**:
   - C is B's sister $\implies$ B and C are siblings.
   - C is A's daughter $\implies$ A is a parent of B and C.
   - However, we do not know A's gender. A could be B's Father or Mother.
   - **Statement (1) is NOT sufficient**.
2. **Evaluate Statement (2) alone**:
   - D is A's wife $\implies$ A is D's husband (Male).
   - D is B's mother $\implies$ B is D's child.
   - Since A is married to B's mother and A is male, A must be B's father.
   - This gives a unique relationship.
   - **Statement (2) is sufficient**.
3. **Answer**: **Option B** (Statement (2) alone is sufficient).

### Solution 5
1. **Evaluate Statement (1) alone**:
   - Point P is mapped relative to R and S. Q is not mentioned.
   - **Statement (1) is NOT sufficient**.
2. **Evaluate Statement (2) alone**:
   - Point Q is mapped relative to T and S. P is not mentioned.
   - **Statement (2) is NOT sufficient**.
3. **Combine Statements (1) and (2)**:
   - Let S be the origin $(0, 0)$.
   - From (1): R is 8 m East of S $\implies R = (8, 0)$. P is 5 m North of R $\implies P = (8, 5)$.
   - From (2): T is 8 m West of S $\implies T = (-8, 0)$. Q is 5 m South of T $\implies Q = (-8, -5)$.
   - Position of P relative to Q:
     - Horizontal displacement: $8 - (-8) = 16$ m (East).
     - Vertical displacement: $5 - (-5) = 10$ m (North).
     - Thus, Point P is North-East of Point Q.
   - **Combined statements are sufficient**.
4. **Answer**: **Option C** (Both statements together are sufficient).

### Solution 6
1. **Evaluate Statement (1) alone**:
   - Let the initial average weight be $A$ and the sum of weights of 10 people be $W \implies W = 10A$.
   - After 2 people (60 kg and 70 kg) leave, 8 people remain:
     $$\frac{W - 60 - 70}{8} = A - 1$$
     $$\frac{10A - 130}{8} = A - 1 \implies 10A - 130 = 8A - 8 \implies 2A = 122 \implies A = 61\text{ kg}$$
   - We get a unique average weight.
   - **Statement (1) is sufficient**.
2. **Evaluate Statement (2) alone**:
   - Let initial sum of weights be $W = 10A$.
   - After 2 new people (50 kg and 60 kg) join, there are 12 people:
     $$\frac{W + 50 + 60}{12} = A + 0.5$$
     $$\frac{10A + 110}{12} = A + 0.5 \implies 10A + 110 = 12A + 6 \implies 2A = 104 \implies A = 52\text{ kg}$$
   - We get a unique average weight.
   - **Statement (2) is sufficient**.
3. **Answer**: **Option D** (Each statement alone is sufficient).

### Solution 7
1. **Evaluate Statement (1) alone**:
   - Compare "sky is bright" ("pi la ko") and "sun is hot" ("ko ze mu").
   - Common word: "is" $\to$ Common code: "ko".
   - This leaves "bright" as either "pi" or "la".
   - **Statement (1) is NOT sufficient**.
2. **Evaluate Statement (2) alone**:
   - Compare "bright sun shines" ("pi mu ra") and "shines like star" ("ra de ga").
   - Common word: "shines" $\to$ Common code: "ra".
   - This leaves "bright" as either "pi" or "mu".
   - **Statement (2) is NOT sufficient**.
3. **Combine Statements (1) and (2)**:
   - From (1), "bright" is either "pi" or "la".
   - From (2), "bright" is either "pi" or "mu".
   - The intersection of both sets of possible codes is "pi".
   - Thus, "bright" is coded as "pi".
   - **Combined statements are sufficient**.
4. **Answer**: **Option C** (Both statements together are sufficient).
