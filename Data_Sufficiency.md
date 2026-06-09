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
