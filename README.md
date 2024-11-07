# gamedatabase
Database managment system for game
The attached code game.cpp implements a Gamers Database Management System (DBMS) using C++. This DBMS allows for the management of player and game data, including the ability to load data from files, display player and game details, track player game history, and perform various operations on the database.
Key Features

Data Storage: The DBMS uses a Binary Search Tree (BST) to store player and game data. Each player and game is represented as a node in the BST.
Data Loading: The DBMS can load player and game data from two separate text files, Players.txt and Games.txt, respectively. The data is parsed and inserted into the BST.
Data Manipulation: The DBMS provides the following operations:

Displaying the top N players based on the number of games played
Displaying the details of a specific player, including the games they have played
Checking if a player has played a specific game
Showing the layer number (depth in the BST) of a given player or game
Saving the database to a file
Deleting a specific entry (player or game)
Displaying the first N layers of the BST
Showing the path from the root to a specific node
Editing the details of a specific entry

Error Handling: The DBMS includes error handling for various cases, such as when a file cannot be opened or an entry is not found in the database.
Randomization: The DBMS uses a seed value (based on the user's roll number) to randomize the loading of player data, skipping some lines based on a probability.
Usage
Compile the game.cpp file using a C++ compiler.
Follow the on-screen menu to perform various operations on the Gamers Database.
File Formats
The DBMS expects the following file formats:
Players.txt:
Each line represents a player and contains the player's ID, name, phone number, email, and password, separated by commas.
After the player's basic information, the line may contain a list of game IDs and their corresponding scores, also separated by commas.
Games.txt:
Each line represents a game and contains the game's ID, title, publisher, developer, rating, and number of downloads, separated by commas.
Conclusion
The Gamers Database Management System (DBMS) provides a basic, console-based interface for managing player and game data. It demonstrates the use of a Binary Search Tree (BST) data structure and various operations on it, including insertion, deletion, and traversal. The DBMS can be further extended and improved to meet the needs of a more complex game data management system.
