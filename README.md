# 🐍 Snake Game

A classic **Snake Game** built using **HTML, CSS, and JavaScript**, deployed via GitHub Pages.  
This lightweight project recreates the nostalgic arcade experience while demonstrating key front-end programming concepts like game loops, DOM manipulation, and user input handling — all without any frameworks.

---

## 🎮 Live Demo

Play now → [https://tarunyaprogrammer.github.io/Snake-Game](https://tarunyaprogrammer.github.io/Snake-Game)

---

## 🎯 Features

- 🐍 Snake movement with arrow keys
- 🧠 Collision detection (walls & self)
- 🍎 Food generation with scoring
- 🔄 Replayable with auto-reset
- 🖥️ Desktop optimized and runs smoothly with `requestAnimationFrame`
- 💡 Minimalistic design with clear gameplay

---

## 📂 Project Structure

```
Snake-Game/
├── index.html     # Game canvas and layout
├── style.css      # Grid styling and visual design
├── script.js      # Game logic (loop, controls, collision)
└── README.md      # Documentation
```

---

## ⚙️ Getting Started

### 🧰 Prerequisites

- A modern web browser (Chrome, Firefox, Edge)
- [Optional] Git + Live Server (VS Code extension or Node)

### 🔧 Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/TarunyaProgrammer/Snake-Game.git
   cd Snake-Game
   ```

2. Open `index.html` in your browser  
   Or use a live server:
   ```bash
   live-server
   ```

---

## 🧠 How It Works

- Snake's body is a list of coordinate pairs, rendered using `div`s in a grid.
- Direction is updated via `keydown` events.
- Game loop runs with `requestAnimationFrame` and a speed threshold.
- Collisions (with walls or self) trigger a game over and reset.
- Food is randomly spawned at available cells.

---

## 🗺️ Roadmap

- [ ] Add pause/resume functionality
- [ ] Touch controls for mobile
- [ ] Save high scores in `localStorage`
- [ ] Add music/sound effects

---

## 🤝 Contributions

Contributions and suggestions are welcome!

1. Fork the repo
2. Create your branch: `git checkout -b feature/your-feature`
3. Commit changes: `git commit -m 'Add your feature'`
4. Push to the branch: `git push origin your-feature`
5. Open a Pull Request 🚀

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👤 Author

**Tarunya Ksh**

- GitHub: [@TarunyaProgrammer](https://github.com/TarunyaProgrammer)
- LinkedIn: [@tarunyakesharwani](https://www.linkedin.com/in/tarunyakesharwani/)
- Email: [tarunyak.10@gmail.com](mailto:tarunyak.10@gmail.com)

---

## 🌟 Show Some Love

If you liked this project or found it helpful, please consider giving it a ⭐️.  
Every star motivates open-source creators like me. 💖

---

> _Made with love & JavaScript to bring back arcade memories._
