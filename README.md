<div align="center">
 
<br/>
 
```
  ████████╗██╗ ██████╗    ████████╗ █████╗  ██████╗    ████████╗ ██████╗ ███████╗
     ██╔══╝██║██╔════╝       ██╔══╝██╔══██╗██╔════╝       ██╔══╝██╔═══██╗██╔════╝
     ██║   ██║██║            ██║   ███████║██║            ██║   ██║   ██║█████╗  
     ██║   ██║██║            ██║   ██╔══██║██║            ██║   ██║   ██║██╔══╝  
     ██║   ██║╚██████╗       ██║   ██║  ██║╚██████╗       ██║   ╚██████╔╝███████╗
     ╚═╝   ╚═╝ ╚═════╝       ╚═╝   ╚═╝  ╚═╝ ╚═════╝       ╚═╝    ╚═════╝ ╚══════╝
```
 
### ✦ A Classic Game, Reimagined in Flutter ✦
 
<br/>
 
[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev)
[![License](https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS-blueviolet?style=for-the-badge&logo=googlechrome&logoColor=white)](https://flutter.dev)
[![Stars](https://img.shields.io/github/stars/ManishSamanta23/Flutter-Game_Tic_Tac_Teo?style=for-the-badge&color=f59e0b)](https://github.com/ManishSamanta23/Flutter-Game_Tic_Tac_Teo/stargazers)
 
<br/>
 
</div>
 
---
 
## 🎮 About The Game
 
> **Tic Tac Toe** — the timeless two-player strategy game — brought to life with a clean, modern Flutter experience. Built for speed, built for fun.
 
Two players take turns marking spaces on a **3×3 grid**. The first player to align three of their marks — horizontally, vertically, or diagonally — wins the round. Simple rules. Infinite replay.
 
<br/>
 
---
 
## ✨ Features
 
<br/>
 
| Feature | Description |
|--------|-------------|
| 🕹️ **Two-Player Mode** | Play against a friend on the same device |
| ⚡ **Instant Win Detection** | Real-time detection of winning combinations |
| 🔄 **Quick Restart** | Reset the board with a single tap |
| 📱 **Responsive UI** | Adapts beautifully to all screen sizes |
| 🎨 **Clean Design** | Minimal, distraction-free interface |
| 🏆 **Score Tracking** | Keep track of wins across rounds |
 
<br/>
 
---
 
## 📸 Screenshots
 
<br/>
 
<div align="center">
 
> *Add your screenshots here by dropping them in an `/assets/screenshots/` folder and linking them below.*
 
| Home Screen | Gameplay | Winner Screen |
|:-----------:|:--------:|:-------------:|
| ![Home](assets/screenshots/home.png) | ![Game](assets/screenshots/game.png) | ![Win](assets/screenshots/win.png) |
 
</div>
 
<br/>
 
---
 
## 🛠️ Tech Stack
 
<br/>
 
```
┌─────────────────────────────────────────────────────────┐
│                     PROJECT STACK                       │
├────────────────────┬────────────────────────────────────┤
│  Framework         │  Flutter (Dart)                    │
│  Language          │  Dart 3.x                          │
│  State Management  │  setState / StatefulWidget         │
│  Target Platforms  │  Android & iOS                     │
│  Min SDK           │  Android 5.0+ / iOS 11+            │
└────────────────────┴────────────────────────────────────┘
```
 
<br/>
 
---
 
## 🚀 Getting Started
 
### Prerequisites
 
Make sure you have the following installed on your system:
 
- [Flutter SDK](https://docs.flutter.dev/get-started/install) `>= 3.0.0`
- [Dart SDK](https://dart.dev/get-dart) `>= 3.0.0`
- [Android Studio](https://developer.android.com/studio) or [VS Code](https://code.visualstudio.com/)
- A connected Android/iOS device or emulator
 
<br/>
 
### 📦 Installation
 
**1. Clone the repository**
 
```bash
git clone https://github.com/ManishSamanta23/Flutter-Game_Tic_Tac_Teo.git
```
 
**2. Navigate into the project directory**
 
```bash
cd Flutter-Game_Tic_Tac_Teo
```
 
**3. Install dependencies**
 
```bash
flutter pub get
```
 
**4. Run the app**
 
```bash
flutter run
```
 
> 💡 **Tip:** Use `flutter run --release` for a faster, optimized build.
 
<br/>
 
---
 
## 📁 Project Structure
 
```
Flutter-Game_Tic_Tac_Teo/
│
├── lib/
│   ├── main.dart               # App entry point
│   ├── screens/
│   │   ├── home_screen.dart    # Landing / welcome screen
│   │   └── game_screen.dart    # Main game board UI & logic
│   ├── widgets/
│   │   └── board_tile.dart     # Individual grid tile widget
│   └── utils/
│       └── game_logic.dart     # Win-check & game state logic
│
├── assets/                     # Images, fonts & other assets
├── test/                       # Unit & widget tests
├── pubspec.yaml                # Dependencies & metadata
└── README.md
```
 
<br/>
 
---
 
## 🎯 How To Play
 
```
  Step 1          Step 2           Step 3          Step 4
─────────      ────────────     ────────────     ───────────
 Launch         Player X         Player O         First to
  App           taps a           taps a           get 3 in
                 cell             cell            a row wins!
 
   📱       →    ❌ · ·    →    ❌ · ·    →    ❌ ❌ ❌
                 · · ·          · ⭕ ·           · ⭕ ·
                 · · ·          · · ·            · · ·
```
 
- **X always goes first**
- Tap any empty cell to place your mark
- First player with **3 marks in a row** (horizontal, vertical, or diagonal) wins
- If all 9 cells fill up with no winner → it's a **Draw!**
- Hit **Restart** to play again
 
<br/>
 
---
 
## 🤝 Contributing
 
Contributions are welcome and appreciated! Here's how you can help:
 
1. **Fork** the repository
2. Create a new branch → `git checkout -b feature/your-feature-name`
3. Make your changes and commit → `git commit -m 'Add: your feature description'`
4. Push to your branch → `git push origin feature/your-feature-name`
5. Open a **Pull Request** 🎉
 
<br/>
 
### 💡 Ideas for Contribution
 
- [ ] Single-player mode with AI opponent
- [ ] Sound effects & haptic feedback
- [ ] Animated winning line highlight
- [ ] Dark / Light theme toggle
- [ ] Online multiplayer support
- [ ] Custom player name entry
 
<br/>
 
---
 
## 🐛 Bug Reports
 
Found a bug? Please [open an issue](https://github.com/ManishSamanta23/Flutter-Game_Tic_Tac_Teo/issues) with:
 
- A clear description of the problem
- Steps to reproduce
- Expected vs actual behavior
- Device & Flutter version info
 
<br/>
 
---
 
## 📄 License
 
This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.
 
```
MIT License — Free to use, modify, and distribute.
Just give credit where it's due. 🙏
```
 
<br/>
 
---
 
## 👨‍💻 Author
 
<div align="center">
 
**Manish Samanta**
 
[![GitHub](https://img.shields.io/badge/GitHub-ManishSamanta23-181717?style=for-the-badge&logo=github)](https://github.com/ManishSamanta23)
 
*Made with ❤️ and Flutter*
 
</div>
 
---
 
<div align="center">
 
⭐ **If you liked this project, please give it a star — it means a lot!** ⭐
 
</div>
