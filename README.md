# 🐍 SNAKE (SFML 3)

A simple but complete Snake game built using **C++ and SFML 3**.  
This project includes a menu system, control selection, scoring, and a Linux `.deb` installer.

---

## 👤 Author
**i4lt**

---

# 🎮 How It Works

The game is a classic Snake implementation:

- You control a snake moving on a grid
- Eat red food to grow and increase score
- Avoid hitting walls or your own tail
- The game speed stays constant for smooth gameplay

### 🧠 Game Loop
1. Read player input (Arrow keys or WASD)
2. Move snake every frame tick
3. Check collisions:
   - Food → grow snake
   - Wall → game over
   - Self → game over
4. Render updated frame

---

# 🎯 Controls

You can choose controls in the game:

### Option 1: Arrow Keys
- ↑ Move up  
- ↓ Move down  
- ← Move left  
- → Move right  

### Option 2: WASD
- W → Up  
- S → Down  
- A → Left  
- D → Right  

---

# 📥 Installation

## 🥇 Option 1 — Install .deb (Debian / Ubuntu / Linux Mint) ⭐ Recommended

Download the `.deb` file from **Releases**, then install:
```bash
sudo dpkg -i snake_1.0_amd64.deb
snake
