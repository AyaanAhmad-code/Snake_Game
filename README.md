# 🐍 Snake Game (Vanilla JavaScript)

A classic **Snake Game** built using **HTML, CSS, and Vanilla JavaScript**.  
The game includes score tracking, high score persistence using `localStorage`, a timer, and a smooth grid-based gameplay experience.

---

## 🚀 Live Preview
> https://ayaanahmad-code.github.io/Snake_Game/

---

## 🎮 Features

- 🎯 **Classic Snake Gameplay**
- 🍎 **Random Food Generation**
- 📈 **Score System**
- 🏆 **High Score Saved using localStorage**
- ⏱ **Real-time Game Timer**
- ⌨️ **Keyboard Controls (Arrow Keys & WASD)**
- 🔁 **Restart Game Option**
- 🧊 **Modern UI with CSS Variables**
- 💡 **Responsive Grid-Based Board**

---

## 🕹 Controls

| Key | Action |
|----|-------|
| ⬆️ Arrow Up / `W` | Move Up |
| ⬇️ Arrow Down / `S` | Move Down |
| ⬅️ Arrow Left / `A` | Move Left |
| ➡️ Arrow Right / `D` | Move Right |

---

## 🧠 Game Logic Overview

- The game board is dynamically created using CSS Grid.
- The snake is represented as an array of coordinate objects.
- Each game tick:
  - A new head position is calculated based on direction.
  - Collision with wall ends the game.
  - Collision with food increases score and snake length.
- High score is stored using `localStorage`.
- Timer runs independently using `setInterval`.

---

## 🛠 Tech Stack

- **HTML5**
- **CSS3 (CSS Variables & Grid)**
- **JavaScript (ES6+)**
- **Browser Local Storage**

---

## 📁 Project Structure

```
Snake-Game/
│
├── index.html 
├── style.css 
├── script.js
├── favicon.ico
└── README.md 
```

---

## ⚙️ How to Run Locally

1. Clone the repository
```bash
git clone https://github.com/your-username/snake-game.git
```

2. Open the project folder
```bash
cd snake-game
```
3. Open index.html in your browser
(No server required)

---

🔮 Future Improvements

▪️🧱 Self-collision detection

▪️🎵 Sound effects

▪️📱 Mobile touch controls

▪️⚡ Difficulty levels (speed increase)

▪️🎨 Multiple themes

---

🤝 Contributing

Contributions are welcome!
Feel free to fork this repository and submit a pull request.

---

👨‍💻 Author

Ayaan Ahmad
Frontend Developer | JavaScript Enthusiast

📫 Connect with me on LinkedIn
⭐ If you like this project, give it a star!
