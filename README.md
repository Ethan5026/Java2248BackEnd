# Java2248BackEnd
With a UI and API given, a backend construction of the connected game, grid, and GameUtil classes was created to model each aspect of the game.

Rules:
  Tiles can be selected if the first two connections are the same level.
  After the first two selections, you can connect to upper levels.
  After each selection, the final tile is upped by one level, and selected tiles are removed.
  
ConnectedGame
  This class defines the rules and selections and manipulation of tiles. This includes setting up the game, randomizing the board, indicating what can and connect be selected at which time, and when a selection has been completed. Then, the selected tiles disappear, the tiles above will fall, and be replaced with random tiles. The last tile selected will be upped one level, and if it exceeds the maximum level (selected in constructor of game) then the smallest level will all be removed and raised by one. 
  
Grid
  This class models the grid of tiles and holds the information in each coordinate.
  
GameUtil
  This class is used when the save/load mode is used within the game, analysing the game's grid, and outputting it into/from a file.
  
