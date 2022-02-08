Idea:
A turn-based strategy game in same the vein of Warlords (MS-DOS). Overcome your enemy to win!

MVP:
Pages
- Home (the game itself)
- About

What the user can do
- Produce, move, and attack with units on a grid
- Navigate between pages
- Win the game by defeating the enemy
- Login/Register to save the game
- Play with another person on the same computer

Database
- The game current game state can be saved and loaded (after account creation)
- One table for users
- For each user table, there is game data associated with that table (one user to many)
- Data saved for unit positions, turn number, and gold/currency


Additional features and notes
- Each unit would have multiple pieces of data associated with it (strength, who it belongs to, etc.)
- Terrain types should provide modifiers to battle

Potential enemy AI
- Produce, move, and attack with units
- Locate and decide to move towards units to attack
- Make basic decisions to attack in favorable conditions