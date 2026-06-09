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

### Problem 4 (Opposite Letter Coding)
In a certain code language, `PRISM` is written as `KIRHN`. How will `LIGHT` be written in that same code language?

### Problem 5 (Cross-Shifting)
In a certain code language, `BREAKING` is written as `AERBGNIK`. How will `COMPUTER` be written in that same code language?

### Problem 6 (Number Coding)
If `WORK` is coded as `4-12-9-16`, how will `PLAY` be coded?

### Problem 7 (Substitution Coding)
In a certain code:
- "truth is eternal" is written as "3a 2b 7c"
- "enmity is temporary" is written as "7c 9a 8b"
- "truth and enmity" is written as "1a 2b 8b"
Which code represents the word "eternal"?

### Problem 8 (Continuous Shifts)
If `GOLD` is written as `IQNF`, how will `WIND` be written in that same code language?

### Problem 9 (Mixed Letter & Number Coding)
If `DANGER` is coded as `8-2-28-14-10-36`, how will `SAFETY` be coded in that same code language?

### Problem 10 (Substitution Coding)
In a certain code language:
- "study hard get success" is written as "ka la ma ta"
- "success is very important" is written as "ta na pa ra"
- "hard work is important" is written as "ka sa na pa"
- "study work get rewards" is written as "la ma sa da"
What is the code for the word "rewards"?

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

### Solution 4
1. **Understand the opposite letter mapping**:
   - Check the mapping of `PRISM` to `KIRHN`:
     - P opposite is K (16 + 11 = 27)
     - R opposite is I (18 + 9 = 27)
     - I opposite is R (9 + 18 = 27)
     - S opposite is H (19 + 8 = 27)
     - M opposite is N (13 + 14 = 27)
   - The pattern is replacing each letter with its opposite letter in the alphabet.
2. **Apply to `LIGHT`**:
   - L opposite is **O**
   - I opposite is **R**
   - G opposite is **T**
   - H opposite is **S**
   - T opposite is **G**
3. **Answer**: `ORTSG`.

### Solution 5
1. **Analyze the pattern in `BREAKING` $\to$ `AERBGNIK`**:
   - Split the 8-letter word in half: `BREA` and `KING`.
   - Reverse the first half: `BREA` $\to$ `AERB`.
   - Reverse the second half: `KING` $\to$ `GNIK`.
   - Combine the two halves: `AERBGNIK`.
2. **Apply to `COMPUTER`**:
   - Split in half: `COMP` and `UTER`.
   - Reverse the first half: `COMP` $\to$ `PMOC`.
   - Reverse the second half: `UTER` $\to$ `RETU`.
   - Combine: `PMOCRETU`.
3. **Answer**: `PMOCRETU`.

### Solution 6
1. **Analyze the code for `WORK`**:
   - W: Forward rank = 23, Reverse rank = 27 - 23 = 4
   - O: Forward rank = 15, Reverse rank = 27 - 15 = 12
   - R: Forward rank = 18, Reverse rank = 27 - 18 = 9
   - K: Forward rank = 11, Reverse rank = 27 - 11 = 16
   - The code is formed by the reverse ranks of the letters separated by hyphens.
2. **Apply to `PLAY`**:
   - P: Forward rank = 16, Reverse rank = 27 - 16 = 11
   - L: Forward rank = 12, Reverse rank = 27 - 12 = 15
   - A: Forward rank = 1, Reverse rank = 27 - 1 = 26
   - Y: Forward rank = 25, Reverse rank = 27 - 25 = 2
3. **Assemble the code**:
   - `11-15-26-2`
4. **Answer**: `11-15-26-2`.

### Solution 7
1. **Compare sentences to identify words**:
   - Compare "truth is eternal" ("3a 2b 7c") and "enmity is temporary" ("7c 9a 8b").
     - Common word: "is". Common code: "7c".
     - Thus, **is = 7c**.
   - Compare "truth is eternal" ("3a 2b 7c") and "truth and enmity" ("1a 2b 8b").
     - Common word: "truth". Common code: "2b".
     - Thus, **truth = 2b**.
2. **Find the code for "eternal"**:
   - The first sentence "truth is eternal" is coded as "3a 2b 7c".
   - We know **truth = 2b** and **is = 7c**.
   - The remaining word "eternal" must correspond to the remaining code **3a**.
3. **Answer**: The code is **3a**.

### Solution 8
1. **Analyze the pattern in `GOLD` $\to$ `IQNF`**:
   - G $+ 2 = $ I
   - O $+ 2 = $ Q
   - L $+ 2 = $ N
   - D $+ 2 = $ F
   - The pattern is a shift of $+2$ for all letters.
2. **Apply to `WIND`**:
   - W $+ 2 = $ Y
   - I $+ 2 = $ K
   - N $+ 2 = $ P
   - D $+ 2 = $ F
3. **Answer**: `YKPF`.

### Solution 9
1. **Analyze the pattern in `DANGER` $\to$ `8-2-28-14-10-36`**:
   - Write down the forward ranks of the letters in `DANGER`:
     - D = 4, A = 1, N = 14, G = 7, E = 5, R = 18.
   - Multiply each forward rank by 2:
     - D: $4 \times 2 = 8$
     - A: $1 \times 2 = 2$
     - N: $14 \times 2 = 28$
     - G: $7 \times 2 = 14$
     - E: $5 \times 2 = 10$
     - R: $18 \times 2 = 36$
   - Combine with hyphens: `8-2-28-14-10-36`.
2. **Apply the pattern to `SAFETY`**:
   - Write down the forward ranks:
     - S = 19, A = 1, F = 6, E = 5, T = 20, Y = 25.
   - Multiply each rank by 2:
     - S: $19 \times 2 = 38$
     - A: $1 \times 2 = 2$
     - F: $6 \times 2 = 12$
     - E: $5 \times 2 = 10$
     - T: $20 \times 2 = 40$
     - Y: $25 \times 2 = 50$
3. **Assemble the code**:
   - `38-2-12-10-40-50`
4. **Answer**: `38-2-12-10-40-50`.

### Solution 10
1. **Compare sentences to isolate words and their codes**:
   - Compare "study hard get success" ("ka la ma ta") and "hard work is important" ("ka sa na pa").
     - Common word: "hard". Common code: "ka". Thus, **hard = ka**.
   - Compare "study hard get success" ("ka la ma ta") and "success is very important" ("ta na pa ra").
     - Common word: "success". Common code: "ta". Thus, **success = ta**.
   - Compare "hard work is important" ("ka sa na pa") and "study work get rewards" ("la ma sa da").
     - Common word: "work". Common code: "sa". Thus, **work = sa**.
2. **Determine "rewards" from the fourth sentence**:
   - Sentence 4: "study work get rewards" $\to$ "la ma sa da".
   - We know **work = sa**.
   - Comparing Sentence 1 "study hard get success" ("ka la ma ta") and Sentence 4 "study work get rewards" ("la ma sa da"), the common words are "study" and "get", and their common codes are "la" and "ma".
   - Therefore, {"study", "get"} corresponds to {"la", "ma"}.
   - The remaining word in Sentence 4 is "rewards" and the remaining code is "da".
3. **Answer**: The code for "rewards" is **da**.
