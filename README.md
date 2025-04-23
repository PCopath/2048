# 2048
 2048 Game – Unity (C#)
A Unity-based clone of the classic 2048 puzzle game, written in C#, structured with modular tile and grid logic.

🎮 How to Play
Combine matching tiles by moving them using the arrow keys.

Merged tiles double their value (e.g., 2 + 2 → 4).

Your goal is to reach 2048!

🧠 Script Overview
GameManager.cs – Handles game state, spawning tiles, and restart logic.

Tile.cs – Represents individual tiles and their values.

TileBoard.cs – Manages tile movement and merges based on input.

TileCell.cs – Defines grid cells; tracks which tile is present.

TileGrid.cs – Initializes and stores the grid layout.

TileRow.cs – Utility class for evaluating and resolving row-based merges.

TileState.cs – Holds tile value and visual styling (e.g., color, sprite).

🔧 Setup in Unity
Clone or download the repository.

Open the project via Unity Hub.

Open MainScene and press ▶️ to play.

✅ Features
Fully functional 2048 mechanics.

Modular C# script architecture.

Scalable tile logic and game restart capability.
