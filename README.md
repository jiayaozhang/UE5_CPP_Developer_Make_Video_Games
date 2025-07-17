# Crypt Raider 

A first-person dungeon exploration and puzzle game built with Unreal Engine 5. Navigate through ancient crypts, solve environmental puzzles, and uncover hidden treasures in this atmospheric adventure game.

##  Overview

[Crypt Raider is a 3D puzzle-adventure game](https://www.udemy.com/course/unrealcourse/?ranMID=39197&ranEAID=ue*79h9bSBU&ranSiteID=ue.79h9bSBU-P0zS7._gOTrh3wbPXDe.fw&LSNPUBID=ue*79h9bSBU&utm_source=aff-campaign&utm_medium=udemyads) where players explore mysterious underground crypts filled with ancient mechanisms, hidden passages, and challenging puzzles. This project demonstrates core Unreal Engine 5 features including physics simulation, lighting systems, and C++ gameplay programming.

##  Features

### Core Gameplay
- **First-Person Exploration**: Immersive first-person perspective with smooth character movement
- **Physics-Based Puzzles**: Interactive objects using Unreal Engine's physics system
- **Grabber Mechanic**: Pick up and manipulate objects to solve puzzles
- **Pressure Plate System**: Activate ancient mechanisms by placing objects on pressure plates
- **Dynamic Lighting**: Atmospheric torch lighting and dynamic shadows
- **Secret Areas**: Hidden rooms and passages to discover

### Technical Features
- **C++ Gameplay Programming**: Core mechanics implemented in C++
- **Blueprint Visual Scripting**: Level-specific logic and interactions
- **Modular Level Design**: Reusable dungeon components for easy level creation
- **Audio System**: Ambient sounds and interactive audio feedback
- **Particle Effects**: Dust particles, torch flames, and atmospheric effects

##  Prerequisites

- **Unreal Engine 5.3+** (or latest version)
- **Visual Studio 2022** (for C++ development)
- **Windows 10/11** (64-bit)
- **Minimum 8GB RAM** (16GB recommended)
- **DirectX 12 compatible GPU**

##  Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/jiayaozhang/UE5_CPP_Developer_Make_Video_Games.git
   cd crypt-raider
   ```

2. **Generate Visual Studio project files**
   - Right-click on `CryptRaider.uproject`
   - Select "Generate Visual Studio project files"

3. **Open the project**
   - Double-click `CryptRaider.uproject` to open in Unreal Engine
   - Or open `CryptRaider.sln` in Visual Studio for C++ development

4. **Build the project**
   - In Unreal Engine: Click "Compile" button
   - In Visual Studio: Build → Build Solution (Ctrl+Shift+B)

## Controls

| Action | Key/Button |
|--------|------------|
| Move Forward/Backward | W/S |
| Strafe Left/Right | A/D |
| Look Around | Mouse Movement |
| Jump | Spacebar |
| Grab/Release Object | E / Left Mouse Button |
| Sprint | Left Shift |
| Pause Menu | Escape |

## Game Mechanics

### Grabber System
- Point at objects and press **E** to grab
- Move grabbed objects with mouse movement
- Release objects to drop them or place on pressure plates
- Limited grab distance for realistic interaction

### Pressure Plates
- Require specific weight to activate
- Can trigger doors, bridges, or reveal secret passages
- Some plates require multiple objects or specific items

### Puzzle Types
1. **Weight Puzzles**: Find and place objects on pressure plates
2. **Sequence Puzzles**: Activate mechanisms in correct order
3. **Hidden Object Puzzles**: Locate secret items to progress
4. **Environmental Puzzles**: Use physics to overcome obstacles

##  Project Structure

```
CryptRaider/
├── Source/
│   ├── CryptRaider/
│   │   ├── Grabber.cpp          # Object interaction system
│   │   ├── Grabber.h
│   │   ├── Mover.cpp           # Moving platform/door logic
│   │   ├── Mover.h
│   │   ├── TriggerComponent.cpp # Pressure plate system
│   │   └── TriggerComponent.h
├── Content/
│   ├── Blueprints/             # Blueprint classes
│   ├── Maps/                   # Level files
│   ├── Materials/              # Textures and materials
│   ├── Meshes/                 # 3D models
│   └── Audio/                  # Sound effects and music
└── Config/                     # Project configuration files
```

##  Level Design

The game features interconnected dungeon rooms with various themes:
- **Entry Chamber**: Tutorial area with basic mechanics
- **Puzzle Halls**: Main gameplay areas with increasing difficulty
- **Treasure Rooms**: Reward areas with collectibles
- **Secret Passages**: Hidden areas for exploration

##  Known Issues

- Grabbed objects may occasionally clip through walls
- Pressure plates might not reset properly in certain conditions
- Performance drops in areas with multiple light sources



##  Screenshots

![Main Chamber](https://user-images.githubusercontent.com/38579506/210294175-7f6cae43-7761-4598-a19d-b5991dcb9cfb.png)
*The main puzzle chamber with ancient mechanisms*

![Grabber Mechanic](https://user-images.githubusercontent.com/38579506/210294275-27cfa234-1814-4250-909d-3f27fcddd489.png)
*Using the grabber to manipulate objects*

![Secret Area](https://user-images.githubusercontent.com/38579506/210294323-701295d6-bbf6-493c-8c19-5cf30331ce74.png)
*A hidden treasure room discovered through exploration*


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

*Built with Unreal Engine 5* 🎮
