Pac-Man Cleans the Maze: A C++ Text Adventure
Introduction
Welcome to Pac-Man Cleans the Maze, a unique text-based adventure game developed in C++. This project reimagines the classic Pac-Man universe with an environmental twist. Instead of just munching dots, you'll guide Pac-Man on a crucial mission to cleanse the labyrinth of "trash remnants", contributing to a cleaner world.

Navigate through various maze sections, collect scattered waste items, and strategize your use of "power pellets" to temporarily turn the tables on the mischievous ghosts, who now embody the persistence of pollution. Along the way, Ms. Pac-Man will act as your insightful ally, offering guidance and assistance. Your ultimate goal is to collect all the trash to restore cleanliness to the world and achieve victory!

This project serves as a foundational exercise in C++ programming, demonstrating core concepts such as Object-Oriented Programming (OOP), textual interaction, and game state management.

Features
Text-Based Exploration: Navigate the labyrinth through textual descriptions and directional commands.

Trash Collection: Collect "trash remnants" in each maze section to earn points and advance your environmental mission.

Power Pellet Mechanic: Consume power pellets to temporarily scare ghosts, making them vulnerable for consumption.

Ghost Encounters: Avoid or "eat" the four iconic ghosts (Blinky, Pinky, Inky, Clyde), each with unique behaviors.

Ms. Pac-Man Ally: Interact with Ms. Pac-Man for hints, assistance, and power-ups.

Score and Lives System: Track your progress and manage your lives as you brave the polluted maze.

Victory/Defeat Conditions: Win by collecting all trash or lose if Pac-Man runs out of lives.

How to Play
Start the Game: Run the compiled executable.

Navigate: Use directional commands (e.g., move north, move south, move east, move west) to move between maze sections.

Clean Up: Type collect trash or collect to pick up all trash items in your current location.

Power Up: If a power pellet is present, type eat power pellet or eat to consume it and scare the ghosts.

Interact: If Ms. Pac-Man is in your location, type talk or talk to ms. pac-man to converse with her.

Watch Out for Ghosts: If a ghost in its normal state catches you, you lose a life. If a ghost is scared, you can "eat" it for points.

Win: Collect all the trash in the maze.

Lose: Run out of lives.

Exit: Type exit or quit to end the game.

Technical Details
This game is built entirely in C++ and designed to run in a console environment. Key programming concepts demonstrated include:

Object-Oriented Programming (OOP): Utilizing classes like Player (Pac-Man), Ghost, TrashItem, PowerPellet, Location, WorldManager, and GameEngine to model game entities and their interactions.

Standard Library Containers: Extensive use of std::map for location exits and std::vector for managing items and ghosts within locations.

Textual Input/Output: Basic console I/O for player commands and game feedback.

Modular Design: Code is organized into multiple header (.h) and source (.cpp) files for better maintainability and scalability.

Getting Started (Compilation)
To compile and run this game, you will need a C++ compiler (like GCC or MinGW).

Save the files: Save all the .h and .cpp files into a single directory.

GameEntities.h

GameEntities.cpp

GameManager.h

GameManager.cpp

main.cpp

Compile: Open your terminal or command prompt, navigate to the directory where you saved the files, and execute the following command:

g++ main.cpp GameEntities.cpp GameManager.cpp -o pacman_game

Run: After successful compilation, run the executable:

./pacman_game

(On Windows, you might just type pacman_game.exe or pacman_game)

Future Enhancements
Advanced Ghost AI: Implement more sophisticated movement patterns for ghosts (e.g., pathfinding, chasing algorithms).

Timed Power Pellet Effects: Add a timer for the "scared" state of ghosts.

Save/Load Game Functionality: Implement saving and loading game progress to/from a file.

More Complex Mazes: Design larger and more intricate maze structures with varied challenges.

Special Events: Introduce random events or more structured mini-quests.

Visual Enhancements: Explore using console libraries (like ncurses) for a more dynamic text-based interface.
