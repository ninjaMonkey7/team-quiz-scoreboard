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
2. Type the answer's score. It shows as dots so the room can't see it.
3. Press **Enter**. The column counts down from 100 to the score.
4. Press **Enter** again to move to the next team.

Shortcuts in the score panel: **P** pointless (0), **W** wrong (100), **A** another answer for the same team, **Esc** back to the board.

## Board controls

| Control | What it does |
| --- | --- |
| Title | Click to rename the game |
| Round − / + or **N** | Change round; new scores are tagged with it |
| **Undo** or **U** | Remove the last score |
| Score chip on a card | Click to remove that one score |
| **Teams** | Rename, recolour, add or remove teams (up to 8); start a new game; reset |
| Sound | Turn the countdown sound on or off |

## Hosting

The page is one static `index.html` with no dependencies. GitHub Pages serves it from the `main` branch root.
