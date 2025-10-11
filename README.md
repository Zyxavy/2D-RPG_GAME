# C++ 2D RPG Adventure 

## 🕹️ About the Project

This is a 2D RPG game developed in C++ using the [Raylib](https://www.raylib.com/) and [RayGUI](https://github.com/raysan5/raygui) libraries.

It includes exploration, battles, skills, inventory management, and multiple zones. The code is functional but still a bit messy and unoptimized, improvements are planned for future updates.

## ✨ Features

*  **World Exploration:** Traverse through multiple distinct zones.
*  **Turn-Based Combat:** Engage in strategic battles against various enemies.
*  **Skill System:** Utilize unique skills to gain an edge in combat.
*  **Inventory Management:** Collect and manage items found on your journey.
*  **Simple GUI:** A clean user interface powered by RayGUI.

##  Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

To build and run this project from the source, you'll need a C++ compiler and the Raylib library configured on your system.
* A C++ compiler (e.g., MinGW-w64 on Windows, GCC on Linux)
* [Visual Studio Code](https://code.visualstudio.com/) (recommended)
* [Raylib Library](https://github.com/raysan5/raylib/releases)

### How to Play

There are two ways to run the game:

**Option 1: Run the Executable**

1.  Go to the game's main folder.
2.  Double-click on `main.exe` to start the game.

**Option 2: Build from Source in VS Code**

1.  Clone the repository to your local machine:
    ```sh
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    ```
2.  Open the project folder in Visual Studio Code.
3.  Ensure your VS Code tasks (`tasks.json`) are configured to compile and link against the Raylib library files.
4.  Press `F5` to build and run the debug version.

## Future Plans

This project is a work in progress. Here are some of the planned improvements:
- [ ] Code refactoring and optimization for better performance.
- [ ] Bug fixing and general stability improvements.

## Development Timeline

| Date   | Update Summary                                                                           |
|--------|------------------------------------------------------------------------------------------|
| Feb 23 | Added Menu; Fixed Battle UI                                                              |
| Mar 4  | Added Character Selection; Fixed Bugs; Implemented Entities                              |
| Mar 11 | Added Barriers; Imported More Music                                                      |
| Mar 18 | Added More Music; Implemented `MusicFunctions.cpp/hpp`; Added Volume Slider                |
| Mar 23 | Added Inventory GUI                                                                      |
| Mar 26 | Replaced Enemy `struct` with `class`; Added AI Movement (Chase/Wander)                     |
| Mar 30 | Added New Enemy; Fixed Various Bugs                                                      |
| Apr 8  | Replaced Hero `struct` with `class`; Fixed Battle Bug; Added Enemy Stun Mechanic           |
| Apr 13 | Added Health Potions; Added Inventory Hover Sound Effects                                |
| Apr 17 | Added Multiple Enemy Instances; Added Level-Up Screen                                    |
| Apr 22 | Finished Level-Up Screen; Added Level-Up SFX                                             |
| May 3  | Fixed Battle UI Bugs; Added (Buggy) Battle Animations                                    |
| May 6  | Enabled Inventory Access in Battle; Added Health Display; Started Skill System (WIP)     |
| May 11 | Added Hero Skills (WIP)                                                                  |
| May 14 | Optimized Skills; Added Status Effects                                                   |
| May 15 | Fixed Battle Bugs; Added Player Buffs                                                    |
| Jun 4  | Added Rogue SFX; Added Energy Foods; Fixed Inventory Bugs; Adjusted Skill Damage         |
| Jun 10 | Made Trees Obstacles; Added More Orcs in Dungeon                                         |
| Jun 13 | Added Tree-Cutting Mechanic                                                              |
| Jun 21 | Added Tutorial Book                                                                      |
| Jun 25 | Added New Enemies (Tree, Ghost, Crab, Statue)                                            |
| Jun 30 | Added New Zone (Plains Land); Adjusted Enemy Scaling                                     |
| Jul 14 | Created Basic Storyline; Added NPCs, Dialog, Custom Maps, Items, and More Enemies/Bosses |
| Jul 29 | Added 3 New Zones; Added Boats and Sea Traversal                                         |
| Aug 23 | Added Sea Zone & Map; New NPCs, Enemies, Boss, Merchant, Potions, and Final Zones        |
| Aug 25 | Minor Ending Adjustments                                                                 |
| Sep 1  | 🎉 Finished the Game! (Minor bugs and balance issues remain)                             |


## Acknowledgements

* **raylib** by [Ramon Santamaria](https://github.com/raysan5) for the amazing game development library.
* **raygui** by [Ramon Santamaria](https://github.com/raysan5) for the simple and immediate-mode GUI.

##Credits

A special thanks to the artist who provided the soundtrack for this game.

* **Music by:** Alkakrab



---