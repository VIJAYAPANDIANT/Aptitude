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
