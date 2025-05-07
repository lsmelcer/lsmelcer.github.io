# 👨‍💻 Louis Smelcer

Welcome to my personal website! I'm a high school senior, getting ready to go to college to study computer science.

## 🚀 Projects

Below is a collection of some of my favorite coding projects. Click on the project titles to learn more.

---

### 🎰 [Diamond Shores Casino](https://github.com/lsmelcer/CSC-134/blob/main/finalProject_smelcer.c%2B%2B)

**Description:**  
Single-player casino game focused on casino games played only against the house. It is purely the logic as the game is played in the console. 

**Tech Stack:**  
`C++`

**Features:**
- 5 casino games supported
- Chips based betting system
- Menu system
- Modular structure

**🃏Black Jack Features:**
- Uses a full deck of 52 cards with suits and ranks.
- Card drawing and shuffling using standard C++ vector and randomization.
- Supports player-dealer comparison with hit/stand logic.
- Implements splitting if the player has two cards of the same rank.
- Dealer draws according to typical rules (stands at 17 or higher).
- Outcome resolution logic for each hand (win, lose, tie).
- Uses lambda functions for reusability in comparing hands.

**🎲Craps Features:**
- Implements standard craps rules:
 - First roll: win on 7/11, lose on 2/3/12, else set a “point.”
 - Subsequent rolls aim to match the point before rolling a 7.
- Dice rolling simulated using rand() and modulo arithmetic.

**🎡Roulette Features:**
- Supports multiple simultaneous bets per round:
 - Straight number, red/black, dozens, halves, even/odd.
- Simulates spinning a wheel with correct color logic.
- Calculates and applies payouts according to standard rules.
- Differentiates between winning, losing, and neutral (0) outcomes.

**🃏Baccarat Features:**
- Follows simplified Baccarat rules:
 - Player/Banker draw cards, possibly a third based on fixed rules.
 - Bets can be placed on Player, Banker, or Tie.
 - Banker win pays 0.95× (accounts for commission).
 - Tie pays 8×.
- Handles third-card logic for both Player and Banker.
- Calculates hand value modulo 10.

**🎰Slots Features:**
- Uses emojis as slot symbols for a visual touch.
- Spins 3 reels and checks for matching symbols.
- Payout is 2× bet for a triple match; otherwise, the player loses.

**Status:** Active