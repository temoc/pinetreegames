# Pine Tree Games 🌲🎮

A collection of fun, browser-based games built with HTML5 Canvas and JavaScript.

**🎮 Play Now:** [https://temoc.github.io/pinetreegames/](https://temoc.github.io/pinetreegames/)

## 📁 Repository Structure

```
pinetreegames/
├── index.html              # Main landing page with game gallery
├── games/
│   ├── tennis-pong/       # Tennis Pong game
│   │   └── index.html
│   ├── table-tennis/      # Coming soon
│   ├── darts/             # Coming soon
│   └── mini-golf/         # Coming soon
└── README.md
```

## 🎮 Games Collection

### 1. Tennis Pong 🎾 [LIVE]
A retro-style tennis game with realistic physics and authentic tennis scoring!

**[Play Tennis Pong](https://temoc.github.io/pinetreegames/games/tennis-pong/)**

#### Features
- 🎾 **Realistic Tennis Scoring** - Love, 15, 30, 40, Deuce, Advantage
- 🎵 **Authentic Racquet Sounds** - Real "thwack" impact audio
- 🎨 **Tennis Court Graphics** - Green court with white lines
- 🎯 **Challenging Gameplay** - Fast ball speed, smaller racquets
- 😂 **Pickleball Taunt** - Losers get roasted!

#### Controls
- **Left Player**: `W` (up) / `S` (down)
- **Right Player**: `↑` (up) / `↓` (down)
- **Start/Pause**: `SPACE`

#### Gameplay
- First to win **3 games** wins the match
- Each game uses standard tennis scoring (0, 15, 30, 40)
- Ball speed increases with each hit (max speed: 18!)
- Deuce and Advantage rules apply
- Loser gets sent to play pickleball 🥒

#### Technical Stats
- Initial ball speed: 8 units/frame
- Max ball speed: 18 units/frame
- Racquet speed: 9 units/frame
- Racquet size: 15x70 pixels
- Ball radius: 8 pixels

### 2. Table Tennis Pro 🏓 [COMING SOON]
Master spin shots and smashes in this realistic table tennis simulator.

### 3. Dart Master 🎯 [COMING SOON]
Precision aiming and strategy in classic pub dart game.

### 4. Mini Golf ⛳ [COMING SOON]
Navigate challenging courses with obstacles and tricky angles.

## 🚀 How to Play Locally

1. Clone this repository:
```bash
git clone https://github.com/temoc/pinetreegames.git
cd pinetreegames
```

2. Open the main page or a specific game:
```bash
# Open main landing page
start index.html

# Or open a specific game
start games/tennis-pong/index.html
```

3. No build process needed - just HTML, CSS, and JavaScript!

## 🛠 Technology Stack

- **HTML5 Canvas** - Graphics rendering
- **Vanilla JavaScript** - Game logic and physics
- **Web Audio API** - Realistic sound effects
- **CSS3** - Styling and animations

## 🎨 Adding New Games

Each game lives in its own folder under `games/`:

1. Create a new folder: `games/your-game-name/`
2. Add `index.html` with your game code
3. Update the main `index.html` to add your game card
4. Update this README

## 📄 License

MIT License - Feel free to use and modify!

## 🤝 Contributing

Want to add a game? Open a PR! All games must:
- Be playable in the browser (HTML5 Canvas preferred)
- Have clear controls and instructions
- Be fun and polished
- Include your own assets (no copyrighted content)

---

**Pine Tree Games - Where winners play tennis and losers play pickleball!** 🎾🥒🌲

🤖 Built with [Claude Code](https://claude.com/claude-code)
