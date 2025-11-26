# Word Guessing Game

An interactive word guessing game in Lithuanian, inspired by Wordle. The game allows you to play with words of different lengths - from 3 to 8 letters.

## Features

- **6 levels**: play with words from 3, 4, 5, 6, 7, or 8 letters
- **Lithuanian letters**: full support for Ą, Č, Ę, Ė, Į, Š, Ų, Ū, Ž
- **Color coding**:
  - Green - letter is in the correct position
  - Yellow - letter is in the word but wrong position
  - Gray - letter is not in the word

## How to Run

### 1. Clone the project
```bash
git clone https://github.com/vasarine/Lithuanian-word-game.git
cd Lithuanian-word-game
```

### 2. Start a local server

**Python 3:**
```bash
python -m http.server 8000
```

### 3. Open in browser
```
http://localhost:8000/zaidimas_lygiai.html
```

## How to Play

1. Select a level (3-8 letters)
2. Guess the word in 6 attempts
3. Watch the colors and adjust your guesses
4. Win by guessing the correct word!
