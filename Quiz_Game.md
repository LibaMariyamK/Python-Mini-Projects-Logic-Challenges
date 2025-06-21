# 🧠 Python Quiz Game with Score Tracking

A menu-driven **Python Quiz Game** that allows users to answer multiple-choice questions, get feedback, track scores, and store results in a file. The game uses dictionaries, functions, loops, and file handling to offer an interactive learning experience.

---

## ✅ Features

### 🔸 Core Functionalities

1. **Quiz Questions Structure**
   - Questions are stored using a **list of dictionaries**.
   - Each question contains:
     - The question text
     - 4 options (A, B, C, D)
     - The correct answer key (e.g., "B")

2. **Quiz Game Flow**
   - Questions are displayed one-by-one in a loop.
   - User inputs an answer and gets **immediate feedback**.
   - Final score is displayed after the quiz ends.
   - List of correctly answered questions is shown.

3. **Interactive Menu**
```

\=== PYTHON QUIZ GAME ===

1. Start Quiz
2. View Last Score
3. View Score History (Last 5 Sessions)
4. Clear Score History
5. Exit

````

4. **Score Tracking**
- Results are saved to `quiz_scores.txt` after each session.
- Each entry includes:
  - Player name
  - Score (e.g., 7/10)
  - (Optional) Timestamp

5. **Session Summary**
- After completing the quiz:
  ```
  Your Score: 7/10
  Correct Answers: Q1, Q3, Q6...
  ```

6. **Error Handling**
- Handles:
  - Invalid inputs (non A/B/C/D)
  - File errors
  - Re-prompts for valid choices

---

## 💡 Bonus Features (Optional)

1. **Timed Questions**
- Limit each answer to 10 seconds using the `time` module.

2. **Difficulty Levels**
- Allow players to choose Easy, Medium, or Hard questions.

3. **Export Score Summary**
- Export the current session's result to a file (e.g., `my_quiz_result.txt`).

4. **Player Name**
- Ask for and store the player’s name with their score.

---

## 🧪 Sample File Entry (`quiz_scores.txt`)

````

Alice | Score: 7/10
Bob | Score: 5/10
Carol | Score: 9/10

```

> With timestamp (bonus format):
```

2025-06-21 12:10:32 | Alice | Score: 7/10

````

---

