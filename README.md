# Color-switch-replica
**Color Switch Replica** is a 2D mobile game made with Unity, where you control a character that jumps through obstacles, changing colors to match them. The game features dynamic color switching, a scoring system, a game over screen, object pooling for efficient performance, and responsive controls for both keyboard and touch input.
# Color Switch Replica

## Overview

Color Switch Replica is a 2D mobile game developed in Unity where players control a character that must navigate through obstacles by changing colors to match them. The game is designed to be challenging yet rewarding, encouraging players to achieve the highest score possible.

## Getting Started

To run this project on your local machine, follow the steps below:

### Prerequisites

- Unity 2021.1 or later
- A suitable IDE (e.g., Visual Studio or Rider)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/color-switch-replica.git
## Getting Started

1. Open the project in Unity.
2. Make sure all required packages are installed.
3. Press the "Play" button in the Unity Editor to start the game.

## Gameplay

- **Jump**: Use the space bar or left mouse button to make the character jump.
- **Match Colors**: Change the character's color by passing through color changers and ensure it matches the obstacles.
- **Score Points**: Earn points for successfully passing through color-matched obstacles.
- **Game Over**: The game ends when you collide with an obstacle that does not match your character's color. Press Enter to restart or Escape to exit.

## File Structure

- **Assets**: Contains all game assets including sprites, audio, and scripts.
- **Scripts**: C# scripts that control game logic, player movement, and spawning of obstacles.

## Key Scripts

- **Player.cs**: Controls the player's movement and color switching.
- **FollowPlayer.cs**: Ensures the game objects follow the player’s position.
- **LogicScriptCS.cs**: Handles score management and UI updates.
- **SpawnerScript.cs**: Manages the spawning of obstacles and color changers.
- **Rotator.cs**: Adds rotation effect to game objects.

## Contributing

Contributions are welcome! If you have suggestions for improvements or find bugs, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Unity Technologies for providing the game engine.
- The community for their inspiration and support.
