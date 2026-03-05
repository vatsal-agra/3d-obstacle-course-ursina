# 3D Obstacle Course Game (Obby)

A first-person 3D obstacle course game built in Python using the Ursina engine — featuring four progressively harder levels, hidden trigger blocks, fake decoy blocks, and a full in-game UI.

## Gameplay

You start on a small platform surrounded by white blocks — some are decoys, one is a hidden trigger. Find and click the trigger block to reveal the first obstacle course. Navigate the floating platforms to reach the next base, find the trigger there, and unlock the next level. Four levels total, each harder than the last.

- **Level 1** — Green platforms
- **Level 2** — Orange platforms  
- **Level 3** — Pink platforms
- **Level 4** — Yellow platforms (hardest)

Fall off? Press **F5** to restart.

## Features

- First-person 3D movement and camera
- 4 distinct obstacle course levels that unlock progressively
- Hidden trigger blocks that reveal the next course on click
- Fake decoy blocks to mislead the player
- In-game how-to-play instructions rendered in 3D space
- Level completion text on screen as you progress
- Win screen on completing all 4 levels

## Tech Stack

- **Python**
- **Ursina Engine** — 3D game engine built on top of Panda3D
- **Ursina FirstPersonController** — built-in FPS movement and camera

## How to Run

```bash
# Install dependencies
pip install ursina
pip install playsound

# Run the game
python obby.py
```

## Controls

| Action | Key/Input |
|--------|-----------|
| Move | W / A / S / D |
| Look around | Mouse |
| Jump | Space |
| Click block | Left Mouse Button |
| Quit (on hovered block) | X |
| Restart | F5 |

## Key Concepts Demonstrated

- 3D scene construction using voxel-based architecture
- Event-driven input handling in a game loop
- Object-oriented game entity design
- Progressive level unlocking via trigger mechanics
- First-person 3D movement and collision

---

**Author:** Vatsal Agrawal  
**GitHub:** [github.com/vatsal-agra](https://github.com/vatsal-agra)  
**LinkedIn:** [linkedin.com/in/vatsal-agrawal-a7a9641b0](https://linkedin.com/in/vatsal-agrawal-a7a9641b0)
