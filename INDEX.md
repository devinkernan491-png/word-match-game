# 🎮 English-Spanish Word Matching Game

A fun, interactive word matching game with bouncing words and adaptive difficulty!

## 📋 What You Got

A complete word matching game with two versions:
- **Browser Version** (game.html) - Play immediately in any browser
- **Desktop App** (Electron) - Full featured desktop application

## ⚡ Get Started in 30 Seconds

### Fastest: Browser Play
```
1. Open: game.html
2. Click: Start Game
3. Play: Match English (RED) with Spanish (CYAN) words
4. Done!
```

### Full Desktop App
```
1. Install Node.js if needed
2. Run: npm install
3. Run: npm start
4. Play!
```

## 🎯 Game Mechanics

**Objective**: Match English words with Spanish translations

**Gameplay**:
- Words bounce dynamically across the screen
- Click an English word (red box)
- Click its Spanish translation (cyan box)
- Earn 10 points per correct match
- Advance to next level when all pairs matched

**Difficulty Increases**:
- More word pairs appear
- Words bounce faster
- Harder vocabulary introduced
- Maximum 15 word pairs

**Scoring**:
- Points: 10 per match
- Levels: 1-7+
- Time: Up to 2 minutes
- Final stats displayed at game over

## 📂 Project Structure

```
📦 Word Match Game
├── 🎮 game.html           ← START HERE (Browser)
├── 🖥️  index.html           (Electron UI)
├── 🔧 main.js            (Electron entry)
├── ⚙️  renderer.js         (Game engine)
├── 📝 words.json          (800 word pairs)
├── 🔐 preload.js          (Security)
├── 📦 package.json        (Dependencies)
├── 📖 README.md           (Full docs)
├── ⚡ QUICKSTART.md       (Quick guide)
└── 📋 INDEX.md            (This file)
```

## 🎮 How to Play

1. **Start Game** - Click "Start Game" button on title screen
2. **Understand Colors**:
   - RED boxes = English words
   - CYAN boxes = Spanish words
   - GOLD highlight = Word selected
3. **Make Matches**:
   - Click English word
   - Click matching Spanish word
   - 10 points awarded!
4. **Advance Levels**:
   - Complete all pairs → Level up
   - More pairs appear
   - Speed increases
5. **Game Over**:
   - 2 minutes elapsed, OR
   - Press ESC key

## 🎨 Features

- ✨ **Smooth Animation** - 60 FPS canvas rendering
- 🌊 **Physics Simulation** - Realistic bouncing & friction
- 📈 **Adaptive Difficulty** - Progressive challenge
- 🎯 **Visual Feedback** - Selection highlighting & glows
- ⏱️ **Time Tracking** - Score & level display
- 🌈 **Beautiful UI** - Gradient backgrounds & modern design
- 🔤 **800+ Words** - Extensive English-Spanish dictionary
- 🎼 **No Dependencies** - Vanilla JavaScript (except Electron)

## 📊 Difficulty Progression

| Level | Pairs | Speed | Difficulty |
|-------|-------|-------|------------|
| 1     | 5     | 1.0x  | 🟢 Easy |
| 2-3   | 6-7   | 1.0x  | 🟢 Easy |
| 4-5   | 8-9   | 1.3-1.6x | 🟡 Medium |
| 6     | 10-11 | 1.9x  | 🟡 Medium |
| 7+    | 12-15 | 1.9x+ | 🔴 Hard |

## 🎮 Pro Tips

- **Memory Game**: Memorize positions before clicking
- **Section Focus**: Work on one area of screen at a time
- **Quick Matches**: Match fast pairs first before they move far
- **Pattern Recognition**: Similar word patterns appear together
- **Rhythm**: Find a clicking rhythm that works for you
- **High Score**: Target 100+ points (10+ matches)

## 🔧 Technical Details

**Architecture**:
- HTML5 Canvas for rendering
- JavaScript for game logic
- 60 FPS animation loop
- Physics-based word movement
- Adaptive difficulty algorithm

**Word Selection**:
- 800 most common English-Spanish word pairs
- Loaded from words.json
- Random selection each level
- Increased complexity at higher levels

**Performance**:
- GPU-accelerated canvas rendering
- Efficient collision detection
- Minimal memory footprint
- Works on low-end systems

## 🚀 Installation Options

### Option A: Browser (Recommended for Quick Play)
- No installation needed
- Open game.html in any modern browser
- Works on Windows, Mac, Linux

### Option B: Desktop App (Full Experience)
```bash
# 1. Install Node.js from https://nodejs.org/
# 2. Run these commands:
npm install
npm start
```

### Option C: Development Mode
```bash
npm run dev  # Includes DevTools for debugging
```

## 🐛 Troubleshooting

**Game won't start?**
- Browser: Try different browser (Chrome, Firefox, Edge)
- Desktop: Run `npm install` and `npm start`
- Check console for errors (F12)

**Words moving too fast?**
- Normal for higher levels!
- Try easier difficulty or lower level

**Clicks not registering?**
- Click center of word box
- Make sure game window is focused
- Try clicking slower/deliberate

**Missing words.json?**
- Make sure all files are in same directory
- Browser version has fallback words built-in

## 📈 Game Statistics

After game ends, you'll see:
- **Final Score**: Total points earned (10 per match)
- **Level Reached**: Highest level achieved
- **Time Played**: Seconds played (max 120)
- **Words Matched**: Number of successful pairs

## 💾 File Descriptions

| File | Purpose |
|------|---------|
| game.html | Browser version - play immediately! |
| index.html | Electron app main UI |
| main.js | Electron process manager |
| renderer.js | Core game engine & logic |
| words.json | 800+ English-Spanish word pairs |
| preload.js | Electron security bridge |
| package.json | Node dependencies |
| README.md | Full documentation |
| QUICKSTART.md | Quick start guide |

## 🎓 Learning Features

Perfect for:
- English learners studying Spanish
- Spanish learners studying English
- Vocabulary practice
- Word association games
- Memory training
- Reaction time practice

## 🔄 Game Flow

```
Start Screen
    ↓
   [Click Start Game]
    ↓
Level 1 (5 pairs, 1.0x speed)
    ↓ (Match all pairs)
Level 2 (6 pairs, 1.0x speed)
    ↓
Level 3-6 (Increasing pairs & speed)
    ↓
Level 7+ (15 pairs, 1.9x+ speed)
    ↓
Game Over (2 min elapsed or ESC)
    ↓
   [Play Again Button]
```

## 🎉 What Makes This Game Special

1. **Real Physics** - Words actually bounce like real objects
2. **Smooth Animation** - 60 FPS smooth gameplay
3. **Smart Difficulty** - Gradually gets harder, never unfair
4. **Beautiful Design** - Modern gradient UI with animations
5. **Responsive** - Works on any screen size
6. **No Lag** - Optimized for all systems
7. **Instant Play** - No loading screens
8. **Accessible** - Works for all skill levels

## 📞 Support

Having issues? Check:
1. QUICKSTART.md for common problems
2. README.md for detailed documentation
3. Browser console (F12) for error messages
4. Make sure all files are in the same directory

## 🎮 Have Fun!

This game is designed to be:
- ✨ Visually appealing
- 🎯 Challenging but fair
- 🚀 Smooth and responsive
- 📚 Educational (language learning)
- 🏆 Fun and addictive

**Start with game.html → Click "Start Game" → Enjoy!**

---

**Version**: 1.0.0  
**Created**: 2026  
**License**: MIT (Free to use and modify)

Enjoy the game! 🎮🎉
