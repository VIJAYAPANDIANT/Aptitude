# Quantitative Aptitude: Time & Work

## 1. Concept Definitions & Explanations

- **Work**: The task or job to be completed. Complete work is represented as $1$ unit (or $100\%$).
- **Efficiency (Rate of Work)**: The amount of work done by a person or machine in a unit of time (e.g., 1 day or 1 hour).
  $$\text{Efficiency} = \frac{\text{Total Work}}{\text{Total Time}}$$
- **Relation between Time and Efficiency**: Efficiency is inversely proportional to the time taken. If a person is twice as efficient as another, they will take half the time to complete the same work.
- **Wages**: Payment for work, which is distributed in the ratio of the actual work done by each person (which equals the ratio of their efficiencies if they work for the same duration).
- **Inlet Pipe**: A pipe that fills a tank (positive work).
- **Outlet Pipe (or Leak)**: A pipe/leak that empties a tank (negative work).

---

## 2. Key Formulas & Shortcuts

### Two and Three Person Formula
- If $A$ can do a piece of work in $x$ days and $B$ in $y$ days, then working together they can finish it in:
  $$\text{Time taken by (A + B)} = \frac{x \times y}{x + y} \text{ days}$$
- If $A, B,$ and $C$ can finish a work in $x, y,$ and $z$ days respectively, then together they finish in:
  $$\text{Time taken by (A + B + C)} = \frac{x \cdot y \cdot z}{xy + yz + zx} \text{ days}$$

### The Man-Day-Hour Formula (Chain Rule)
$$\frac{M_1 \times D_1 \times H_1 \times E_1}{W_1} = \frac{M_2 \times D_2 \times H_2 \times E_2}{W_2}$$
*where:*
- $M = \text{number of workers}$
- $D = \text{number of days}$
- $H = \text{number of hours per day}$
- $E = \text{efficiency of workers}$
- $W = \text{units of work completed / wages earned}$

### Pipes and Cisterns
- If inlet pipe $A$ fills a tank in $x$ hours and outlet pipe $B$ empties it in $y$ hours ($y > x$), then the net part filled in 1 hour when both are open is:
  $$\text{Net Rate} = \frac{1}{x} - \frac{1}{y}$$
- Time taken to fill the tank completely:
  $$\text{Time} = \frac{x \times y}{y - x} \text{ hours}$$

---

## 3. Practice Problems

### Problem 1
A can complete a work in 12 days and B can complete it in 18 days. They start working together, but A leaves 3 days before the completion of the work. In how many days is the work completed?

### Problem 2
A is thrice as efficient as B and is therefore able to finish a piece of work in 60 days less than B. Find the time in which they can complete the work together.

### Problem 3
Pipe A can fill a tank in 10 hours and Pipe B can fill it in 15 hours. Due to a leak at the bottom of the tank, it took 2 hours more to fill the tank. In how many hours can the leak alone empty the full tank?

### Problem 4
12 men can complete a work in 8 days. 16 women can complete the same work in 12 days. 8 men and 8 women started working together and worked for 6 days. How many more men should be added to complete the remaining work in 1 day?

### Problem 5
A and B together can do a piece of work in 12 days. B and C together can do it in 15 days, and C and A together in 20 days. In how many days can A, B, and C together complete the work?

### Problem 6
A can do a work in 15 days. He works for 5 days and then leaves. The remaining work is finished by B in 20 days. In how many days can B alone complete the whole work?

### Problem 7
Two pipes A and B can fill a tank in 24 minutes and 32 minutes respectively. If both pipes are opened together, after how many minutes should pipe B be closed so that the tank is full in 18 minutes?

### Problem 8
A, B, and C can complete a work in 10, 12, and 15 days respectively. They started working together, but A left after 2 days and B left 3 days before the completion of the work. How long did the work last?

### Problem 9
If 12 men or 18 women can reap a field in 14 days, in how many days can 8 men and 16 women reap the same field?

### Problem 10
Pipe A can fill a tank in 12 minutes and Pipe B in 18 minutes. Pipe C can empty the full tank in 15 minutes. If all three pipes are opened together in the empty tank, how much time will they take to fill the tank?

---

## 4. Step-by-Step Solutions

### Solution 1
1. **Apply the LCM Method**:
   - Time taken by A $= 12$ days.
   - Time taken by B $= 18$ days.
   - Let Total Work $= \text{LCM}(12, 18) = 36$ units.
2. **Find Efficiencies**:
   - Efficiency of A $= \frac{36}{12} = 3$ units/day.
   - Efficiency of B $= \frac{36}{18} = 2$ units/day.
3. **Analyze the work distribution**:
   - Let the total number of days the work lasted be $x$.
   - A worked for $(x - 3)$ days.
   - B worked for the entire $x$ days.
4. **Form the equation**:
   $$\text{Work done by A} + \text{Work done by B} = \text{Total Work}$$
   $$3(x - 3) + 2x = 36$$
   $$3x - 9 + 2x = 36$$
   $$5x = 45 \implies x = 9$$
5. **Answer**: The work was completed in **9 days**.

### Solution 2
1. **Express efficiencies and times**:
   - Let the efficiency of B $= 1$.
   - Efficiency of A $= 3$.
   - Ratio of times taken by A and B $= 1 : 3$ (inverse of efficiency ratio).
2. **Find the individual time periods**:
   - Let time taken by A $= t$ and B $= 3t$.
   - The difference in time is 60 days.
   $$3t - t = 60 \implies 2t = 60 \implies t = 30 \text{ days}$$
   - Thus, A takes 30 days and B takes 90 days.
3. **Calculate time together**:
   - Let Total Work $= 90$ units.
   - Efficiency of A $= 3$, Efficiency of B $= 1$, Combined Efficiency $= 4$.
   $$\text{Combined Time} = \frac{90}{4} = 22.5 \text{ days}$$
4. **Answer**: Working together, they can finish in **$22\frac{1}{2}$ days**.

### Solution 3
1. **Determine expected time without the leak**:
   - Let Total Capacity of tank $= \text{LCM}(10, 15) = 30$ units.
   - Efficiency of Pipe A $= +3$ units/hour.
   - Efficiency of Pipe B $= +2$ units/hour.
   - Net efficiency of (A + B) $= 5$ units/hour.
   - Time taken without leak $= \frac{30}{5} = 6$ hours.
2. **Determine actual time with the leak**:
   - Actual time $= 6 \text{ hours} + 2 \text{ hours} = 8$ hours.
3. **Calculate the leak's efficiency**:
   - Let the efficiency of the leak be $L$ (negative).
   - In 8 hours, the net filled capacity is 30 units:
     $$8 \times (3 + 2 - L) = 30$$
     $$5 - L = \frac{30}{8} = 3.75$$
     $$L = 5 - 3.75 = 1.25 \text{ units/hour}$$
4. **Calculate leak emptying time**:
   - Time to empty full tank $= \frac{\text{Total Capacity}}{L} = \frac{30}{1.25} = 24$ hours.
5. **Answer**: The leak alone can empty the tank in **24 hours**.

### Solution 4
1. **Calculate individual day rates**:
   - 1 Man's 1-day work $= \frac{1}{12 \times 8} = \frac{1}{96}$.
   - 1 Woman's 1-day work $= \frac{1}{16 \times 12} = \frac{1}{192}$.
2. **Use the LCM method for rates**:
   - Let Total Work $= 192$ units.
   - Efficiency of 1 Man $= 2$ units/day.
   - Efficiency of 1 Woman $= 1$ unit/day.
3. **Calculate work done in first 6 days**:
   - Combined efficiency of 8 men and 8 women:
     $$\text{Efficiency} = 8(2) + 8(1) = 24 \text{ units/day}$$
   - Work completed in 6 days $= 24 \times 6 = 144$ units.
4. **Calculate remaining work and additions**:
   - Remaining work $= 192 - 144 = 48$ units.
   - This 48 units must be finished in 1 day, meaning the target efficiency is 48 units/day.
   - Current efficiency is 24 units/day. Additional efficiency needed $= 48 - 24 = 24$ units/day.
   - Since 1 Man $= 2$ units/day, number of men to add $= \frac{24}{2} = 12$ men.
5. **Answer**: **12 more men** should be added to complete the remaining work in 1 day.

### Solution 5
1. **Represent the daily work rates**:
   - Let rates of A, B, and C be $a, b,$ and $c$ respectively.
   - $a + b = \frac{1}{12}$
   - $b + c = \frac{1}{15}$
   - $c + a = \frac{1}{20}$
2. **Find the combined rate of A, B, and C**:
   - Add all equations:
     $$2(a + b + c) = \frac{1}{12} + \frac{1}{15} + \frac{1}{20}$$
   - Find common denominator (60):
     $$2(a + b + c) = \frac{5 + 4 + 3}{60} = \frac{12}{60} = \frac{1}{5}$$
     $$a + b + c = \frac{1}{10}$$
3. **Determine the total days**:
   - Time taken $= \frac{1}{a + b + c} = 10$ days.
4. **Answer**: Working together, they can complete the work in **10 days**.

### Solution 6
1. **Find A's completed work portion**:
   - A can complete the work in 15 days, so A's 1-day rate $= \frac{1}{15}$.
   - Work done by A in 5 days $= 5 \times \frac{1}{15} = \frac{1}{3}$.
2. **Find remaining work and B's rate**:
   - Remaining work $= 1 - \frac{1}{3} = \frac{2}{3}$.
   - B completes this $\frac{2}{3}$ of the work in 20 days.
3. **Find B's total time**:
   - B's total time to complete the entire work alone:
     $$\text{Time} = 20 \times \frac{3}{2} = 30 \text{ days}$$
4. **Answer**: B alone can complete the work in **30 days**.

### Solution 7
1. **Set up the capacity and efficiencies**:
   - Let capacity of the tank $= \text{LCM}(24, 32) = 96$ units.
   - Efficiency of Pipe A $= \frac{96}{24} = 4$ units/minute.
   - Efficiency of Pipe B $= \frac{96}{32} = 3$ units/minute.
2. **Define running durations**:
   - The tank should be filled in 18 minutes. Since A is open the entire time, it runs for 18 minutes.
   - Let Pipe B be open for $X$ minutes.
3. **Form the equation**:
   - Work done by A + Work done by B = Total capacity
     $$18 \times 4 + X \times 3 = 96$$
     $$72 + 3X = 96 \implies 3X = 24 \implies X = 8$$
4. **Answer**: Pipe B must be closed after **8 minutes**.

### Solution 8
1. **Establish total work and individual rates**:
   - Let Total Work $= \text{LCM}(10, 12, 15) = 60$ units.
   - Efficiency of A $= 6$ units/day.
   - Efficiency of B $= 5$ units/day.
   - Efficiency of C $= 4$ units/day.
2. **Formulate the work equation based on durations**:
   - Let total days be $D$.
   - A worked for 2 days.
   - B worked for $(D - 3)$ days (since B left 3 days before completion).
   - C worked for all $D$ days.
3. **Solve for $D$**:
   $$\text{Work by A} + \text{Work by B} + \text{Work by C} = 60$$
   $$2(6) + (D - 3)5 + D(4) = 60$$
   $$12 + 5D - 15 + 4D = 60$$
   $$9D - 3 = 60 \implies 9D = 63 \implies D = 7$$
4. **Answer**: The work was completed in **7 days**.

### Solution 9
1. **Find individual rates**:
   - Work done by 12 men in 1 day $= \frac{1}{14}$. So, 1 man's 1-day work $= \frac{1}{12 \times 14} = \frac{1}{168}$.
   - Work done by 18 women in 1 day $= \frac{1}{14}$. So, 1 woman's 1-day work $= \frac{1}{18 \times 14} = \frac{1}{252}$.
2. **Calculate work done by 8 men and 16 women in 1 day**:
     $$\text{1-day work} = 8 \left(\frac{1}{168}\right) + 16 \left(\frac{1}{252}\right) = \frac{8}{168} + \frac{16}{252} = \frac{1}{21} + \frac{4}{63}$$
   - Find common denominator (63):
     $$\text{1-day work} = \frac{3}{63} + \frac{4}{63} = \frac{7}{63} = \frac{1}{9}$$
3. **Calculate total time**:
   - The time taken to complete the work is the reciprocal of the 1-day work:
     $$\text{Time} = 9 \text{ days}$$
4. **Answer**: The field can be reaped in **9 days**.

### Solution 10
1. **Find capacities and efficiencies**:
   - Let capacity of the tank be LCM of 12, 18, and 15, which is 180 units.
   - Efficiency of Pipe A $= \frac{180}{12} = +15$ units/minute.
   - Efficiency of Pipe B $= \frac{180}{18} = +10$ units/minute.
   - Efficiency of Pipe C $= \frac{180}{15} = -12$ units/minute (negative since it empties).
2. **Calculate net efficiency when all are open**:
   - $\text{Net Efficiency} = 15 + 10 - 12 = 13$ units/minute.
3. **Calculate time to fill**:
   - $\text{Time} = \frac{180}{13} = 13\frac{11}{13}$ minutes.
4. **Answer**: The tank will be filled in **$13\frac{11}{13}$ minutes**.
