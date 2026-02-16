# 🎰 Task3 - Character Roulette (AxGrid Unity)

Unity-based character roulette system built with **AxGridUnityTools** framework.

![Unity](https://img.shields.io/badge/Unity-6000-black?logo=unity)
![URP](https://img.shields.io/badge/Render-URP-green)
![AxGrid](https://img.shields.io/badge/AxGrid-UnityTools-blue)

---

## ✨ Features

- 🎯 FSM-driven state management (AxGrid FSM)
- 🎨 Smooth Path-based animations
- 🏆 Winner selection with scale/position animation
- 🎆 Particle effects on win
- 🔄 Restart & Exit functionality

---

## 📋 Tech Stack

| Component | Version |
|-----------|---------|
| Unity | 6000 |
| Render Pipeline | URP |
| Framework | AxGridUnityTools |
| UI | TextMeshPro |

---

## 📁 Files

| File/Folder | Description |
|-------------|-------------|
| `____Task003 Game/` | **Clean build** (ready to run) |
| `task3byMechZeroRun.exe` | **Launch executable** |
| `Project/` | Full Unity project source |
| `README.md` | This file |

| https://disk.yandex.ru/d/vmkmOgSnBTwH2Q |
| https://disk.yandex.ru/d/X45s4CjVoWBcYg |
---

## 🎮 Controls

| Button | Action |
|--------|--------|
| **START** | Begin spin |
| **STOP** | Stop (min 3 sec) |
| **RESTART** | Reset state |
| **EXIT** | Close app |

---

## 📁 Project Structure

Assets/
├── Scripts/Task3/ # All game scripts
├── Editor/ # Custom inspectors (build excluded)
├── Prefabs/ # Character prefabs
├── Scenes/ # Main scene
└── Arts/ # Sprites & effects


---

## ⚙️ Configuration

**Task3View Inspector:**
- Item Height: 100
- Scroll Speed: 2000
- Stop Deceleration: 1.5s
- Winner Scale: 1.5
- Pool Size: 12

---

## 📝 Notes

- Editor scripts in `Assets/Editor/` (excluded from build)
- Winner = closest to center (Y=0)
- Minimum 3 seconds before stop allowed

---

## 👨‍ Author

**MechZero** (MechromancerZero)

---

**Made with ❤️ and Unity 6000**
