# 🎲 The Doomed Dice Challenge

## 📜 Problem Statement
You are given two six-sided dice, **Die A** and **Die B**, each with faces numbered from **1 to 6**. You can only roll both dice together, and your turn is guided by the sum obtained from rolling them.

However, the mischievous Norse God **Loki** has cursed your dice by removing all the spots! You must reattach the spots while maintaining the original probability distribution of sums.

---

## 📝 Part A: Understanding Dice Probabilities and Distributions

### ✅ Tasks:
1. **Total Combinations Calculation**
   - Compute the total number of possible outcomes when rolling two six-sided dice.
   
2. **Sum Distribution Matrix**
   - Create a **6x6 matrix** showing all possible sums when rolling both dice.
   
3. **Probability Calculation**
   - Compute the probability of obtaining each possible sum (2 to 12).
   
---

## 🛠️ Part B: Restoring Doomed Dice While Maintaining Probabilities

### 🔥 Challenge:
Loki cursed the dice with these conditions:
- **Die A** cannot have more than **4 spots** on a face.
- **Die A** may have **multiple faces with the same number of spots**.
- **Die B** can have any number of spots on a face, even more than 6.

### 🚀 Solution:
Implement a function **`undoom_dice(Die_A, Die_B)`** to transform the dice while ensuring the probability of obtaining each sum remains unchanged.

### ✅ Final Restored Dice:
```python
New Die A: [1, 2, 2, 3, 3, 4]
New Die B: [1, 3, 4, 5, 6, 8]
```
These dice maintain the **original probability distribution** and allow the game to continue! 🎲✨

---

## 📌 How to Run the Code
1. Clone the repository:
   ```bash
   git clone https://github.com/Selvakumar1904/-Doomed-Dice-Challenge.git


   ```
2. Navigate to the directory:
   ```bash
   cd Doomed-Dice-Challenge
   ```
3. Run the Python script:
   ```bash
   python doomed_dice.py
   ```

---

## 🏆 Conclusion
This challenge demonstrated an interesting application of **probability, combinatorics, and mathematical transformations**. Loki’s curse was lifted by redistributing the spots cleverly! 🎭⚡

---

### 🔗 References
- Probability Theory
- Combinatorics
- Dice Game Strategies
