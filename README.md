# Binary Echoes

**Course:** COMP3421/9415 - Computer Graphics (2025 T3)
**Project Type:** 3D Platformer & Puzzle Video Game

## 1. Project Overview
"Binary Echoes" is a third-person 3D puzzle-platformer set in a cosmic environment inspired by Pluto and Charon. The player controls an energy entity named "Echo" to restore the broken bond between the two planets.

The primary objective is to navigate the planetary terrain, solve environmental puzzles, and activate the "Resonance Spires" (Towers) to restore the universe's harmony.

## 2. How to Launch
1.  **Unzip** the submitted project folder.
2.  Run the executable file: **`BinaryEchoes.exe`**.
3.  *Note:* Source files can be accessed via the GitHub link provided below.

## 3. Controls
### Movement
* **W / A / S / D**: Move Character
* **Spacebar**: Jump
* **Shift + (W/A/S/D)**: Dash (Quick movement/dodge)
* **Mouse**: Rotate Camera

### Abilities & Interaction
* **Q**: **Laser Interaction** (Fire a beam to interact with Crystals and solve puzzles)
* **C**: **Guide** (Summon a "Wisp" visual guide to show the next objective)
* **H**: **Toggle Flight Mode** (Turn flight On/Off)
* **R**: Ascend (While in Flight Mode)
* **F**: Descend (While in Flight Mode)

## 4. Debug / Cheat Keys (For Markers)
To assist with testing and grading, the following keys allow immediate access to abilities that are normally unlocked later in the game:
* **1**: Unlock **Laser** Ability
* **2**: Unlock **Flight** Ability
* **3**: Unlock **Dash** Ability

---

## 5. Development & Contribution Breakdown

### Joint Development (Collaborative Core Systems)
* **Custom Planetary Gravity System**: Collaborated on core character movement logic for spherical surfaces and gravity field transitions.
* **Dynamic Character Movement**: Tuned physics and animation states for smooth planetary traversal.

### Individual Contributions: William (Student ID: z5318851)
**Key Focus: Advanced Locomotion, Level Design (Planet B), & Environment Art**

* **Flight System (Gameplay Programming)**: Implemented the flight state machine, allowing detachment from planetary gravity and full 3D vertical movement (Ascend/Descend).
* **Dash Mechanics**: Developed velocity-based impulse calculations for rapid dodging and gap traversal, including cooldowns.
* **Level Design (Planet B - Charon)**: Designed and sculpted the second planet's landscape, specifically structured to test Flight and Dash mastery with verticality.
* **Environment Art & Lighting**: Created the custom Cosmic Skybox/Starfield and implemented Global Illumination to match the specific visual tone.
* **UI Systems**: Designed the Main Menu Widget (`WBP_MainMenu`) and game loop logic.

### Individual Contributions: Tom
**Key Focus: Interaction Mechanics, Puzzle Logic, & VFX**

* **Interaction System**: Developed `LineTraceByChannel` raycasting for the Laser and created the `BPI_Interactable` interface.
* **Navigation System**: Designed the "Wisp" guide (`BP_Wisp`) using Spline Components to lead players.
* **Puzzle & Logic**: Created the `BP_TowerManager` for sequential and single-target puzzles, including cinematic transitions.
* **Game Objects**: Implemented Timed Crystals, Gate/Ice Wall logic, and Shield Cages.
* **VFX (Tech Art)**: Created custom Niagara Systems for lasers and procedural Energy Shield materials.
* **Level Design (Planet A)**: Designed the North Pole (Intro) and South Pole (Advanced) regions.

---

## 6. Source Control
**GitHub Repository:** [https://github.com/WilliamLiu5318851/BinaryEcho](https://github.com/WilliamLiu5318851/BinaryEcho)
