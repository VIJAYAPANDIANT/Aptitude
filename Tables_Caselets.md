# Data Interpretation: Tables & Caselets

## 1. Concept Definitions & Explanations

- **Tabular DI**: Data presented systematically in columns and rows.
- **Missing Data Tables**: Tabular sets where some cell values are omitted. You must use headers, row/column totals, or auxiliary conditions given in the instructions to calculate the missing values.
- **Caselets**: Paragraph-style descriptions of data. There are no charts or tables. You must extract the numerical data yourself and construct a table or a Venn Diagram to solve the questions.
- **Mixed DI**: Sets containing more than one type of data source (e.g., a Pie Chart showing distribution of items, and a Table showing the ratio of defective to non-defective items).

---

## 2. Practice Problems

### Problem 1 (Missing Data Table)
The table below shows the distribution of students in three different streams (Science, Commerce, Arts) across two colleges, A and B. Some data is missing.

| College | Science | Commerce | Arts | Total |
| :---: | :---: | :---: | :---: | :---: |
| **A** | 240 | *__* | 120 | 500 |
| **B** | *__* | 180 | 150 | *__* |
| **Total** | 400 | 320 | *__* | *__* |

**Additional Clue**: The ratio of Science students in College A to College B is $3 : 2$.
1. Fill in the missing values in the table.
2. Find the total number of students in College B.

### Problem 2 (Caselet)
In a school survey of 200 students regarding their sports preferences:
- 120 students like Football.
- 90 students like Cricket.
- 30 students like both Football and Cricket.
1. Construct a Venn Diagram representing this data.
2. How many students do not like either Football or Cricket?

---

## 3. Step-by-Step Solutions

### Solution 1
1. **Find Science students in College B**:
   - Science students in College A $= 240$.
   - Ratio Science(A) : Science(B) $= 3 : 2$.
   - Let Science(B) $= x$.
     $$\frac{240}{x} = \frac{3}{2} \implies 3x = 480 \implies x = 160$$
   - Place **160** in the `College B - Science` cell.
2. **Verify Total Science students**:
   - Total Science $= 240 + 160 = 400$. (Matches the table).
3. **Find Commerce students in College A**:
   - Total Commerce students $= 320$.
   - Commerce students in College B $= 180$.
   - Commerce students in College A $= 320 - 180 = 140$.
   - Place **140** in the `College A - Commerce` cell.
4. **Find Total Arts students**:
   - Arts in College A $= 120$.
   - Arts in College B $= 150$.
   - Total Arts $= 120 + 150 = 270$.
   - Place **270** in the `Total - Arts` cell.
5. **Find Total students in College B**:
   - Total College B $= \text{Science} + \text{Commerce} + \text{Arts} = 160 + 180 + 150 = 490$.
   - Place **490** in the `College B - Total` cell.
6. **Find Grand Total of students**:
   - Grand Total $= \text{Total College A} + \text{Total College B} = 500 + 490 = 990$.
   - Place **990** in the bottom-right corner.

#### Completed Table:
| College | Science | Commerce | Arts | Total |
| :---: | :---: | :---: | :---: | :---: |
| **A** | 240 | **140** | 120 | 500 |
| **B** | **160** | 180 | 150 | **490** |
| **Total** | 400 | 320 | **270** | **990** |

**Answer**: Total students in College B is **490**.

### Solution 2
1. **Analyze the Venn Diagram components**:
   - Total students $N = 200$.
   - Let $F$ be the set of students who like Football, and $C$ be the set of students who like Cricket.
   - Both Football and Cricket $n(F \cap C) = 30$.
2. **Calculate exclusive regions**:
   - Students who like Football only $= n(F) - n(F \cap C) = 120 - 30 = 90$.
   - Students who like Cricket only $= n(C) - n(F \cap C) = 90 - 30 = 60$.
3. **Calculate total students who like at least one sport ($n(F \cup C)$)**:
   $$n(F \cup C) = \text{Football only} + \text{Cricket only} + \text{Both}$$
   $$n(F \cup C) = 90 + 60 + 30 = 180$$
   - *(Alternative formula: $n(F \cup C) = n(F) + n(C) - n(F \cap C) = 120 + 90 - 30 = 180$)*
4. **Calculate students who like neither**:
   $$\text{Neither} = \text{Total} - n(F \cup C) = 200 - 180 = 20$$
5. **Answer**: There are **20** students who do not like either Football or Cricket.
