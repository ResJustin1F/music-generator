# Mozart Dice Game – Python Music Generator 

This is a Python-based music generator inspired by Wolfgang Amadeus Mozart’s 1787 dice game — *Musikalisches Würfelspiel*. The program composes and plays a randomized waltz by piecing together pre-recorded musical measures based on dice rolls.

## Concept

Mozart’s original game used two parts:
- **Minuet** (16 measures, chosen using 2 dice)
- **Trio** (16 measures, chosen using 1 die)

Each measure corresponds to a `.wav` audio file. With over 10^23 combinations possible, every generated waltz is unique.

## Technologies Used

- Python 3
- `simpleaudio` (for playing `.wav` files)
- `random` (for simulating dice)
- Pre-recorded `.wav` files

## Features

- Simulates Mozart's randomized music composition logic
- Plays selected audio measures in sequence
- Organized with reusable functions for filename generation, dice rolling, and waltz construction

## ▶ How to Run

1. Install the `simpleaudio` module:
```bash
pip install simpleaudio
```

2. Ensure all audio `.wav` files are in the same folder as the script  
3. Run the program:
```bash
python musical_dice_game.py
```

## Setup Notes (Important)

To hear the generated music, you’ll need two things:

1. **Install the `simpleaudio` package**

Use one of the following commands in your terminal:

**Windows:**
```bash
python -m pip install simpleaudio --user
```

**Mac:**
```bash
python3 -m pip install simpleaudio --user
```

> If you have issues on Mac, install Homebrew first from [https://brew.sh](https://brew.sh)

---

2. **Audio Files Required**

You’ll need the `.wav` files provided in the original assignment archive. These include:

- `M###.wav` files for the Minuet section (e.g., `M96.wav`)
- `T##.wav` files for the Trio section (e.g., `T72.wav`)

Make sure all `.wav` files are in the **same folder** as `musical_dice_game.py`. The script loads and plays each file sequentially using filenames constructed from dice roll logic.

⚠ **The audio files are not included in this GitHub repo**. If you're viewing this for educational purposes and don't have the `.wav` files, you can still examine the code logic.

## What I Learned

- How to apply randomness to structured data  
- How to manage external assets (audio files) in Python  
- Timing and playback control using `simpleaudio`  

## Created by

**Justin Restrepo**  
Student – Computer Programming & Information Systems  
 Farmingdale State College  
 [LinkedIn](https://linkedin.com/in/justin-restrepo)  
 [GitHub](https://github.com/ResJustin1F)
