# 🌞 Summer Adventure Game

A top-down 2D action game that combines the **Free Simple Summer Top-Down Tileset** with the **Bloody Alchemist Character Sprites**.

## Features

- **Three Playable Characters**: Switch between all three Bloody Alchemist variants (press 1, 2, or 3)
- **Enemy AI**: Multiple enemy variants patrol and chase the player
- **Combat System**: Slash attack (SPACE) with collision detection
- **Particle Effects**: Leaf particles spawn when taking/dealing damage and switching characters
- **Procedurally Generated World**: A randomly generated tile-based world with trees, houses, rocks, and more
- **Dynamic Enemy Spawning**: Enemies spawn as you progress, with a maximum limit
- **Health Bars**: Visual health indicators for enemies
- **Smooth Camera Follow**: Camera follows the player across the world
- **Kill Counter**: Track your combat progress

## How to Play

1. Open `game.html` in any modern web browser
2. Use **WASD** or **Arrow Keys** to move your character around the world
3. Press **SPACE** to slash nearby enemies
4. Press **1**, **2**, or **3** to switch between character variants
5. Defeat enemies to rack up kills!

## Controls

| Key            | Action                |
| -------------- | --------------------- |
| **W** or **↑** | Move Up               |
| **S** or **↓** | Move Down             |
| **A** or **←** | Move Left             |
| **D** or **→** | Move Right            |
| **SPACE**      | Slash Attack          |
| **1**          | Switch to Character 1 |
| **2**          | Switch to Character 2 |
| **3**          | Switch to Character 3 |

## Game Features

### Characters

- **Three playable variants** with all animations:
  - Idle (20 frames)
  - Walking (26 frames)
  - Running (14 frames)
  - Slashing (14 frames)

### Enemies

- Enemies spawn with random character variants
- **AI Behavior**:
  - Patrol when player is far away
  - Chase player when nearby (within 5 tiles)
  - Take damage from slash attacks
  - Display health bars
  - Knockback on hit
- **Difficulty**: Enemies spawn progressively as you advance

### Environment

- **81 unique tileset assets**:
  - Ground tiles (grass variations)
  - Props: houses, trees, rocks, barrels, and more
- **Procedurally generated maps** for variety

### Visual Effects

- **Leaf particles**: Spawn on character switch, damage dealt, and kills
- **Slash effect circles**: Show attack range during slash
- **Enemy health bars**: Red bars above enemies
- **Smooth animation blending**: Natural transitions between movement states

## Technical Details

- **Engine**: HTML5 Canvas
- **Language**: Vanilla JavaScript (no frameworks)
- **Asset Sources**:
  - Tileset: [Craftpix - Free Simple Summer Top-Down Vector Tileset](https://craftpix.net/)
  - Characters: [Craftpix - Free Bloody Alchemist Chibi Character Sprites](https://craftpix.net/)

## Browser Compatibility

Works on all modern browsers that support:

- HTML5 Canvas
- ES6 JavaScript
- Image loading
- RequestAnimationFrame

## World Size

- **Map Dimensions**: 16 × 12 tiles
- **Tile Size**: 64 × 64 pixels
- **Camera**: Follows player with smooth centering
- **Max Enemies**: 8 active enemies at once

## Game Balance

- **Player Speed**: 3 pixels/tick
- **Enemy Speed**: 1.5 pixels/tick
- **Slash Range**: 1.5 tiles
- **Slash Duration**: 15 frames
- **Enemy Health**: 30 points
- **Slash Damage**: 20 points
- **Enemy Spawn Rate**: One every 200 frames (max 8)

## Tips for Playing

1. Keep moving to avoid enemy attacks
2. Use the slash attack (SPACE) when enemies are close
3. Switch characters with 1/2/3 for visual variety
4. Watch for the red slash circle to know your attack range
5. Use terrain and buildings as cover

---

_Created with assets from CraftPix.net_
_Final version with full combat system and multiple characters_
