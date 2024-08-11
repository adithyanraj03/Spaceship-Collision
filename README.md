# Space Collision Game

A space-themed collision game built in Unity using Playground Assets and custom scripts. Players navigate a spaceship through an asteroid field, avoiding collisions and aiming for high scores.

## Overview

In this game, players control a spaceship in a 2D space environment. The objective is to avoid asteroids and collect power-ups to score points. The game features various obstacles and power-ups to enhance the gameplay experience.

## Features

- **Spaceship Navigation:** Move your spaceship using keyboard controls.
- **Asteroid Field:** Dodge asteroids that appear randomly in space.
- **Power-Ups:** Collect power-ups to gain additional points or temporary abilities.
- **Score System:** Keep track of your score and aim for high scores.
- **Collision Detection:** Detect collisions between the spaceship and asteroids.

## Getting Started

### Prerequisites

- Unity 2021.1 or later
- Basic understanding of Unity and C# scripting

### Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/yourusername/space-collision-game.git
    cd space-collision-game
    ```

2. **Open the Project in Unity**

    - Launch Unity Hub.
    - Click on "Add" and navigate to the cloned project directory.
    - Select the project to open it in Unity.

3. **Import Playground Assets**

    The project uses Playground Assets for visual elements and environment.
    Ensure you have the Playground Asset Package imported into your Unity project. If not, you can download it from the Unity Asset Store.

## How to Play

1. **Start the Game**

    Click on the "Play" button in the Unity Editor to start the game.

2. **Control the Spaceship**

    - Use the Arrow Keys or W, A, S, D keys to navigate the spaceship.
    - Avoid asteroids and collect power-ups to increase your score.

3. **Score and Collisions**

    - Your score is displayed on the screen.
    - Colliding with asteroids will end the game. Try to achieve the highest score possible!

## Scripts

The game includes several C# scripts to handle gameplay mechanics:

- **PlayerController.cs:** Manages spaceship movement and controls.
- **AsteroidSpawner.cs:** Spawns asteroids at random positions.
- **PowerUp.cs:** Handles power-up collection and effects.
- **ScoreManager.cs:** Tracks and displays the player's score.
- **GameManager.cs:** Manages game states, including game over and restarting.

## Customizing the Game

You can modify the following aspects to customize the game:

- **Asteroid and Power-Up Prefabs:** Adjust the size, speed, and appearance of asteroids and power-ups.
- **Player Controls:** Change control schemes or add additional features to the spaceship.
- **Game Settings:** Configure game difficulty, scoring, and other gameplay parameters.

## Troubleshooting

- **Missing Assets:** Ensure that all required Playground Assets are imported.
- **Collision Issues:** Verify that colliders are correctly attached to game objects.
- **Performance:** Adjust quality settings if the game runs slowly.

## Contributing

If you'd like to contribute to the project:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a description of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Playground Assets:** For providing visual elements and environment assets.
- **Unity:** For the powerful game development platform.
