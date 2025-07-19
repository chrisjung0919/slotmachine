# 🎰 Python Slot Machine

A fun command-line slot machine game written in Python! Test your luck by spinning for fruits and symbols to win multipliers based on matching combinations.

## 💡 Features

- 5 different symbols: 🍒 🍉 🍋 🔔 ⭐  
- Randomized spins using Python’s `random` module  
- Betting system with balance tracking  
- Symbol-based payout multipliers  
- Replayable until funds run out or the player quits

## 🕹 How to Play

1. Run the program.  
2. Start with a balance of **$100**.  
3. Enter a bet amount for each spin.  
4. If all three symbols match, you win a payout based on the symbol:
   - 🍒 — 3x your bet  
   - 🍉 — 4x your bet  
   - 🍋 — 5x your bet  
   - 🔔 — 10x your bet  
   - ⭐ — 20x your bet  
5. Otherwise, you lose your bet.  
6. Continue playing until you choose to stop or your balance hits $0.

## 🧾 Example Gameplay

```
*******************************
Welcome to Python Slot Machine!
Symbols: 🍒 🍉 🍋 🔔 ⭐
*******************************
Current balance: $100
Place your bet amount: 10
Spinning...

*************
🍉 | 🍉 | 🍉
*************
You won 40
Do you want to spin again? (Y/N):
```

## 🛠 Requirements

- Python 3.x  
- No external libraries required

## ▶️ Run the Game

```bash
python slotmachine.py
```

## 🙏 Credit

This program is based on the YouTube tutorial by **Bro Code**:  
🎥 [Python Slot Machine Game | Bro Code](https://www.youtube.com/watch?v=f5J3YiZ3XX8&list=WL&index=2)

Thanks to Bro Code for the great tutorial!
