# 2D Survival Defense Game (Unity)

A fast-paced **2D survival defense game** developed in **Unity and C#**, where the player protects a core object from waves of enemies while surviving as long as possible.

[Gameplay Demo Video](https://github.com/harrishyesuraj/2D-Survival-Defense-Game/releases/tag/v1.0)


---

## 🎮 Game Objective
- Protect the **Core Object** from enemy attacks
- Survive as long as possible while enemies spawn faster over time
- Track kill count and survival time
- Game ends if the player or core is destroyed

---

## 🕹️ Player Mechanics
- Movement: Left/Right
- Jumping
- Melee attacks
- Damage system with health feedback

---

## 👾 Enemy AI
- Moves toward player/core
- Attacks in range
- Flip sprites dynamically
- Death triggers kill count increment

---

## ❤️ Health & Damage System
- Reusable **Entity base class**
- Manages health, damage, attack logic
- Visual damage feedback via material swap

---

## 🧠 Core Architecture
- Entity base class used by Player, Enemy, Core
- Handles animations, health, attack, sprite flipping
- Clean OOP architecture for scalability

---

## 🖥️ UI System
- Start menu, in-game timer & kill count
- Game Over menu with Retry/Quit

---

## 🛠️ Technologies Used
- Unity (2D)
- C# scripting
- Rigidbody2D & Collider2D physics
- TextMeshPro for UI
- Object-Oriented Programming

---

## 🌟 Key Learnings
- Designing reusable base classes
- Animation events and movement control
- Enemy AI & wave spawning
- Full gameplay flow management
- Scalable Unity project development

---

### 🔹 Steps to Run
1. Clone or download this repository from GitHub
2. Open **Unity Hub**
3. Click **Open Project**
4. Select the project folder that contains:
   - `Assets`
   - `Packages`
   - `ProjectSettings`
5. Unity will automatically generate missing folders (`Library`, `Temp`, etc.)
6. Open the main scene:
   `Assets/Scenes/MainScene.unity`
7. Click the ▶️ **Play** button to start the game

### ⚠️ Notes
- First launch may take a few minutes while Unity builds cache
- If Unity asks for an editor version, choose the closest **LTS version**

---

## 👥 Contributors
- **Solo Developer:** HARRISH YESURAJ P  
- Main contributors featured in the video: [Watch here](https://youtu.be/ZEtKg9AyEJc)
