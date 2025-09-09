# 🎮 Edge Gamer – 3D Endless Runner

**Edge Gamer** is a 3D endless runner game built in **C++ with OpenGL (GLUT)**.  
The player controls a rolling cube navigating along procedurally generated paths filled with dynamic obstacles. The objective is to survive as long as possible while scoring points based on distance traveled.

---

## 🚀 Features
- **Procedural Path Generation** – dynamically extending path with increasing difficulty  
- **Dynamic Obstacles** – rising, falling, spinning, and moving blocks challenge the player  
- **Player Mechanics** – rolling, jumping, and smooth movement animations  
- **Camera Modes** – isometric, top-down, side view, and first-person perspectives  
- **Graphics Effects** – real-time lighting, fog, textured cubes, and skybox  
- **Scoring System** – distance-based scoring with game over and restart functionality  

---

## 🎮 Controls
| Key | Action |
|-----|--------|
| `W / A / S / D` | Roll forward, left, backward, right |
| `SPACE + Direction` | Jump in the chosen direction |
| `V` | Change camera view |
| `C` | Toggle camera rotation |
| `+ / -` | Zoom in / out |
| `R` | Restart game |
| `ESC` | Exit |

---

## 🛠️ Installation & Setup
### Prerequisites
- **C++ Compiler** (g++, clang++, or MSVC)  
- **OpenGL & GLUT libraries** installed on your system  

### Build & Run (Linux / macOS)
```bash
g++ Edge_Gamer.cpp -lGL -lGLU -lglut -o EdgeGamer
./EdgeGamer
