# Pig Game 🐷🎲

A classic two-player dice game developed in **JavaScript**, **HTML**, and **CSS**. The first player to reach **100 points** wins\!

-----

## 🕹️ How to Play

The Pig Game is a simple yet engaging game of risk and reward.

### The Objective

The goal is to be the first player to accumulate a total score of **100 points** or more.

### Gameplay Rules

1.  **Start:** The game begins with **Player 1** as the active player.
2.  **Rolling:**
      * The active player clicks the **"Roll Dice"** button.
      * The number rolled is added to their **CURRENT** (turn) score.
3.  **Holding:**
      * The active player clicks the **"Hold"** button to end their turn.
      * Their **CURRENT** score is added to their **GLOBAL** (total) score.
      * The turn passes to the other player.
4.  **Losing the Turn (The Pig):**
      * If a player rolls a **1**, they immediately lose their entire **CURRENT** score (it resets to 0).
      * The turn automatically passes to the other player.
5.  **Winning:**
      * The first player to reach a **GLOBAL** score of **100** or more wins the game\!
6.  **New Game:** Click the **"New Game"** button to reset all scores and start over.

-----

## 💻 Technologies Used

  * **JavaScript:** Core game logic and functionality.
  * **HTML5:** Game structure and interface.
  * **CSS3:** Styling and visual design.

-----

## 🚀 Getting Started

Follow these simple steps to run the game locally on your machine.

### Prerequisites

You only need a modern web browser (like Chrome, Firefox, Safari, or Edge) to play the game.

### Installation

1.  **Clone the repository:**

    ```bash
    git clone [Your-Repo-URL-Here]
    ```

2.  **Navigate to the project directory:**

    ```bash
    cd pig-game
    ```

3.  **Open the file:**
    Simply open the `index.html` file in your preferred web browser.

    **(or double-click the `index.html` file in your file explorer)**

-----

## ✨ Features

  * **Two-Player Mode:** Competitive play between two human players.
  * **Interactive Dice:** A visual representation of the dice roll.
  * **Active Player Indicator:** Clear visual cues to show whose turn it is.
  * **New Game Functionality:** Quick restart button to begin a new round.
  * **Score Tracking:** Separate displays for **Current** (turn) and **Global** (total) scores.

-----

## 📝 Future Enhancements

  * Add a computer opponent (AI).
  * Implement a feature to change the winning score limit.
  * Include sound effects for rolling and winning.

-----

## ✍️ Author

  * **MrCoser** - `https://github.com/MrCoser`
-----

## 📜 License

This project is licensed under the **[MIT License / other desired license]** - see the `LICENSE.md` file for details.