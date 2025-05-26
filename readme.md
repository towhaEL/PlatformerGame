# 🎮 Platformer Game (Pygame)

A side-scrolling 2D platformer game developed using **Pygame**, featuring dynamic levels, animated characters, collectibles, hazards, moving platforms, and a fun gameplay experience with background music and sound effects.

<p align="center">
  <img src="demo/platformer_demo.gif" width="600" alt="Platformer Game Demo"/>
</p>

---

## ✨ Features

- 🕹️ Player with smooth movement and jump animation  
- 💀 Enemies that move and interact with the player  
- 🔥 Lava & spikes as deadly traps  
- 🪙 Coins and ❤️ Life collectibles  
- ⛓️ Moving platforms (horizontal and vertical)  
- 🏁 Exit gates to clear levels  
- 💾 Level loading using `pickle`  
- 🔊 Background music and SFX using Pygame Mixer  
- 🧠 Modular, expandable codebase  

---

## 🎮 Controls

| Key       | Action        |
|-----------|---------------|
| Left Arrow / `←`  | Move Left     |
| Right Arrow / `→` | Move Right    |
| Spacebar  | Jump          |
| Mouse     | UI Interactions (buttons) |

---

## 🛠 Tech Stack

- **Python 3.x**  
- **Pygame**  
- **Pygame Mixer** – for audio  
- **Pickle** – for level data loading  
- **OS / Path** – for asset management  

---

## 📁 Project Structure

```
PlatformerGame/
├── assets/
│   ├── img/
│   │   ├── player, tiles, enemies, buttons, sounds...
│   └── levelData/
│       ├── level1_data, level2_data, ...
├── main.py
├── README.md
└── ...
```

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/PlatformerGame.git
cd PlatformerGame
```

### 2. Install dependencies
```bash
pip install pygame
```

### 3. Run the game
```bash
python main.py
```

> Make sure your folder structure and asset paths are preserved as shown above.

---

## 🖼️ Demo Screenshots

<p align="center">
  <img src="demo/menu.png" width="280"/>
  <img src="demo/level1.png" width="280"/>
  <img src="demo/gameover.png" width="280"/>
</p>

---

## 🧠 Future Improvements

- Add support for saving progress  
- Add power-ups and new enemy types  
- More levels and story mode  
- Controller support  

---

## ✍️ Author

- [Towha Elahi](https://github.com/towhaEL)

---

## ⭐ Show Your Support

If you enjoyed the game or found it useful, please ⭐ the repo and share with friends!