# Bleach Tower Defense

A 2D tower defense game set in the Bleach universe, where players defend against waves of Hollows and other spiritual threats using various Shinigami towers and abilities.

## Features

- 2D tower defense gameplay with Bleach-themed content
- Multiple tower types based on different Zanpakuto abilities:
  - Zanpakuto: Basic melee tower
  - Kido: Magic-based tower
  - Shikai: First release tower
  - Bankai: Final release tower
- Enemy types from the Bleach universe:
  - Hollow: Basic enemy
  - Gillian: Medium enemy
  - Adjucha: Advanced enemy
  - Vasto Lorde: Boss enemy
  - Arrancar: Special enemy
- Upgrade system for towers and abilities
- Custom map editor
- Resource management and strategic gameplay
- Menu system with options and settings

## System Requirements

- Windows 7 or later
- 4GB RAM minimum
- OpenGL 3.0 compatible graphics card
- 500MB free disk space

## Dependencies

- SFML 2.5 or later
- CMake 3.10 or later
- C++17 compatible compiler

## Building the Project

1. Install SFML:
   - Download SFML from https://www.sfml-dev.org/download.php
   - Extract to a known location
   - Set SFML_DIR environment variable to the SFML CMake directory

2. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/TowerDefenseGame.git
   cd TowerDefenseGame
   ```

3. Create build directory and build:
   ```bash
   mkdir build
   cd build
   cmake ..
   cmake --build .
   ```

4. Run the game:
   ```bash
   ./TowerDefenseGame
   ```

## Game Controls

- Left Mouse Button: Place/Select towers
- Right Mouse Button: Cancel tower placement
- ESC: Open menu
- Space: Pause/Resume game
- 1-9: Quick select tower types
- U: Upgrade selected tower
- S: Sell selected tower

## Tower Types

1. Zanpakuto Tower
   - Basic melee tower
   - Good for early game
   - Can be upgraded to Shikai and Bankai

2. Kido Tower
   - Magic-based tower
   - Slower attack speed but higher damage
   - Good against groups of enemies

3. Shikai Tower
   - First release of Zanpakuto
   - Increased range and damage
   - Special abilities based on different Zanpakuto types

4. Bankai Tower
   - Final release of Zanpakuto
   - Highest damage and range
   - Unique ultimate abilities

## Enemy Types

1. Hollow
   - Basic enemy
   - Low health and damage
   - Fast movement speed

2. Gillian
   - Medium enemy
   - Moderate health and damage
   - Slower than basic Hollows

3. Adjucha
   - Advanced enemy
   - High health and damage
   - Special abilities

4. Vasto Lorde
   - Boss enemy
   - Very high health and damage
   - Multiple special abilities

5. Arrancar
   - Special enemy
   - Balanced stats
   - Unique abilities

## Project Structure

```
TowerDefenseGame/
├── src/                    # Source files
│   ├── entities/          # Game entities (Towers, Enemies, etc.)
│   ├── managers/          # Resource and state management
│   ├── ui/               # User interface components
│   ├── renderer/         # Rendering system
│   └── map/              # Map handling and editor
├── include/               # Header files
├── resources/            # Game assets
│   ├── textures/        # Images and sprites
│   ├── fonts/          # Font files
│   ├── sounds/         # Sound effects
│   └── maps/           # Map files
└── CMakeLists.txt       # Build configuration
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 