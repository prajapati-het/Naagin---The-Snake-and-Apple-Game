Naagin - The Game

Naagin is a snake game built with Python using the Pygame library. The game features a leaderboard, dynamic snake movement, and customizable themes for the snake and background colors. The objective of the game is to control the snake, eat the food, and grow while avoiding collisions with the boundaries or itself.
Features

    Dynamic Snake Movement: The snake moves with wavy patterns, and the head has animated eyes.
    Customizable Themes: Players can customize the snake's head, body, strip, background, and food colors through a dropdown menu.
    Player Profiles: Players can create or select profiles and save high scores in a SQLite database.
    Leaderboard: Displays the top 10 high scores and player names.
    Smooth Graphics and Animations: Uses Pygame for smooth, real-time rendering of graphics.
    Interactive UI: Buttons for starting the game, viewing the leaderboard, and customizing themes.

Setup Instructions
Prerequisites

Before running the game, ensure that the following libraries are installed:

    Python 3.x
    Pygame
    Pygame Menu (for the dropdown customization menu)
    SQLite3 (included with Python)

Install required Python packages using pip:

bash

pip install pygame pygame-menu

File Structure

    game.py: The main game file containing the logic for snake movement, rendering, and interactions.
    homescreen.jpg: Background image for the game's home screen.
    player_data.db: SQLite database to store player profiles and high scores.
    home_music.mp3: (Optional) Background music for the home screen.

Make sure all required assets (images, sound files) are placed in the correct directory relative to the Python script.
How to Run the Game

    Clone or Download the Repository: Download or clone the project to your local machine:

    bash

git clone <repository_url>

Run the Game: Navigate to the project directory and run the main game file:

bash

    python game.py

    Gameplay:
        On the home screen, either create a new user or select an existing one.
        Customize the snake and background colors via the "Theme" button.
        View the leaderboard to see the top 10 players.
        Start playing and aim for the highest score!

Controls

    Arrow Keys: Control the snake's movement (up, down, left, right).
    ESC: Pause the game or exit menus.
    Mouse: Navigate through the home screen, leaderboard, and settings.

Game Screens

    Home Screen: Select an existing player, create a new player, or access the leaderboard and settings.
    Game Screen: Play the snake game. The snake grows as it eats food.
    Leaderboard: Displays the top 10 players with the highest scores.
    Settings: Customize the snake and background colors.

Saving and Loading Data

The game stores player data and high scores in an SQLite database (player_data.db). When a new player is created, their profile is stored with an initial high score of 0. If an existing player achieves a higher score, the database is updated accordingly.
Leaderboard

The leaderboard displays the top 10 players with the highest scores. This data is fetched from the SQLite database and is updated automatically after each game session.
Customization Options

Players can customize the snake's:

    Head Color
    Body Color
    Strip Color
    Background Color
    Food Color

These settings can be accessed through the "Theme" button on the home screen.
Future Enhancements

    Add sound effects during gameplay (e.g., when the snake eats food or crashes).
    Add more game modes or levels of difficulty.
    Improve the visuals with animated food or environment elements.
