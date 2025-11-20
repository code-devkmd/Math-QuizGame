## 🧠 Math Quiz Challenge

A highly interactive and challenging front-end math quiz game built with vanilla HTML, CSS, and JavaScript. The game features a timed challenge format, multiple difficulty levels, and tracks the user's high score using local storage.

## ✨ Features

  -  **Timed Gameplay:** Players have 60 seconds to answer as many questions as possible.

  -  **Dynamic Difficulty:** Choose between three levels that introduce different operations and number ranges:

     -   **Easy:** Simple Addition (+)

     -   **Medium:** Addition (+) and Subtraction (-)

     -   **Hard:** Addition (+), Subtraction (-), and Multiplication (x)

  -  **Scoring System:**

     -   **Correct Answer:** +10 points and +2 seconds bonus time.

     -   **Wrong Answer:** -5 points (score cannot drop below 0).

  -  **High Score Tracking:** Your best score is saved in the browser's local storage and displayed persistently.

  -  **Interactive Feedback:** Instant visual and textual feedback (✅ Correct! / ❌ Wrong!) using CSS animations.

  -  **Game Over Screen:** A clear summary screen displaying the final score when the time runs out.

  -  **Keyboard Input:** Questions can be answered by typing in the input field and pressing the Enter key.

## 🛠️ Technologies Used

This is a pure front-end application contained within a single file.

  -  **HTML5:** Structure of the quiz game.

  -  **CSS3:** Styling, animations (pop, shake), and responsive design.

  -  **Vanilla JavaScript (ES6+):** Game logic, score management, timer control, problem generation, and high score persistence using localStorage.

## 🚀 How to Play (Setup and Launch)

Since this application is a single self-contained HTML file (index.html), no server, environment, or dependencies (like Python/Flask) are required to run it.

  1.  **Save the file:** Ensure you have saved the provided code as index.html.

  2.  **Open in Browser:** Double-click the index.html file. It will open directly in your web browser (Chrome, Firefox, Edge, etc.).

## 🎮 Game Instructions

1. **Select a Level:** Choose Easy, Medium, or Hard from the "Level" dropdown menu.

2. **Start the Challenge:** Click the "Start Challenge" button. The timer will begin counting down from 60 seconds.

3. **Answer Questions:** Read the question, type your numerical answer into the input field, and press Enter or click Submit.

4. **Watch the Timer:** Pay attention to the timer in the Stats Bar. It will turn red when you have 10 seconds remaining.

5. **Game Over:** The game ends when the timer reaches 0. The Game Over screen will appear, showing your final score and the option to play again.

6. **High Score:** The "Best" score is updated automatically if you beat your previous record.# Math-QuizGame
