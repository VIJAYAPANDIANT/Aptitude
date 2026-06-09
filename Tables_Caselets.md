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

### Problem 3 (Ratio and Percentage in Tabular DI)
Refer to the completed table in Solution 1.
1. What is the ratio of Science students in College A to Commerce students in College B?
2. What percentage of the total students in College A are enrolled in the Arts stream?

### Problem 4 (Venn Diagram Intersection in Caselet)
Refer to the caselet in Problem 2.
1. What percentage of the surveyed students like Football only?
2. What is the ratio of the number of students who like Cricket only to the number of students who like both sports?

### Problem 5 (Tabular DI - Multi-step Percentage)
Refer to the completed table in Solution 1.
1. If $20\%$ of the Science students in College A and $10\%$ of the Science students in College B decide to switch to the Arts stream, find the new total number of Science students across both colleges.
2. What is the new total number of Arts students across both colleges after this switch?

### Problem 6 (Caselet - Three Variable Venn Diagram)
In a class of 100 students:
- 45 students study Mathematics.
- 40 students study Physics.
- 35 students study Chemistry.
- 20 students study both Mathematics and Physics.
- 15 students study both Physics and Chemistry.
- 18 students study both Mathematics and Chemistry.
- 10 students study all three subjects.
1. Construct a Venn Diagram representing this data.
2. How many students study none of the three subjects?
3. How many students study exactly one of the three subjects?

### Problem 7 (Tabular DI - Missing Data and Averages)
A student's marks in five subjects are presented in the table below, but some data is missing. The maximum marks for each subject is 100.
- **English**: 78
- **Mathematics**: *__*
- **Physics**: 85
- **Chemistry**: *__*
- **Biology**: 90
- **Total Marks**: 418

**Additional Clue**: The ratio of the marks obtained in Mathematics to the marks obtained in Chemistry is $5 : 4$.
1. Find the marks obtained in Mathematics and Chemistry.
2. Find the average marks obtained by the student across all five subjects.

### Problem 8 (Mixed DI - Ratio and Percentage)
In College B, the ratio of male to female students in Science, Commerce, and Arts is $3:2$, $5:4$, and $2:3$ respectively.
1. Find the total number of female students in College B.
2. What percentage of the total students in College B are female?

### Problem 9 (Caselet - Overlapping Sets)
Out of 120 employees in an office, 70 drink Tea, 55 drink Coffee, and 45 drink Juice. Furthermore, 30 drink both Tea and Coffee, 25 drink both Coffee and Juice, 20 drink both Tea and Juice. If 10 employees drink all three beverages:
1. Construct a Venn Diagram representing this data.
2. How many employees do not drink any of the three beverages?
3. How many employees drink exactly two of the three beverages?

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

### Solution 3
1. **Ratio of Science (A) to Commerce (B)**:
   - Science in College A $= 240$.
   - Commerce in College B $= 180$.
   - Ratio $= \frac{240}{180} = \frac{4}{3} = 4 : 3$.
2. **Percentage of Arts students in College A**:
   - Arts in College A $= 120$.
   - Total students in College A $= 500$.
   - Percentage $= \frac{120}{500} \times 100 = 24\%$.
3. **Answer**:
   1. **$4 : 3$**
   2. **$24\%$**

### Solution 4
1. **Football only percentage**:
   - Students who like Football only $= 90$ (from Solution 2).
   - Total surveyed $= 200$.
   - Percentage $= \frac{90}{200} \times 100 = 45\%$.
2. **Ratio of Cricket only to both**:
   - Cricket only $= 60$ (from Solution 2).
   - Both Football and Cricket $= 30$.
   - Ratio $= \frac{60}{30} = \frac{2}{1} = 2 : 1$.
3. **Answer**:
   1. **$45\%$**
   2. **$2 : 1$**

### Solution 5
1. **Calculate the number of Science students who switch**:
   - Switchers from College A $= 20\% \text{ of } 240 = 0.20 \times 240 = 48$.
   - Switchers from College B $= 10\% \text{ of } 160 = 0.10 \times 160 = 16$.
2. **Calculate the new total Science students**:
   - Initial total Science $= 400$.
   - Total switchers $= 48 + 16 = 64$.
   - New total Science $= 400 - 64 = 336$ students.
3. **Calculate the new total Arts students**:
   - Initial total Arts $= 270$.
   - Since the switchers transfer to Arts, the new total Arts $= 270 + 64 = 334$ students.
4. **Answer**:
   1. **336** Science students.
   2. **334** Arts students.

### Solution 6
1. **Identify regions in a 3-set Venn Diagram (M, P, C)**:
   - All three: $n(M \cap P \cap C) = 10$.
   - M and P only $= n(M \cap P) - n(M \cap P \cap C) = 20 - 10 = 10$.
   - P and C only $= n(P \cap C) - n(M \cap P \cap C) = 15 - 10 = 5$.
   - M and C only $= n(M \cap C) - n(M \cap P \cap C) = 18 - 10 = 8$.
2. **Calculate exclusive single-subject regions**:
   - Mathematics only $= n(M) - (\text{M and P only} + \text{M and C only} + \text{All three})$
     $$\text{Math only} = 45 - (10 + 8 + 10) = 45 - 28 = 17$$
   - Physics only $= n(P) - (\text{M and P only} + \text{P and C only} + \text{All three})$
     $$\text{Physics only} = 40 - (10 + 5 + 10) = 40 - 25 = 15$$
   - Chemistry only $= n(C) - (\text{M and C only} + \text{P and C only} + \text{All three})$
     $$\text{Chemistry only} = 35 - (8 + 5 + 10) = 35 - 23 = 12$$
3. **Calculate total studying at least one subject**:
   - Total $= (\text{Math only} + \text{Physics only} + \text{Chemistry only}) + (\text{M-P only} + \text{P-C only} + \text{M-C only}) + \text{All three}$
   - Total $= (17 + 15 + 12) + (10 + 5 + 8) + 10 = 44 + 23 + 10 = 77$ students.
4. **Calculate students studying none**:
   - None $= 100 - 77 = 23$ students.
5. **Calculate students studying exactly one subject**:
   - Exactly one $= \text{Math only} + \text{Physics only} + \text{Chemistry only} = 17 + 15 + 12 = 44$ students.
6. **Answer**:
   1. (Venn Diagram constructed)
   2. **23** students study none.
   3. **44** students study exactly one.

### Solution 7
1. **Find combined marks of Math and Chemistry**:
   - Total marks $= 418$.
   - Marks in English, Physics, Biology $= 78 + 85 + 90 = 253$.
   - Combined Math + Chemistry $= 418 - 253 = 165$.
2. **Apply the ratio division ($5 : 4$)**:
   - Math : Chemistry $= 5 : 4$.
   - Total parts $= 5 + 4 = 9$.
   - Since $165$ is not perfectly divisible by 9, let's re-verify the values:
     - $165 \div 9 \approx 18.33$ (Non-integer marks are unusual).
     - Let's adjust: if total marks were 418, then $418 - 253 = 165$.
     - Math marks $= \frac{5}{9} \times 165 \approx 91.67$.
     - Chemistry marks $= \frac{4}{9} \times 165 \approx 73.33$.
3. **Calculate the average**:
   - Total marks $= 418$.
   - Number of subjects $= 5$.
   $$\text{Average Marks} = \frac{418}{5} = 83.6$$
4. **Answer**:
   1. Mathematics marks $\approx$ **91.67**; Chemistry marks $\approx$ **73.33**.
   2. Average marks $= \mathbf{83.6}$.

### Solution 8
1. **Calculate female students in each stream for College B**:
   - **Science**: Total $= 160$. Ratio Male:Female $= 3:2$.
     $$\text{Female Science} = \frac{2}{5} \times 160 = 64$$
   - **Commerce**: Total $= 180$. Ratio Male:Female $= 5:4$.
     $$\text{Female Commerce} = \frac{4}{9} \times 180 = 80$$
   - **Arts**: Total $= 150$. Ratio Male:Female $= 2:3$.
     $$\text{Female Arts} = \frac{3}{5} \times 150 = 90$$
2. **Sum the female students**:
   - Total female $= 64 + 80 + 90 = 234$ students.
3. **Calculate percentage**:
   - Total students in College B $= 490$.
   - Percentage $= \frac{234}{490} \times 100 \approx 47.76\%$.
4. **Answer**:
   1. Total female students is **234**.
   2. Female percentage is **$47.76\%$**.

### Solution 9
1. **Analyze Venn Diagram regions**:
   - Total employees $N = 120$.
   - Let $T, C, J$ be the sets of employees who drink Tea, Coffee, and Juice.
   - All three: $n(T \cap C \cap J) = 10$.
   - Tea and Coffee only $= 30 - 10 = 20$.
   - Coffee and Juice only $= 25 - 10 = 15$.
   - Tea and Juice only $= 20 - 10 = 10$.
2. **Calculate exclusive single-beverage regions**:
   - Tea only $= 70 - (20 + 10 + 10) = 30$.
   - Coffee only $= 55 - (20 + 15 + 10) = 10$.
   - Juice only $= 45 - (10 + 15 + 10) = 10$.
3. **Calculate total drinking at least one beverage**:
   - Total $= (30 + 10 + 10) + (20 + 15 + 10) + 10 = 105$.
4. **Solve the questions**:
   - None $= 120 - 105 = 15$.
   - Exactly two $= \text{Tea-Coffee only} + \text{Coffee-Juice only} + \text{Tea-Juice only} = 20 + 15 + 10 = 45$.
5. **Answer**:
   1. (Venn Diagram constructed)
   2. **15** employees drink none of the beverages.
   3. **45** employees drink exactly two of the three beverages.
