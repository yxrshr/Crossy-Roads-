#  CROSSY ROADS – 3D Endless Runner in OpenGL

> A Computer Graphics Project developed using OpenGL and GLUT in C++  
> Developed as part of UCS505 - Computer Graphics  
> **By:** Yash Saxena, Madhur Mahajan, Nikhil Garg  
> **Institution:** Thapar Institute of Engineering and Technology

---

##  Project Overview

**CROSSY ROADS** is a 3D endless runner game inspired by the popular "Crossy Roads" concept. The objective is to control a cube-shaped character and avoid dynamic and static obstacles while navigating a path that dynamically generates itself.

---

##  Key Features

- **Player Movement**: W/A/S/D keys for rolling; Spacebar + direction for jumping
- **Dynamic Obstacles**: Includes spinning, rising, falling, and moving cubes
- **Multiple Camera Views**: Isometric, Top-down, Side, and First-Person
- **Graphics**: Real-time 3D rendering using OpenGL (lighting, shading, materials)
- **Score System**: Distance-based score displayed on HUD
- **Skybox & Grid**: Enhances the environment visually

---

##  Technologies Used

| Library / API  | Purpose                                  |
|----------------|------------------------------------------|
| OpenGL         | Graphics rendering                       |
| GLUT           | Windowing, keyboard & timer callbacks    |
| C++ STL        | Data structures like `vector`, `tuple`   |
| GLU            | Camera and perspective setup             |

---

##  Functions Overview

###  User-Defined Functions
| Function               | Purpose                                                                 |
|------------------------|-------------------------------------------------------------------------|
| `generateInitialPath()`| Generates the first segment of the playable path                        |
| `generateObstacles()`  | Adds obstacles with logic and randomness                                |
| `onPath()`             | Checks if player is on a valid path                                     |
| `checkObstacleCollision()` | Detects if the player hit an obstacle                           |
| `updateGame()`         | Updates all game logic and physics                                      |
| `reset()`              | Restarts the game                                                       |
| `nextCameraMode()`     | Switches camera perspective                                             |
| `toggleCameraRotation()` | Rotates or fixes camera angle                                        |
| `zoomIn()` / `zoomOut()` | Changes zoom level                                                  |
| `drawPlayer()`         | Renders the player cube                                                 |
| `drawObstacle()`       | Renders dynamic cubes                                                   |
| `drawGrid()` / `drawSkybox()` | Adds 3D environment elements                                |

(📜 Full function list available in `CROSSY_ROADS.pdf`)

---

## 🚀 How to Run the Project

### ▶️ Requirements
- C++ Compiler with OpenGL support
- GLUT library installed
- Any platform (Windows, Linux, Mac) with OpenGL support

### 🛠️ Setup Instructions
1. **Install OpenGL & GLUT**  
   For Windows (MSYS2):  
   ```bash
   pacman -S mingw-w64-x86_64-freeglut
   sudo apt-get install freeglut3-dev
   g++ crossy_roads.cpp -o crossy_roads -lGL -lGLU -lglut
   ./crossy_roads


## Game Controls

| Key                 | Action                       |
| ------------------- | ---------------------------- |
| `W` `A` `S` `D`     | Move forward/left/back/right |
| `SPACE` + Direction | Jump                         |
| `V`                 | Switch camera view           |
| `C`                 | Toggle camera rotation       |
| `R`                 | Restart the game             |
| `+` / `-`           | Zoom In / Out                |
| `ESC`               | Exit the game                |


## Project Demo
  
[Watch on Google Drive](https://drive.google.com/file/d/1BHdA7T0pVtAHyb2KQvywSPu425qSZ89k/view?usp=sharing)


## About Project 
Working on CROSSY ROADS was an exciting journey into the world of computer graphics. Implementing real-time rendering, obstacle logic, and interactive controls using OpenGL taught me a lot about game development fundamentals. It was both a challenging and rewarding experience that strengthened my problem-solving and programming skills.


