# Quantitative Aptitude: Probability

## 1. Concept Definitions & Explanations

- **Random Experiment**: An experiment whose outcome cannot be predicted with certainty.
- **Sample Space ($S$)**: The set of all possible outcomes of a random experiment.
- **Event ($E$)**: A subset of the Sample Space. E.g., getting an even number in a die roll: $E = \{2, 4, 6\}$.
- **Mutually Exclusive Events**: Events that cannot happen at the same time. If $A$ and $B$ are mutually exclusive, $A \cap B = \emptyset$.
- **Independent Events**: Two events are independent if the occurrence of one does not affect the probability of the occurrence of the other.

---

## 2. Key Formulas & Shortcuts

### Basic Probability
$$P(E) = \frac{\text{Number of favorable outcomes } n(E)}{\text{Total number of possible outcomes } n(S)}$$
- $0 \le P(E) \le 1$
- $P(E') = 1 - P(E)$ *(where $E'$ is the complement/non-occurrence of event $E$)*

### Addition Theorem of Probability
- **For any two events $A$ and $B$**:
  $$P(A \cup B) = P(A) + P(B) - P(A \cap B)$$
- **If $A$ and $B$ are Mutually Exclusive**:
  $$P(A \cup B) = P(A) + P(B)$$

### Multiplication Theorem of Probability
- **If $A$ and $B$ are Independent**:
  $$P(A \cap B) = P(A) \times P(B)$$

### Cards Reference (52-Card Deck)
- **Total Cards** $= 52$
- **Suits** $= 4$ (Spades $\spadesuit$, Clubs $\clubsuit$ - Black; Hearts $\heartsuit$, Diamonds $\diamondsuit$ - Red), 13 cards each.
- **Face Cards** $= 12$ (4 Jacks, 4 Queens, 4 Kings).
- **Aces** $= 4$ (not considered face cards).

---

## 3. Practice Problems

### Problem 1
Two unbiased dice are rolled simultaneously. Find the probability that the sum of the numbers on the two dice is exactly 8.

### Problem 2
One card is drawn at random from a pack of 52 cards. What is the probability that the card drawn is either a Red Card or a King?

### Problem 3
A bag contains 5 red, 4 blue, and 3 green balls. If three balls are drawn at random, what is the probability that 2 are red and 1 is blue?

### Problem 4
What is the probability of getting a sum of 9 from two throws of a single die?

### Problem 5
Three unbiased coins are tossed. What is the probability of getting at least two heads?

### Problem 6
Two cards are drawn together from a pack of 52 cards. What is the probability that both the cards are kings?

### Problem 7
The probability that A can solve a problem is $\frac{2}{3}$ and that B can solve it is $\frac{3}{5}$. If both try, what is the probability that the problem is solved?

### Problem 8
A card is drawn from a pack of 52 cards. What is the probability that the card drawn is a spade or an ace?

---

## 4. Step-by-Step Solutions

### Solution 1
1. **Find size of Sample Space ($n(S)$)**:
   - When rolling two dice, each die has 6 faces.
   - $n(S) = 6 \times 6 = 36$.
2. **Find Favorable Outcomes ($n(E)$)**:
   - The pairs whose sum is 8 are:
     $$E = \{(2,6), (3,5), (4,4), (5,3), (6,2)\}$$
   - $n(E) = 5$.
3. **Calculate Probability**:
   $$P(E) = \frac{n(E)}{n(S)} = \frac{5}{36}$$
4. **Answer**: The probability is **$\frac{5}{36}$**.

### Solution 2
1. **Identify parameters**:
   - Total cards $n(S) = 52$.
   - Let $A$ be the event of drawing a Red Card.
   - Let $B$ be the event of drawing a King.
2. **Calculate individual probabilities**:
   - There are 26 Red Cards: $P(A) = \frac{26}{52}$.
   - There are 4 Kings: $P(B) = \frac{4}{52}$.
   - There are 2 Red Kings (King of Hearts and King of Diamonds): $P(A \cap B) = \frac{2}{52}$.
3. **Apply the Addition Theorem**:
   $$P(A \cup B) = P(A) + P(B) - P(A \cap B)$$
   $$P(A \cup B) = \frac{26}{52} + \frac{4}{52} - \frac{2}{52} = \frac{28}{52} = \frac{7}{13}$$
4. **Answer**: The probability is **$\frac{7}{13}$**.

### Solution 3
1. **Calculate total number of ways to draw 3 balls ($n(S)$)**:
   - Total balls in bag $= 5 + 4 + 3 = 12$.
   - Choosing 3 balls from 12:
     $$n(S) = 12C_3 = \frac{12 \times 11 \times 10}{3 \times 2 \times 1} = 220$$
2. **Calculate favorable combinations ($n(E)$)**:
   - We need 2 Red balls (from 5) AND 1 Blue ball (from 4).
     $$n(E) = 5C_2 \times 4C_1 = 10 \times 4 = 40$$
3. **Calculate Probability**:
   $$P(E) = \frac{n(E)}{n(S)} = \frac{40}{220} = \frac{2}{11}$$
4. **Answer**: The probability is **$\frac{2}{11}$**.

### Solution 4
1. **Find size of Sample Space ($n(S)$)**:
   - Rolling a die twice gives $n(S) = 6 \times 6 = 36$ outcomes.
2. **Find Favorable Outcomes ($n(E)$)**:
   - Pairs whose sum is 9:
     $$E = \{(3,6), (4,5), (5,4), (6,3)\}$$
   - $n(E) = 4$.
3. **Calculate Probability**:
   - $P(E) = \frac{4}{36} = \frac{1}{9}$.
4. **Answer**: The probability is **$\frac{1}{9}$**.

### Solution 5
1. **Find Sample Space ($n(S)$)**:
   - Tossing 3 coins: $n(S) = 2^3 = 8$.
   - $S = \{HHH, HHT, HTH, HTT, THH, THT, TTH, TTT\}$.
2. **Find Favorable Outcomes ($n(E)$) for "at least 2 heads"**:
   - Out of the 8 outcomes, those containing 2 or 3 heads:
     $$E = \{HHH, HHT, HTH, THH\}$$
   - $n(E) = 4$.
3. **Calculate Probability**:
   - $P(E) = \frac{4}{8} = \frac{1}{2}$.
4. **Answer**: The probability is **$\frac{1}{2}$**.

### Solution 6
1. **Find Sample Space ($n(S)$)**:
   - Choosing 2 cards from 52:
     $$n(S) = 52C_2 = \frac{52 \times 51}{2 \times 1} = 1326$$
2. **Find Favorable Outcomes ($n(E)$)**:
   - Choosing 2 kings from 4 kings in the deck:
     $$n(E) = 4C_2 = \frac{4 \times 3}{2 \times 1} = 6$$
3. **Calculate Probability**:
   - $P(E) = \frac{6}{1326} = \frac{1}{221}$.
4. **Answer**: The probability is **$\frac{1}{221}$**.

### Solution 7
1. **Understand "problem is solved"**:
   - The problem is solved if at least one of them solves it.
   - It is easier to calculate the probability of the complementary event: "neither of them solves the problem".
2. **Find individual complement probabilities**:
   - Probability that A does not solve it: $P(A') = 1 - \frac{2}{3} = \frac{1}{3}$.
   - Probability that B does not solve it: $P(B') = 1 - \frac{3}{5} = \frac{2}{5}$.
3. **Find probability that neither solves the problem**:
   - Since A and B work independently:
     $$P(A' \cap B') = P(A') \times P(B') = \frac{1}{3} \times \frac{2}{5} = \frac{2}{15}$$
4. **Calculate probability that the problem is solved**:
   - $P(\text{Solved}) = 1 - P(\text{neither solves}) = 1 - \frac{2}{15} = \frac{13}{15}$.
5. **Answer**: The probability that the problem is solved is **$\frac{13}{15}$**.

### Solution 8
1. **Identify the individual events**:
   - Let $A$ be the event of drawing a Spade. There are 13 spades in a deck: $P(A) = \frac{13}{52}$.
   - Let $B$ be the event of drawing an Ace. There are 4 aces in a deck: $P(B) = \frac{4}{52}$.
2. **Identify the overlap**:
   - There is 1 Ace of Spades which is both a spade and an ace: $P(A \cap B) = \frac{1}{52}$.
3. **Apply the Addition Theorem**:
   - $P(A \cup B) = P(A) + P(B) - P(A \cap B) = \frac{13}{52} + \frac{4}{52} - \frac{1}{52} = \frac{16}{52} = \frac{4}{13}$.
4. **Answer**: The probability is **$\frac{4}{13}$**.
