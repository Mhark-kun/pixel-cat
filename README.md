# 🐱 Pixel Cat Survival

A browser-based grid survival game with boss battles, inventory, a shop system, multiple maps, and save/load.

## 🚀 Deploy to Vercel (free, 1 minute)

### Option A — Vercel CLI
```bash
npm i -g vercel
cd pixel-cat
vercel
```
Follow the prompts. Your game will be live at `https://pixel-cat-survival-xxx.vercel.app`.

### Option B — Vercel Dashboard (drag & drop)
1. Go to **https://vercel.com/new**
2. Choose **"Browse"** → upload this entire `pixel-cat` folder as a zip
3. Click **Deploy** — done!

---

## 📁 File Structure

```
pixel-cat/
├── index.html              ← Game UI & overlays
├── style.css               ← All styling + disco death screen
├── caramelldansen.mp3      ← Death music 🎵
├── vercel.json             ← Vercel static config
└── js/
    ├── audio.js            ← Web Audio beeps
    ├── save.js             ← localStorage save/load
    ├── maps.js             ← 5 maps (Dungeon → Castle)
    ├── items.js            ← Item catalog & inventory
    ├── enemies.js          ← Enemy AI
    ├── boss.js             ← 5 boss battle patterns
    ├── shop.js             ← Shop UI
    ├── inventory.js        ← Inventory overlay & equip
    ├── game.js             ← Core game loop & state
    ├── ui.js               ← Rendering + death screen
    └── main.js             ← Input & boot
```

## 🎮 Controls

| Key | Action |
|-----|--------|
| WASD / Arrow Keys | Move |
| SPACE | Ghost Mode (needs 5 power) |
| I | Inventory |
| B | Shop |
| Q | Quick use item |
| F5 | Save game |
| ESC | Pause |

## ✨ Features

- ❤️ **Health + Inventory** — HP bar, armor, weapons, 10+ items
- 👑 **Boss Battles** — 1 unique boss per map with special attack patterns
- 🏪 **Shop System** — Buy items with 🪙 coins; stock upgrades per map
- 🗺 **5 Maps** — Dungeon → Haunted Forest → Lava Kingdom → Frozen Tundra → Shadow Castle
- 💾 **Save / Load** — Press F5 or use pause menu; Continue button on title screen
- 💀 **Disco Death Screen** — Rainbow lights + Caramelldansen on every death 🎶
