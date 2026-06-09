# Logical Reasoning: Syllogism

## 1. Proposition Types

Syllogisms consist of statements that make assertions about categories. There are four basic types of propositions:

1. **A-Type (Universal Affirmative)**: *"All A are B"*
   - Represented by drawing Circle A completely inside Circle B.
2. **E-Type (Universal Negative)**: *"No A is B"*
   - Represented by drawing Circle A and Circle B completely separated, with a cross-line indicating no intersection.
3. **I-Type (Particular Affirmative)**: *"Some A are B"*
   - Represented by intersecting circles A and B (there is a common area).
4. **O-Type (Particular Negative)**: *"Some A are not B"*
   - Represented by shading a part of circle A that cannot overlap with B.

---

## 2. Solving with Venn Diagrams

### Rules for Valid Deductions
- **Definite Conclusions**: A conclusion is only definitely true if it holds true in **all possible Venn diagrams** (both basic and alternative diagrams).
- **Possible Conclusions (Possibility)**: A conclusion stated with "is a possibility" is true if it holds in **at least one valid diagram**.

### Either-Or Case Rules (Complementary Pairs)
Two conclusions form an **"Either-Or"** relationship if they satisfy **all three** of the following conditions:
1. Both conclusions are individually **undetermined/false** (doubtful).
2. The subject and predicate in both conclusions are **identical** (e.g., Conclusion 1 is about "Cups and Plates" and Conclusion 2 is also about "Cups and Plates").
3. They form a **complementary pair**:
   - **Some + No** (e.g., "Some cups are plates" and "No cup is a plate")
   - **All + Some Not** (e.g., "All cups are plates" and "Some cups are not plates")

---

## 3. Practice Problems

### Problem 1
**Statements**:
- All pens are pencils.
- Some pencils are erasers.

**Conclusions**:
1. Some pens are erasers.
2. No pen is an eraser.

Decide which of the conclusions follow logically from the statements.

### Problem 2
**Statements**:
- No cat is a dog.
- All dogs are animals.

**Conclusions**:
1. Some animals are dogs.
2. No animal is a cat.

Decide which of the conclusions follow logically from the statements.

---

## 4. Step-by-Step Solutions

### Solution 1
1. **Draw the Basic Venn Diagram**:
   - "All pens are pencils" $\to$ Circle `Pen` is inside circle `Pencil`.
   - "Some pencils are erasers" $\to$ Circle `Eraser` intersects circle `Pencil`. In the basic diagram, `Eraser` does not touch `Pen`.
2. **Draw Alternative Venn Diagrams (if needed)**:
   - Since "Some pencils are erasers", the circle `Eraser` *can* expand to intersect `Pen`. So an alternative diagram exists where some pens are erasers.
3. **Evaluate Conclusions**:
   - **Conclusion 1**: "Some pens are erasers"
     - True in the alternative diagram, but False in the basic diagram. Thus, it is not a definite conclusion.
   - **Conclusion 2**: "No pen is an eraser"
     - True in the basic diagram, but False in the alternative diagram. Thus, it is not a definite conclusion.
4. **Check for "Either-Or"**:
   - Condition 1: Both are individually false/doubtful? Yes.
   - Condition 2: Subject and predicate are same? Yes (both talk about `Pen` and `Eraser`).
   - Condition 3: They form a complementary pair? Yes ("Some" + "No").
5. **Answer**: **Either Conclusion 1 or Conclusion 2 follows**.

### Solution 2
1. **Draw the Basic Venn Diagram**:
   - "No cat is a dog" $\to$ Draw `Cat` and `Dog` as separate disjoint circles.
   - "All dogs are animals" $\to$ Draw circle `Dog` completely inside circle `Animal`.
2. **Analyze intersection possibilities**:
   - Since `Dog` is inside `Animal`, and `Dog` cannot touch `Cat`, the `Animal` circle *can* still overlap with `Cat` or even contain `Cat` entirely. But `Dog` can never touch `Cat`.
3. **Evaluate Conclusions**:
   - **Conclusion 1**: "Some animals are dogs"
     - Since all dogs are inside the `Animal` circle, the region occupied by dogs is also part of animals. This is definitely true.
   - **Conclusion 2**: "No animal is a cat"
     - In the basic diagram, `Animal` and `Cat` do not touch. However, we can easily draw an alternative diagram where `Animal` intersects `Cat` without letting `Dog` touch `Cat`. Thus, this is not definitely true.
4. **Answer**: **Only Conclusion 1 follows**.
