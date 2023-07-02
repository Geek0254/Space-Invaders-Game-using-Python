# Space-Invaders-Game-using-Python
This is a terminal-based Space Invaders game implemented in Python using the curses library. The game provides a classic arcade experience where the player controls a ground tank and shoots at invading aliens.

# Gameplay
The tank is controlled using the arrow keys, allowing movement left or right on the bottom row of the screen.
Press the spacebar to fire shots from the tank. The tank can have a maximum of three active shots at a time.
Aliens attempt to land by moving sideways across the screen. They initially number 30 in count and are positioned in three rows.
The aliens move in a zig-zag motion, changing direction and dropping down one row when they hit an edge.
Aliens have a 1% chance of randomly dropping bombs as they move.
Shots fired by the tank can destroy aliens, while bombs dropped by aliens can destroy the tank.
The game is won when all aliens are destroyed. The game is lost if the tank is destroyed or if an alien reaches the ground.

# Installation and Running the Game
Make sure you have Python installed on your system.
Clone this repository or download the space_invaders.py file.
Open a terminal and navigate to the project directory.
Run the game using the following command: python space_invaders.py
Enjoy playing the Space Invaders game in the terminal!

Please note that the curses library may have some compatibility issues on certain platforms. If you encounter any errors related to curses, refer to the troubleshooting section in the readme file or consider running the game in a different environment.

# Controls
Arrow keys: Move the tank left or right.
Spacebar: Fire a shot from the tank.
Q: Quit the game.

# Requirements
Python 3.x
curses library (for Unix-like systems)
windows-curses package (for Windows systems) [ pip install windows-curses ]
