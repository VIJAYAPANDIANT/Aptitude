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

### Problem 3
**Statements**:
- All keys are locks.
- All locks are doors.
- Some doors are windows.

**Conclusions**:
1. Some locks are windows.
2. All keys are doors.

Decide which of the conclusions follow logically from the statements.

### Problem 4
**Statements**:
- Some actors are singers.
- All singers are dancers.
- Some dancers are directors.

**Conclusions**:
1. Some actors are dancers.
2. Some singers are directors.

Decide which of the conclusions follow logically from the statements.

### Problem 5
**Statements**:
- All apples are bananas.
- No banana is a cherry.
- Some cherries are dates.

**Conclusions**:
1. Some dates being bananas is a possibility.
2. All apples being cherries is a possibility.

Decide which of the conclusions follow logically from the statements.

### Problem 6
**Statements**:
- Some laptops are keyboards.
- No keyboard is a mouse.

**Conclusions**:
1. All laptops are mice.
2. Some laptops are not mice.

Decide which of the conclusions follow logically from the statements.

### Problem 7
**Statements**:
- All cups are saucers.
- No saucer is a spoon.
- All spoons are forks.

**Conclusions**:
1. No cup is a spoon.
2. Some forks are spoons.

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

### Solution 3
1. **Draw the Venn Diagram**:
   - "All keys are locks" $\to$ Circle `Key` is inside `Lock`.
   - "All locks are doors" $\to$ Circle `Lock` (and thus `Key`) is inside `Door`.
   - "Some doors are windows" $\to$ Circle `Door` overlaps with `Window`.
2. **Evaluate Conclusions**:
   - **Conclusion 1**: "Some locks are windows"
     - In the basic representation, `Window` only overlaps with `Door` but not `Lock`. Hence, this is not definitely true.
   - **Conclusion 2**: "All keys are doors"
     - Since `Key` is inside `Lock` and `Lock` is inside `Door`, all keys must be inside `Door`. This is definitely true.
3. **Answer**: **Only Conclusion 2 follows**.

### Solution 4
1. **Draw the Venn Diagram**:
   - "Some actors are singers" $\to$ Circle `Actor` overlaps with `Singer`.
   - "All singers are dancers" $\to$ Circle `Singer` is entirely inside `Dancer`.
   - "Some dancers are directors" $\to$ Circle `Dancer` overlaps with `Director`.
2. **Evaluate Conclusions**:
   - **Conclusion 1**: "Some actors are dancers"
     - Since the intersection of `Actor` and `Singer` lies within `Singer`, and all of `Singer` is inside `Dancer`, that intersection must also be inside `Dancer`. Hence, some actors are definitely dancers. (True)
   - **Conclusion 2**: "Some singers are directors"
     - In the basic diagram, `Director` overlaps with `Dancer` but does not touch `Singer`. Hence, this is not definitely true.
3. **Answer**: **Only Conclusion 1 follows**.

### Solution 5
1. **Draw the Venn Diagram**:
   - "All apples are bananas" $\to$ Circle `Apple` is inside `Banana`.
   - "No banana is a cherry" $\to$ `Banana` and `Cherry` circles are disjoint. Thus, `Apple` and `Cherry` are also disjoint.
   - "Some cherries are dates" $\to$ Circle `Cherry` overlaps with `Date`.
2. **Evaluate Conclusions**:
   - **Conclusion 1**: "Some dates being bananas is a possibility"
     - Although the part of `Date` that overlaps with `Cherry` cannot overlap with `Banana` (since no cherry is a banana), the remaining part of the `Date` circle is free to overlap with `Banana`. Thus, this is a valid possibility. (True)
   - **Conclusion 2**: "All apples being cherries is a possibility"
     - Since all apples are inside `Banana` and no banana can touch `Cherry`, no apple can ever touch `Cherry`. Thus, this is impossible. (False)
3. **Answer**: **Only Conclusion 1 follows**.

### Solution 6
1. **Draw the Venn Diagram**:
   - "Some laptops are keyboards" $\to$ Circle `Laptop` overlaps with `Keyboard`.
   - "No keyboard is a mouse" $\to$ `Keyboard` and `Mouse` circles are disjoint.
2. **Evaluate Conclusions**:
   - **Conclusion 1**: "All laptops are mice"
     - Since some laptops are keyboards, and no keyboard can be a mouse, those laptops that are keyboards can never be mice. Thus, all laptops can never be mice. (False)
   - **Conclusion 2**: "Some laptops are not mice"
     - The portion of `Laptop` that overlaps with `Keyboard` cannot overlap with `Mouse`. Thus, there is definitely a portion of laptops that is not mice. (True)
3. **Answer**: **Only Conclusion 2 follows**.

### Solution 7
1. **Draw the Venn Diagram**:
   - "All cups are saucers" $\to$ Circle `Cup` is inside `Saucer`.
   - "No saucer is a spoon" $\to$ `Saucer` and `Spoon` circles are disjoint. Thus, `Cup` and `Spoon` are also disjoint.
   - "All spoons are forks" $\to$ Circle `Spoon` is inside `Fork`.
2. **Evaluate Conclusions**:
   - **Conclusion 1**: "No cup is a spoon"
     - Since all cups are inside `Saucer`, and `Saucer` is completely disjoint from `Spoon`, no cup can touch `Spoon`. This is definitely true.
   - **Conclusion 2**: "Some forks are spoons"
     - Since all spoons are inside `Fork`, the area occupied by spoons belongs to forks as well. Hence, some forks are definitely spoons. (True)
3. **Answer**: **Both Conclusion 1 and Conclusion 2 follow**.
