# Logical Reasoning: Coding & Decoding

## 1. Alphabet Reference Chart

In coding/decoding questions, letters are mapped to numbers. Memorizing the forward and backward ranks of alphabets is essential.

### EJOTY Shortcut
Use the word **EJOTY** to remember key forward positions (multiples of 5):
- **E** = 5
- **J** = 10
- **O** = 15
- **T** = 20
- **Y** = 25

### Forward & Reverse Positions
For any letter:
$$\text{Forward Rank} + \text{Reverse Rank} = 27$$

### Reverse Pairs (Opposite Letters)
Opposite letters are pairs that sum to 27:
- **A – Z** (AZ)
- **B – Y** (BY)
- **C – X** (CruX)
- **D – W** (DeW)
- **E – V** (EVen)
- **F – U** (FUll)
- **G – T** (GT Road)
- **H – S** (High School)
- **I – R** (Indian Railway)
- **J – Q** (Jack & Queen)
- **K – P** (KP Tower)
- **L – O** (LOve)
- **M – N** (MaN)

---

## 2. Common Coding Patterns

1. **Letter Shifting**: Shifting letters forward/backward by a fixed value. E.g., `CAT` $\to$ `DBU` (shift of $+1$).
2. **Reverse/Opposite Coding**: Replacing letters with their opposites. E.g., `BAG` $\to$ `YZT`.
3. **Cross-Shifting**: Splitting a word in half and crossing the letters.
4. **Number Coding**: Mapping words to numbers using their place value sums.
5. **Substitution (Chinese Coding)**: Grouping sentences and codes together to solve by word elimination.

---

## 3. Practice Problems

### Problem 1 (Letter Shift)
In a certain code language, `COMPUTER` is written as `RFUVQNPC`. How will `MEDICINE` be written in that same code language?

### Problem 2 (Number Coding)
If `BAT` $= 23$ and `CAT` $= 24$, find the value of `BALL`.

### Problem 3 (Substitution Coding)
In a code language:
- "sky is blue" is written as "mud pot ko"
- "blue color pen" is written as "ko ra ze"
- "sky has color" is written as "mud ra pi"
What is the code for the word "has"?

---

## 4. Step-by-Step Solutions

### Solution 1
1. **Analyze the pattern in `COMPUTER` $\to$ `RFUVQNPC`**:
   - Split the word into individual letters and notice the first and last letters:
     - The first letter `C` goes to the end `C`.
     - The last letter `R` goes to the beginning `R`.
   - Now check the inner letters: `O M P U T E` $\to$ `F U V Q N P` (written in reverse order):
     - `O` $+ 1 = $ `P` (placed second to last).
     - `M` $+ 1 = $ `N` (placed third to last).
     - `P` $+ 1 = $ `Q` (placed fourth to last).
     - `U` $+ 1 = $ `V`.
     - `T` $+ 1 = $ `U`.
     - `E` $+ 1 = $ `F` (placed second).
   - Summary: Reverse the word, then add $+1$ to all middle letters while keeping original first/last letters.
2. **Apply the pattern to `MEDICINE`**:
   - First and last letters: Swap `M` and `E` $\to$ Starts with `E`, ends with `M`.
   - Reverse the inner letters `E D I C I N` $\to$ `N I C I D E`.
   - Add $+1$ to each of these reversed inner letters:
     - `N` $+ 1 = $ `O`
     - `I` $+ 1 = $ `J`
     - `C` $+ 1 = $ `D`
     - `I` $+ 1 = $ `J`
     - `D` $+ 1 = $ `E`
     - `E` $+ 1 = $ `F`
3. **Assemble the final code**:
   - `E` + `O J D J E F` + `M` = `EOJDJEFM`.
4. **Answer**: `EOJDJEFM`.

### Solution 2
1. **Check place values**:
   - `BAT` $= B(2) + A(1) + T(20) = 23$.
   - `CAT` $= C(3) + A(1) + T(20) = 24$.
   - The code is simply the sum of forward alphabetical ranks.
2. **Calculate value for `BALL`**:
   - `BALL` $= B(2) + A(1) + L(12) + L(12) = 27$.
3. **Answer**: The value is **27**.

### Solution 3
1. **Compare sentences to isolate words**:
   - Compare "sky is blue" ("mud pot ko") and "blue color pen" ("ko ra ze").
     - Common word: "blue". Common code: "ko".
     - Thus, **blue = ko**.
   - Compare "blue color pen" ("ko ra ze") and "sky has color" ("mud ra pi").
     - Common word: "color". Common code: "ra".
     - Thus, **color = ra**.
   - Compare "sky is blue" ("mud pot ko") and "sky has color" ("mud ra pi").
     - Common word: "sky". Common code: "mud".
     - Thus, **sky = mud**.
2. **Find the code for "has"**:
   - Look at the third sentence: "sky has color" coded as "mud ra pi".
   - We know **sky = mud** and **color = ra**.
   - The remaining word is "has" and the remaining code is "pi".
   - Therefore, **has = pi**.
3. **Answer**: The code is **pi**.
