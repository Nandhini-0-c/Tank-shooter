# 🎯 Tank Shooter — C Mini Project

A lightweight, terminal-based 2D tank shooter game built in C. Navigate your tank, fire projectiles, dodge enemy fire, and rack up a high score — all from your terminal window.

---

## 📸 Demo

```
  ████████████████████████████████████████
  █  [E]              [E]                █
  █                                      █
  █        █████                         █
  █                      [E]             █
  █                 •                    █
  █                                      █
  █           [P]                        █
  ████████████████████████████████████████
  Score: 320    Lives: 3    Level: 2
```

---

## 🎮 Features

- Player-controlled tank with smooth movement
- Projectile firing mechanics with collision detection
- Enemy tanks with basic AI behavior
- Score tracking system
- Multiple levels with increasing difficulty
- Lives system and game over screen
- Terminal rendering using `ncurses`

---

## 🛠️ Built With

- **Language:** C (C99 standard)
- **Library:** ncurses (terminal UI)
- **Build Tool:** Make

---

## 📁 Project Structure

```
tank-shooter/
├── src/
│   ├── main.c          # Entry point and game loop
│   ├── player.c        # Player tank logic
│   ├── enemy.c         # Enemy AI logic
│   ├── bullet.c        # Projectile mechanics
│   ├── collision.c     # Collision detection
│   ├── renderer.c      # Terminal rendering (ncurses)
│   └── score.c         # Scoring system
├── include/
│   ├── player.h
│   ├── enemy.h
│   ├── bullet.h
│   ├── collision.h
│   ├── renderer.h
│   └── score.h
├── Makefile
└── README.md
```

---

## ⚙️ Installation & Setup

### Prerequisites

Make sure you have the following installed:

- GCC compiler
- `ncurses` library
- `make`

**Install ncurses (Ubuntu/Debian):**
```bash
sudo apt-get install libncurses5-dev libncursesw5-dev
```

**Install ncurses (macOS):**
```bash
brew install ncurses
```

### Clone & Build

```bash
# Clone the repository
git clone https://github.com/your-username/tank-shooter.git
cd tank-shooter

# Build the project
make

# Run the game
./tank-shooter
```

---

## 🕹️ Controls

| Key | Action |
|-----|--------|
| `W` / `↑` | Move Up |
| `S` / `↓` | Move Down |
| `A` / `←` | Move Left |
| `D` / `→` | Move Right |
| `Space` | Fire |
| `P` | Pause |
| `Q` | Quit |

---

## 🧠 Concepts Demonstrated

This project was built to practice and demonstrate core C programming concepts:

- **Structs** — Game entities (tank, bullet, enemy) modeled as structs
- **Pointers & Memory Management** — Dynamic allocation for bullets and enemy arrays
- **Game Loop Architecture** — Fixed-step update loop with input polling
- **Modular Design** — Separation of concerns across multiple source files
- **Header Files** — Proper use of `.h` files and include guards
- **ncurses Library** — Terminal-based rendering and keyboard input

---

## 🗺️ Roadmap

- [x] Player movement & shooting
- [x] Enemy AI (basic patrol + shoot)
- [x] Collision detection
- [x] Score & lives system
- [ ] Power-ups (speed boost, rapid fire, shield)
- [ ] Map obstacles / walls
- [ ] High score leaderboard (file I/O)
- [ ] Two-player mode

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -m 'Add my feature'`)
4. Push to the branch (`git push origin feature/my-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

Made with ❤️ and lots of `segfaults` — **Your Name**  
[GitHub](https://github.com/your-username) · [LinkedIn](https://linkedin.com/in/your-profile)
