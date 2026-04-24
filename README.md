# CSC_1S004-Project

This project is a dynamic, interactive, and standards-compliant web application.  
It demonstrates the use of **HTML (structure and semantics)**, **CSS (layout and styling)**, and **JavaScript (dynamic behavior and user interaction)** as covered in the course.

---

# 🎮 Sky Leap

Sky Leap is a browser-based 2D platformer game built with **HTML**, **CSS**, and **JavaScript**.  
Players jump across platforms, collect coins, avoid spikes, and reach the exit door — with support for **custom maps and map-specific ranking systems**.

---

## 🚀 Features

### 🎯 Core Gameplay
- Smooth player movement and jumping
- Gravity and platform collision detection
- Coin collection system
- Hazard system (spikes cause death)
- Goal-based gameplay (reach the door)

### 🗺️ Map System
- Built-in **default map**
- Custom map editor
- Players can:
  - Create maps
  - Save maps
  - Reload and edit maps
- Multiple maps selectable before starting the game

### 🏆 Ranking System
- Each map has its **own ranking board**
- Stores:
  - Player name
  - Coins collected
  - Completion time
- Duplicate names:
  - Only the **best score is kept**
- Password-protected reset system

### 🎨 Character Customization
- Players can customize:
  - Skin color
  - Shirt color
  - Pants color
  - Hair color

### 🧭 Multi-Page Web Application
- `index.html` → Main game  
- `ranking.html` → Ranking board  
- `editor.html` → Map editor  

---

## 🕹️ How to Play

| Action | Key |
|--------|-----|
| Move Left | A / ← |
| Move Right | D / → |
| Jump | W / ↑ / Space |
| Restart | R |

### Objective
- Avoid spikes  
- Collect coins  
- Reach the green door  

---

## 🧱 Technologies Used

- **HTML5** — structure and semantics  
- **CSS3** — layout and styling  
- **JavaScript (ES6 Modules)** — game logic and interaction  
- **Canvas API** — rendering and animation  
- **LocalStorage** — data persistence (rankings & maps)

---

## 📂 Project Structure

```text
CSC_1S004-Project/
├── index.html
├── ranking.html
├── editor.html
├── style.css
├── README.md
└── js/
    ├── main.js
    ├── config.js
    ├── player.js
    ├── levels.js
    ├── renderer.js
    ├── collision.js
    ├── ui.js
    ├── rankings.js
    ├── mapEditor.js
    └── character.js
