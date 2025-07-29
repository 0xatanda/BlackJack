# 🃏 Blackjack Game in Python

## Overview

This is a **text-based Blackjack game** implemented in Python. The game allows a user to play against a computer-controlled dealer. It simulates a simplified version of Blackjack (also known as 21), including deck shuffling, card dealing, hand evaluation, and game outcomes.

---

## Features

* Simulates a **realistic deck of 52 cards**
* **Player vs Dealer** gameplay
* Automatic handling of:

  * Aces (as 1 or 11)
  * Blackjack detection
  * Dealer behavior (hits until 17 or more)
* Multiple rounds of gameplay
* Clear and user-friendly console output

---

## Gameplay Instructions

1. **Start the game** by specifying how many rounds you want to play.
2. The deck is shuffled and two cards are dealt to both the player and the dealer.
3. The player can choose to:

   * **Hit** (draw another card)
   * **Stand** (end their turn)
4. The dealer reveals their cards and follows the rule: hit until reaching **at least 17**.
5. Winner is decided based on Blackjack rules:

   * Closest to 21 without going over
   * Blackjack beats any other hand
   * Busting (going over 21) results in an automatic loss

---

## How to Run

### Requirements

* Python 3.x

### Running the Game

1. Clone this repository or copy the script files locally.
2. Run the game using:

```bash
python blackjack.py
```

3. Follow the prompts in the terminal.

---

## Example Interaction

```
How many games do you want to play? 1

******************************
Game 1 of 1
******************************
Your hand:
9 of hearts
7 of clubs
Value: 16

Dealer's hand:
hidden
5 of spades

Please choose 'Hit' or 'Stand': hit
...
```

---

## File Structure

| File           | Description                           |
| -------------- | ------------------------------------- |
| `blackjack.py` | Main game script containing all logic |
| `README.md`    | Game documentation (this file)        |

---

## Possible Enhancements

* Add betting system and chips
* Track win/loss statistics
* Support for multiple players
* GUI version using Tkinter or PyGame

---

## License

This project is open-source and free to use for learning or educational purposes.

---

