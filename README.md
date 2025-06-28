# 🎮 Raylib Inertia Shape Bouncer

A fun interactive project using [Raylib](https://www.raylib.com/) and C++, showcasing real-time motion physics, keyboard/mouse input, and dynamic shape transformations.

![screenshot](screenshot.gif) <!-- Replace with actual gif or image -->

---

## 🧠 Features

- 🔄 **Shape Toggle (5 Types)**: Double-click to switch between:
  - Circle
  - Square
  - Triangle
  - Star
  - Pentagon

- 🖱️ **Mouse Dragging**: Click and drag shapes around the screen.
- 🚀 **Inertia Movement**: Release the shape after dragging to make it float with motion.
- ⌨️ **Keyboard Controls**: Move with `Arrow Keys` or `WASD`.
- 🧱 **Bouncing Physics**: Shapes bounce off window edges with realistic direction changes.
- 🌈 **Color Flash on Impact**: Each wall collision triggers a color change effect.

---

## 🛠️ Requirements

- [Raylib](https://github.com/raysan5/raylib) installed
- C++ compiler with C++17 support
  - For Windows: MinGW or MSYS2
  - For Linux/macOS: g++ via system package manager

---

## 🚀 How to Compile

### 🪟 On Windows

```bash
g++ raylib_move_circle.cpp -o shape_app -Iinclude -Llib -lraylib -lopengl32 -lgdi32 -lwinmm
.\shape_app
