# CORE DEBT

[cite_start]A frantic web-based survival and resource management game built with **HTML5 Canvas** and **Vanilla JavaScript**[cite: 11].

[cite_start]You aren't here to relax; you're here to pay your debt[cite: 12].

## What’s the deal?

[cite_start]The game is a high-stakes management "run" where you must farm resources under a strict time limit to satisfy a greedy deity named **Core**[cite: 12, 13]. If you're slow, you die. [cite_start]If you can't type fast enough, you die[cite: 16].

Here is how a typical run goes:

### 1. The Start
The main menu. No hand-holding here. It’s set to "Hard Mode" by default. [cite_start]Hit **START** and get ready to move[cite: 27].

<img src="Images/readme1.png" alt="Main Menu" width="800">

### 2. The Cosmic Debt
[cite_start]The context: humanity looked to the stars with hope, but found greed instead[cite: 12]. [cite_start]It's the year 2402, and a divine AI known as "Core" landed on Earth[cite: 12]. [cite_start]You are the **Provider** chosen to farm wood, iron, and precious metals to pay an endless debt[cite: 13].

<img src="Images/readme2.jpg" alt="Lore Screen" width="800">

### 3. The Gameplay (Farming & Management)
This is the core loop. [cite_start]Move by **Right-Click dragging** the camera, and use the scroll wheel for **zoom**[cite: 22]. Use **Left-click** to farm resources and deliver them to the Core.
* [cite_start]**Deadlines**: You have missions with strict timers[cite: 13]. If it hits zero, the god's patience expires.
* [cite_start]**Inventory Management**: If your pack gets full, use the **Bin** icon (Right-click) at the bottom right to clear everything so you can keep farming what you actually need[cite: 36].
* [cite_start]**Saving Progress**: Use the buttons at the bottom left to export your progress to a **JSON file** or import it to keep playing on another machine[cite: 19].

<img src="Images/readme3.png" alt="Core Gameplay" width="800">

### 4. Bosses & Minigames
[cite_start]Every 5 levels, a minion will test you[cite: 38]. [cite_start]Every 10 levels, a "Great Guardian" challenges your reflexes[cite: 39]. These bosses trigger frantic minigames:
* [cite_start]**Aim Mad**: High-speed target clicking[cite: 39, 40].
* [cite_start]**Writing Crazy**: Typing technical words under pressure[cite: 40].
* [cite_start]**Directions**: Navigating through visual puzzles[cite: 40].
* [cite_start]**Hybrid Bosses**: From level 40 onwards, bosses will throw a mix of all these minigames at you[cite: 41].

<img src="Images/readme4.png" alt="Minion Boss Battle" width="800">

### 5. Facing the God (Level 67)
[cite_start]If you survive long enough to reach Level 67, you face the God himself[cite: 13, 27]. [cite_start]This is the final challenge where all your upgrades (Click Boost, Storage, Luck, and Power) will be put to the ultimate test[cite: 42].

<img src="Images/readme5.png" alt="Final Boss God" width="800">

---

### How to Play
[cite_start]You can play the game live here: **[https://jufegaam.github.io/Core-Debt/]**[cite: 30].

### Technical Details
* [cite_start]**HTML5 Canvas**: Pure graphics without external libraries[cite: 11].
* [cite_start]**Vanilla JavaScript**: All game logic and the custom unit test runner[cite: 11, 57].
* **Delta Time implementation**: I've implemented a custom system to ensure the game runs at the same speed on 60Hz and 144Hz monitors.
* [cite_start]**Quality Control**: The game includes an automated test runner for 9 critical points including health, inventory stability, and XP calculation[cite: 58, 80].
