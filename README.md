# 🕹️ Hand-Tracking Pong Game

A fun and interactive Pong-style game where you control paddles using hand gestures via your webcam. The game uses **OpenCV**, **cvzone**, and **Pygame** to create an engaging and immersive experience with sounds, scoring, and real-time hand tracking.

---

## ✨ Features

- 👋 Real-time hand tracking using webcam
- 🏓 Paddle control with left and right hands
- 🎯 Ball collision physics
- 🔊 Sound effects for bounce, bat hit, and game over
- 📊 Score and high score tracking
- ⏱️ Countdown before each game starts
- 🖥️ Fullscreen gameplay
- 🎮 Game over screen with current score and high score

---

## 📦 Requirements

Install the following Python libraries:

```bash
pip install opencv-python cvzone pygame numpy
```

---

## 📁 Project Structure

```
HandTrackingPong/
│
├── main.py                    # Main game script
├── README.md                  # Project documentation
└── Resources/                 # Assets folder
    ├── Background.png         # Background image
    ├── gameOver.png           # Game over screen image
    ├── Ball.png               # Ball image (transparent)
    ├── bat1.png               # Left bat 
    ├── bat2.png               # Right bat 
    ├── bounce.wav             # Wall bounce sound
    ├── bat_hit.wav            # Bat hit sound
    ├── game_over.wav          # Game over sound
```

---

## 🚀 How to Run

1. Clone or download the project.
2. Place all assets inside the `Resources/` folder.
3. Run the main script:

```bash
python main.py
```

---

## 🎮 Controls

| Action        | Key / Gesture          |
|---------------|------------------------|
| Move paddles  | Show left/right hand   |
| Restart game  | Press `R`              |
| Quit game     | Press `Q`              |

---

## 📝 Notes

- Make sure your webcam is connected and working.
- The game runs in fullscreen for better immersion.
- Scores are displayed in real time.
- The high score persists only during the current run.

---

## 🙏 Acknowledgements

- [cvzone](https://github.com/cvzone/cvzone) for hand tracking utilities
- [OpenCV](https://opencv.org/) for image and video processing
- [Pygame](https://www.pygame.org/) for audio integration

---

## 📌 To Do (Optional Enhancements)

- [ ] Add player name input
- [ ] Save high scores between sessions
- [ ] Multiplayer over LAN or Bluetooth
- [ ] Power-ups and increasing ball speed

---

## 📬 Contact

For feedback or suggestions, feel free to open an issue or contribute to the project.
