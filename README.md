# Coxswain Calls

A simple flash card game for learning crew coxswain commands, when to use them, and steering basics.

## How to play
Open `index.html` in any browser (phone, tablet or computer). Nothing to install.

- **Play**: multiple-choice cards. Some show a situation and ask for the command; others show a command and ask what it means.
- **Study**: flip cards to review everything before playing.
- **Categories**: tap the chips at the top to focus on one area (Land & Carrying, Launch & Dock, On the Water, Race & Rate Calls, Steering & Safety).
- **Keyboard**: press 1–4 to answer and Enter for the next card. In Study, use the arrow keys and Space to flip.

## Scoring
- Each correct answer in a row is worth more than the last: the 1st is +1, the 2nd +2, the 3rd +3, and so on.
- One wrong answer resets your streak and score to **0**.
- The high score and best streak are saved on this device's browser.
- Cards you miss come back sooner.

## Editing the cards
All cards are in the `DECK` list inside `index.html`. Each card has `cmd` (the call), `when` (when to use it), `tip`, a category `c`, and an illustration `art`. Programs word some calls differently, so edit them to match what his coach uses.
