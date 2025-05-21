# Bleach Tower Defense

A 2D tower defense game set in the Bleach universe, where players defend against waves of Hollows and other spiritual threats using various Shinigami towers and abilities.

## Features

- 2D tower defense gameplay with Bleach-themed content
- Multiple tower types based on different spiritual powers:
  - Zanpakuto: Basic melee tower with Shikai and Bankai releases
  - Kido: Magic-based tower with Hado, Bakudo, and Kaido spells
  - Quincy: Ranged tower with different arrow types and spirit particles
  - Fullbring: Environmental manipulation tower
- Enemy types from the Bleach universe:
  - Hollow: Basic enemy
  - Gillian: Medium enemy
  - Adjucha: Advanced enemy
  - Vasto Lorde: Boss enemy
  - Arrancar: Special enemy
- Advanced visual effects system:
  - Area effects (spell circles, barriers)
  - Particle effects (spirit particles, energy bursts)
  - Buff/debuff effects with stack counts
  - Environmental effects
- Sound system with:
  - Dynamic music system
  - Sound effects for all actions
  - Volume control for different categories
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
   git clone https://github.com/Wsh7Ash/TowerDefenseGame.git
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
   - Special abilities based on different Zanpakuto types

2. Kido Tower
   - Magic-based tower
   - Three spell types: Hado (attack), Bakudo (binding), Kaido (healing)
   - Spell charge system for powerful abilities
   - Good against groups of enemies

3. Quincy Tower
   - Ranged tower with different arrow types
   - Spirit particle system for enhanced attacks
   - Special abilities: Vollstandig and Letzt Stil
   - Good for long-range combat

4. Fullbring Tower
   - Environmental manipulation tower
   - Three object types: Paper, Metal, Liquid
   - Environmental charge system
   - Good for area control

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
│   ├── effects/          # Visual and sound effects
│   └── map/              # Map handling and editor
├── include/               # Header files
├── resources/            # Game assets
│   ├── textures/        # Images and sprites
│   ├── fonts/          # Font files
│   ├── sounds/         # Sound effects and music
│   └── maps/           # Map files
└── CMakeLists.txt       # Build configuration
```

## Next Steps

1. Tower Selection and Placement System
   - Implement tower selection UI
   - Add placement preview
   - Add placement validation
   - Implement tower rotation

2. Upgrade System UI
   - Create upgrade menu
   - Add upgrade previews
   - Implement upgrade effects
   - Add upgrade costs display

3. Text Rendering System
   - Add font loading
   - Implement text effects
   - Add damage numbers
   - Add UI text elements

4. Game State Management
   - Implement wave system
   - Add score tracking
   - Add resource management
   - Implement game progression

5. Additional Features
   - Add more tower types
   - Implement special abilities
   - Add more enemy types
   - Create additional maps

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 