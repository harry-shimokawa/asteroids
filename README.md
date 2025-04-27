

# 🚀 Asteroids Game (Python + Pygame)

Welcome to my recreation of the classic **Asteroids** arcade game!  
Built completely from scratch using **Python** and **Pygame**, this project was designed to solidify my understanding of game loops, collision detection, object management, and real-time user interaction.

---

## 📜 Summary of Progress So Far

✅ **Project Setup**
- Virtual environment created with `venv`
- Project organized with clean module structure (`main.py`, `player.py`, `asteroid.py`, etc.)

✅ **Core Game Systems**
- Basic game loop with update and draw phases
- Framerate limited to **60 FPS** using `pygame.time.Clock`
- Groups (`updatable`, `drawable`, `asteroids`, `shots`) to manage all game objects efficiently

✅ **Player Mechanics**
- Smooth rotation with `A` and `D` keys
- Forward/backward movement with `W` and `S`
- Shooting bullets with `Spacebar`
- Bullet rate-limited (0.3s cooldown)

✅ **Asteroid Mechanics**
- Random spawning from screen edges
- Movement with random angles and speeds
- Asteroids split into smaller ones upon being shot
- Small asteroids disappear when destroyed

✅ **Collision Detection**
- Circle-based collision logic (simplified hitboxes)
- Player collision triggers **Game Over**
- Bullet collision destroys or splits asteroids

✅ **Game Feel**
- Smooth and responsive controls
- Streamlined object updates and automatic cleanup using `kill()`

---

## 🎯 Next Steps (Planned Improvements)

Here’s what I’m planning to implement next to make the game even better:

### ⭐ Immediate Enhancements
- **Add a Scoring System**  
  ➔ +100 points for destroying a large asteroid  
  ➔ +200 points for destroying a medium asteroid  
  ➔ +300 points for destroying a small asteroid

- **Bullet Lifetime**  
  ➔ Bullets automatically disappear after 2 seconds if they don't hit anything (prevents clutter and performance issues)

- **Screen Wrapping**  
  ➔ When the player or asteroids fly off one edge of the screen, they reappear on the opposite side (true to the original Asteroids!)

- **Lives System**  
  ➔ Start with 3 lives  
  ➔ Lose a life upon collision  
  ➔ Show "Game Over" screen after losing all lives

---

## 🎨 Future Stretch Goals (Fun Ideas)
- Explosion particle effects when asteroids break apart
- Background image (starfield or galaxy theme)
- Shield and speed boost power-ups
- Different weapon types (e.g., lasers, bombs)
- Asteroids with lumpy, irregular shapes
- Accurate triangular hitbox for the spaceship
- New enemy types (hostile UFOs?)
- Save high scores locally

---

## 📸 Screenshots

_(Coming soon after implementing scoring and wrapping!)_

---

## 🛠 How to Run the Game

1. Clone the repository:

```bash
git clone https://github.com/your-username/asteroids-project.git
cd asteroids-project
```

2. Create and activate the virtual environment:

```bash
python3 -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate     # Windows
```

3. Install requirements:

```bash
pip install -r requirements.txt
```

4. Run the game:

```bash
python3 main.py
```

---

## 📚 Technologies Used
- Python 3
- Pygame 2.6.1
- Git + GitHub for version control

---

## 🙌 Special Thanks
Thanks to Boot.dev for designing the structure of the project and providing an awesome learning platform! 🎮

---

# 🌟 Final Thoughts
Building this project taught me so much about how games work internally — from input handling and game loops to collision detection and sprite management.  
I'm excited to keep extending it and adding new features! 🚀
