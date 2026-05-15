# Quick Start Guide

## 🚀 Fastest Way to Play (Browser)

**Option 1: Immediate Browser Play**
1. Open the file `game.html` in your web browser
2. Click "Start Game"
3. Begin matching words!

No installation needed. Works on Windows, Mac, or Linux.

---

## 📦 Desktop App Version (Electron)

**Option 2: Full Desktop Application**

### Prerequisites
- Node.js installed (download from https://nodejs.org/)

### Installation & Run
```bash
# Navigate to project folder
cd word-match-game

# Install dependencies (one-time only)
npm install

# Start the game
npm start
```

---

## 🎮 How to Play

1. **Start the Game** - Click the "Start Game" button
2. **Match Words** - Click an English word (RED), then click its Spanish translation (CYAN)
3. **Advance** - Complete all pairs to move to the next level
4. **Score Points** - Each correct match = 10 points
5. **Game Ends** - After 2 minutes OR press ESC

---

## 📊 Difficulty Progression

| Level | Pairs | Speed | Features |
|-------|-------|-------|----------|
| 1-3   | 5-8   | 1x    | Basic words |
| 4-6   | 8-11  | 1.3-1.9x | Medium difficulty |
| 7+    | 12-15 | 1.9x+ | Complex words & phrases |

---

## 🎯 Tips & Tricks

- **Memory**: Try to remember word positions before they move
- **Focus**: Concentrate on one region of the screen at a time
- **Speed**: Difficulty increases gradually, not suddenly
- **Simple Starts**: Earlier levels use common, basic vocabulary
- **Challenge**: Higher levels introduce phrases and harder words

---

## 🔧 Troubleshooting

| Problem | Solution |
|---------|----------|
| Words not visible | Make sure game started (click Start button) |
| Clicks not working | Click in the center of the word box |
| Slow performance | Close other applications, check browser/system resources |
| Game not starting | Try the browser version (game.html) first |

---

## 📁 Files in This Project

- **game.html** ← Start here for browser play!
- **index.html** - Electron version UI
- **main.js** - Electron application entry point
- **renderer.js** - Game logic and canvas rendering
- **words.json** - 800+ English-Spanish word pairs
- **preload.js** - Security configuration for Electron
- **package.json** - Project dependencies

---

## 💡 Features

✅ 800+ word pairs
✅ Smooth physics-based animation
✅ Adaptive difficulty system
✅ Score tracking
✅ Level progression
✅ Time tracking
✅ Beautiful gradient UI
✅ Works on desktop & browser
✅ No lag or stuttering

---

## 📞 Need Help?

**Browser version won't load?**
- Make sure you're opening game.html with a modern browser (Chrome, Firefox, Edge, Safari)
- Check that the file path is correct

**Electron version issues?**
- Make sure Node.js is installed: `node --version`
- Try deleting `node_modules` folder and running `npm install` again
- Check that all files (.js, .json, .html) are in the same directory

---

**Enjoy the game! 🎮🎉**

For the full documentation, see README.md
