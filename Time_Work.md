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
