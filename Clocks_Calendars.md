# Quantitative Aptitude: Clocks & Calendars

## 1. Concept Definitions & Explanations

### Clocks
- **Clock Face**: A circle divided into 12 equal hours and 60 equal minute spaces.
- **Hour Hand Speed**: Covers $360^\circ$ in 12 hours.
  - Speed $= 30^\circ/\text{hour} = 0.5^\circ/\text{minute}$.
- **Minute Hand Speed**: Covers $360^\circ$ in 60 minutes.
  - Speed $= 6^\circ/\text{minute}$.
- **Relative Speed**: The minute hand gains $5.5^\circ$ per minute ($6^\circ - 0.5^\circ$) over the hour hand.

### Calendars
- **Odd Days**: The remainder left when total number of days is divided by 7. This is used to determine weekdays.
- **Ordinary Year**: 365 days (52 weeks + 1 odd day).
- **Leap Year**: 366 days (52 weeks + 2 odd days).
  - A year is a leap year if it is divisible by 4, unless it is a century year (ending in 00).
  - Century years must be divisible by 400 to be leap years. E.g., 2000 is a leap year, but 1900 is not.

---

## 2. Key Formulas & Shortcuts

### Clock Angles
The angle $\theta$ between the hour hand and the minute hand at $H$ hours and $M$ minutes is:
$$\theta = \left| 30H - \frac{11}{2}M \right|$$
*Note: If the result is greater than $180^\circ$, find the reflex angle by subtracting it from $360^\circ$.*

### Calendar Odd Days Reference
- **Odd Days in Centuries**:
  - 100 years $= 5$ odd days
  - 200 years $= 3$ odd days
  - 300 years $= 1$ odd day
  - 400 years $= 0$ odd days
  - *Multiples of 400 years (800, 1200, 1600, 2000) have 0 odd days.*

- **Odd Days in Months**:
  - Jan, Mar, May, Jul, Aug, Oct, Dec (31 days) $= 3$ odd days
  - Apr, Jun, Sep, Nov (30 days) $= 2$ odd days
  - Feb (28 days) $= 0$ odd days
  - Feb (29 days) $= 1$ odd day

- **Weekday Mapping Table**:

| Odd Days | Day of Week |
| :---: | :--- |
| **0** | Sunday |
| **1** | Monday |
| **2** | Tuesday |
| **3** | Wednesday |
| **4** | Thursday |
| **5** | Friday |
| **6** | Saturday |

---

## 3. Practice Problems

### Problem 1
Find the angle between the hour hand and the minute hand of a clock at 8:20.

### Problem 2
What was the day of the week on 15th August 1947?

### Problem 3
If 9th June 2026 is a Tuesday, what day of the week will 9th June 2030 be?

### Problem 4
At what time between 4 and 5 o'clock will the hands of a clock be together (coincide)?

### Problem 5
A clock is set right at 5 a.m. The clock loses 16 minutes in 24 hours. What will be the true time when the clock indicates 10 p.m. on the 4th day?

### Problem 6
If the 1st of January 2001 was a Monday, what day of the week was the 1st of January 2002?

### Problem 7
How many times do the hands of a clock stand at right angles to each other in a day (24 hours)?

### Problem 8
What is the number of odd days in 400 years?

---

## 4. Step-by-Step Solutions

### Solution 1
1. **Identify parameters**:
   - $H = 8$, $M = 20$.
2. **Apply the Clock Angle Formula**:
   $$\theta = \left| 30(8) - \frac{11}{2}(20) \right|$$
   $$\theta = \left| 240 - 11 \times 10 \right|$$
   $$\theta = \left| 240 - 110 \right| = 130^\circ$$
3. **Answer**: The angle between the hands is **$130^\circ$**.

### Solution 2
1. **Break down the years**:
   - We need to calculate odd days up to 15th August 1947.
   - Period completed: 1946 years + period from Jan 1st to Aug 15th, 1947.
2. **Calculate odd days for 1946 years**:
   - Split 1946 into parts: $1600 \text{ years} + 300 \text{ years} + 46 \text{ years}$.
     - 1600 years $= 0$ odd days (multiple of 400).
     - 300 years $= 1$ odd day.
     - 46 years contains:
       - $46 \div 4 = 11$ leap years.
       - $46 - 11 = 35$ ordinary years.
       - Odd days in 46 years $= (11 \times 2) + (35 \times 1) = 22 + 35 = 57$ days.
       - Convert to weekly remainder: $57 \div 7 = 8$ weeks + $1$ odd day.
   - Total odd days for 1946 years $= 0 + 1 + 1 = 2$ odd days.
3. **Calculate odd days for Jan 1 to Aug 15, 1947**:
   - 1947 is an ordinary year (Feb has 28 days).
   - Monthly odd days:
     - Jan (3) + Feb (0) + Mar (3) + Apr (2) + May (3) + Jun (2) + Jul (3) + 15 days in August.
     - Sum $= 3 + 0 + 3 + 2 + 3 + 2 + 3 + 15 = 31$ days.
     - Convert to weekly remainder: $31 \div 7 = 4$ weeks + $3$ odd days.
4. **Total cumulative odd days**:
   - Total $= 2 \text{ (from years)} + 3 \text{ (from months)} = 5$ odd days.
5. **Map to Weekday**:
   - 5 corresponds to **Friday**.
6. **Answer**: 15th August 1947 was a **Friday**.

### Solution 3
1. **Analyze year differences from 2026 to 2030**:
   - 2026 (remaining) to 2030.
   - Number of years elapsed $= 4$ years.
2. **Find the number of leap years in this span**:
   - The year 2028 is a leap year.
   - Leap years $= 1$, Ordinary years $= 3$.
3. **Calculate total odd days**:
   - Odd days $= (1 \times 2) + (3 \times 1) = 2 + 3 = 5$ odd days.
4. **Determine the new day**:
   - Add 5 days to Tuesday:
     - Tuesday + 5 days = Sunday.
5. **Answer**: 9th June 2030 will be a **Sunday**.

### Solution 4
1. **Understand hand coincidence conditions**:
   - Hands coincide when the angle $\theta = 0$.
   - The time is between 4 and 5, so $H = 4$. Let the minute be $M$.
2. **Apply the Clock Angle formula**:
   - $\theta = \left| 30H - \frac{11}{2}M \right| \implies 0 = 30(4) - \frac{11}{2}M$
   - $\frac{11}{2}M = 120 \implies M = \frac{240}{11} = 21\frac{9}{11}$ minutes.
3. **Answer**: The hands will coincide at **$21\frac{9}{11}$ minutes past 4**.

### Solution 5
1. **Calculate total elapsed time indicated by the clock**:
   - Start: 5 a.m. Day 1.
   - End: 10 p.m. Day 4.
   - Day 1 (5 a.m.) to Day 4 (5 a.m.) $= 3 \text{ days} = 72 \text{ hours}$.
   - Day 4 (5 a.m.) to Day 4 (10 p.m.) $= 17 \text{ hours}$.
   - Total indicated time $= 72 + 17 = 89$ hours.
2. **Determine the relation between incorrect and correct time**:
   - The clock loses 16 minutes in 24 hours.
   - Indicated time in 24 hours $= 23 \text{ hours } 44 \text{ minutes} = 23\frac{44}{60} \text{ hours} = 23\frac{11}{15} \text{ hours} = \frac{356}{15}$ hours.
   - Thus, $\frac{356}{15}$ hours of incorrect clock $= 24$ hours of correct clock.
3. **Calculate the correct time for 89 indicated hours**:
   - $\text{True time} = 89 \times \frac{24}{356/15} = 89 \times \frac{24 \times 15}{356} = 89 \times \frac{360}{356}$.
   - Note that $356 = 4 \times 89$.
   - $\text{True time} = \frac{360}{4} = 90$ hours.
4. **Determine the true end time**:
   - The correct elapsed time is 90 hours (which is 1 hour more than the indicated 89 hours).
   - Therefore, the true time is 1 hour ahead of 10 p.m.
   - True time $= 11$ p.m.
5. **Answer**: The true time is **11 p.m.**.

### Solution 6
1. **Analyze year differences**:
   - 2001 is an ordinary year (not divisible by 4).
   - Therefore, 2001 has 365 days.
2. **Calculate odd days**:
   - 365 days $= 52 \text{ weeks} + 1 \text{ odd day}$.
3. **Determine the new day**:
   - Monday + 1 odd day = Tuesday.
4. **Answer**: 1st of January 2002 was a **Tuesday**.

### Solution 7
1. **Analyze clock right angle occurrences**:
   - In 1 hour, the hands are at right angles twice (except between 2-3 and 8-9, where they are at right angle only once each, or rather, the transitions at 3:00 and 9:00 are shared).
   - Specifically:
     - In a 12-hour period, right angles occur 22 times.
2. **Calculate for a full day (24 hours)**:
   - In 24 hours, they will be at right angles $22 \times 2 = 44$ times.
3. **Answer**: The hands are at right angles **44 times** in a day.

### Solution 8
1. **Break down 400 years**:
   - 100 years $= 5$ odd days.
   - 200 years $= 3$ odd days.
   - 300 years $= 1$ odd day.
2. **Calculate for 400 years**:
   - 400 years $= 4 \times (\text{odd days in 100 years}) + 1 \text{ leap day (since the 400th year is a leap year)}$.
   - Odd days $= 4 \times 5 + 1 = 21$ days.
   - $21 \div 7 = 3$ weeks with remainder $0$ odd days.
3. **Answer**: The number of odd days in 400 years is **0**.
