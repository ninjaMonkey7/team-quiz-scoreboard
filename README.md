# Lowest Score Wins: team quiz scoreboard

A single-page scoreboard for a team quiz where the **lowest total wins**. Every answer is scored 0 to 100. A wrong answer scores 100, and a 0 is a pointless answer.

## Use it in a deck

1. Copy the GitHub Pages URL for this repo.
2. In PowerPoint, select a shape or text, then **Insert → Link** and paste the URL.
3. In slideshow mode, click the link. The scoreboard opens in your browser.
4. Press **F** for full screen. Switch back to the deck with Cmd+Tab (Mac) or Alt+Tab (Windows).

Scores are saved in that browser, so you can switch between the deck and the scoreboard all game.

## Scoring an answer

1. Click a team card, or press its number key (**1** to **8**).
2. Type the answer's score. Nothing you type shows on screen, not even how many digits, just "Ready ✓".
3. Press **Enter**. The column counts down from 100 to the score.
4. Press **Enter** again to move to the next team.

Shortcuts in the score panel: **P** pointless (0), **W** wrong (100), **A** another answer for the same team, **Esc** back to the board.

## Final round

One team gets a question with three answers (A, B, C) and picks one. The goal is a pointless answer.

1. **Before the game:** click **Final round**, then pick the team (it defaults to the current leader) and enter the question, the three answers and each answer's score. Scores stay hidden as "Set ✓"; tick **Show scores** to check them. Everything is saved in the browser.
2. **On the night:** click **Final round**, then **Show on screen**. The question and answers fill the TV.
3. When the team decides, click their answer or press **A**, **B** or **C**. It's highlighted gold as their pick.
4. Press **Enter** (or **Reveal**). The column counts down to that answer's score. A 0 gets a gold "Pointless!" win with confetti.
5. Press **Enter** again to reveal the other two answers one at a time, then **Back to board**.

The final round doesn't change the team totals.

## Board controls

| Control | What it does |
| --- | --- |
| Title | Click to rename the game |
| Round − / + or **N** | Change round; new scores are tagged with it |
| **Undo** or **U** | Remove the last score |
| Score chip on a card | Click to remove that one score |
| **Teams** | Rename, recolour, add or remove teams (up to 8); start a new game; reset |
| Speed | Countdown speed: Slow (default, 0 takes 9s), Medium (6s) or Fast (3.4s) |
| Sound | Turn the countdown sound on or off |

## Hosting

The page is one static `index.html` with no dependencies. GitHub Pages serves it from the `main` branch root.
