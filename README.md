#  Running Man (Chạy Đi Chờ Chi)

A fast-paced 2D arcade survival game built with **Java Swing** where players navigate through heavy traffic and obstacles to escape pursuit.

---

##  Introduction

In **Running Man**, you play as a desperate student who, after failing classes and needing money to retake them, makes a reckless decision: attempting a “dog snatching” heist.

Unfortunately, both locals and the police spot you.

Now your only chance is to jump on your trusty **Exciter motorbike**, speed through chaotic city streets, dodge traffic, avoid pedestrians, and escape law enforcement for as long as possible.

Survive. Don’t crash. Don’t get caught.

---

##  Gameplay Features

###  Dynamic Difficulty

Choose from **5 difficulty levels**:

- Chill guy
- Medium
- Hard
- Asian
- Are you sure!?

Higher difficulty levels:
- Increase traffic density
- Increase game speed acceleration

---

###  Character Selection

Players can choose between:

- **T2UH**
- **T3U**

Each character includes unique visual assets.

---

###  Interactive Environments

- Straight city roads  
- Dangerous intersections  

---

###  Diverse Obstacles

Avoid various computer-controlled entities:

- Civilian cars (Blue, Pink, White)
- Motorbikes
- Pedestrians crossing the street
- Police patrol units
- Roadside trees

---

###  Scoring & Ranking

- High score tracking system
- Stores the **Top 3 best runs**

---

###  Audio System

- Background music
- Interactive sound effects
- Vehicle horns trigger when near other cars

---

##  Controls

| Key | Action |
|------|--------|
| ↑ UP Arrow | Accelerate |
| ↓ DOWN Arrow | Brake |
| ← LEFT Arrow | Move / Lean Left |
| → RIGHT Arrow | Move / Lean Right |
| SPACE | Pause Game |

---

##  Technical Overview

- **Language:** Java  
- **Framework:** Java Swing / AWT  
- **Architecture Pattern:** MVC-like structure  

### Structure Breakdown

- **Controllers**
  - Sound management
  - Game logic control

- **Models**
  - Player
  - Vehicles
  - Police
  - Trees
  - Other game entities

- **Views**
  - Menu screen
  - Game screen
  - Game Over screen

---

##  How to Run

###  Prerequisites

- Java Development Kit (JDK) installed

---

###  Compilation

Compile source files located in the `scr` directory:

```bash
javac scr/main/GameMenu.java
```

---

###  Execution

Run the main class:

```bash
java scr.main.GameMenu
```

---

##  Project Structure

```
resources/
│
├── images/              # Game sprites & UI elements
├── buttons/             # Button assets
└── sounds/              # Background music & effects
│
scr/
│
├── controller/          # Game logic & sound management
├── models/              # Player, Police, Cars, Trees, etc.
├── views/               # UI screens & RunGame loop
├── utils/               # Utilities (Map generation, helpers)
└── main/                # Entry point (GameMenu.java)
```

---

##  Summary

Running Man is a chaotic arcade survival game combining:

- Fast reflex gameplay
- Dynamic traffic systems
- Audio feedback
- Score tracking
- MVC-based Java architecture

Survive the streets as long as possible — or crash trying.

## Video demo

![demo](https://github.com/user-attachments/assets/0e45242c-366d-4665-b7cd-027ec09f5c75)
