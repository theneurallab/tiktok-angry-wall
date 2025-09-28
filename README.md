# Angry Walls Game

A Python implementation of an endless runner game with obstacle avoidance mechanics using Pygame, inspired by classic mobile runner games.

## Requirements

- Python 3.6+
- Pygame library

## Steps to Run this Codebase

1. Fork this repository: `https://github.com/theneurallab/tiktok-angry-wall.git`
2. Clone your forked repository (replace `YOUR_USERNAME` with your actual GitHub username):

```bash
git clone https://github.com/YOUR_USERNAME/tiktok-angry-wall.git
```

3. Navigate to the project directory:

```bash
cd tiktok-angry-wall
```

4. Run the game:

```bash
python main.py
```

## Game Controls:

- **Mouse Click**: Start game from home screen or restart after game over
- **Mouse Hold & Drag**: Move the red bird left and right during gameplay
- **ESC**: Quit game at any time

## Project Structure

```
tiktok-angry-wall/
├── main.py                   # Main game loop and logic
├── objects.py                # Game object classes (Player, Bar, Ball, Block, ScoreCard, Message,Particle)
├── assets/                   # Game graphics
│   ├── red.png               # Player bird sprite
│   ├── block.jpeg            # Animated block texture
│   └── backgrounds/          # Background images
│       ├── bg1.jpg           # Background variant 1
│       ├── bg2.jpeg          # Background variant 2
│       ├── bg3.jpg           # Background variant 3
│       ├── bg4.jpg           # Background variant 4
│       └── home.jpeg         # Home screen background
├── sounds/                   # Sound effects
│   ├── coin.mp3              # Score collection sound
│   ├── death.mp3             # Game over sound
│   └── move.mp3              # Movement sound effect
├── fonts/                    # Game fonts for UI text
│   ├── BubblegumSans-Regular.ttf    # Score font
│   ├── Robus-BWqOd.otf              # Title font
│   ├── DebugFreeTrial-MVdYB.otf     # UI font
│   ├── Aladin-Regular.ttf           # Additional font
│   ├── DalelandsUncialBold-82zA.ttf # Additional font
│   └── QUIGLEYW.TTF                 # Additional font
└── README.md                 # Project documentation
```

Made with ❤️ by [Neural Lab](https://theneurallab.com)
