# Fruit Ninja – Game Programming Project

A Unity-based Fruit Ninja-style game developed as a college Game Programming project. The project demonstrates fruit slicing, scoring, lives, bombs, random object spawning, game-over handling, and restart functionality.

## Features
- Fruit slicing using mouse input
- Score tracking
- Three-life system
- Bomb collision and game-over behavior
- Random fruit/obstacle spawning
- Sliced-fruit and juice effects
- Restart game functionality
- Endless gameplay loop

## Technologies
- Unity
- C#
- Unity Physics / Rigidbody
- TextMeshPro
- Unity UI

## Project Scripts
| Script | Purpose |
|---|---|
| `GameManager.cs` | Score, lives, game-over and restart management |
| `Blade.cs` | Mouse-controlled slicing blade |
| `Fruits.cs` | Fruit collision, scoring and slicing effects |
| `BombScript.cs` | Bomb rotation, explosion and game-over handling |
| `SpawnObjects.cs` | Random object spawning and movement |

## Gameplay
The player slices fruits with the mouse. Missing fruits reduces lives, while hitting a bomb ends the game. The report documents the game with screenshots showing the start screen, slicing, changing lives, and the game-over/restart screen.

## Assets
The original report documents sprites for a bomb and fruits including apple, coconut, orange, pear and watermelon. The report screenshots are included in `Screenshots/`.

## Documentation
The original college project report is included in `Documentation/`.

## Video
The project report provides this demonstration video link:
https://drive.google.com/file/d/1_uXGxpHYPQ4_Sw5wapHuYOvRad1uUYx/view?usp=sharing

## Important note
This repository is reconstructed from the submitted college project report. The report contains the C# source code and screenshots, but it does not contain the original Unity project folder, scene files, prefabs, or complete asset files. Therefore, this repository should not be presented as the original runnable Unity project.
