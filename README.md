# HexPeriment

This is a little project experimenting with hexes, pathfinding, line of sight and the Dart programming language.

## Description
This projects is presented as a pseudo game displaying, on a hex map, the best path between a character and a treasure chest. This path is computed according to the ground type of each hex on the map. The map can be modified with several ground type (mountain, hill, sand...) associated with different value, updating the best path on the fly.

## Code
The code is split between 2 modules :

### Hex
Module containing the basic operation dealing with hexes.
- Hex.dart : basic hex data structure and methods
- geometry.dart : geometric computation such as intersection between line and hexes.

### HexPeriment
Module containing the code for all the features : 
 - astarAlgorithm.dart : implement the pathfinding with hexes.
 - visibilityAlgorithm.dart : implements the line of sight algorithm.
 - game_info.dart : main file creating the game.
 - hex_renderer.dart : contains method for displaying the hexes on a canvas.


[Give it a try !](http://kiramind.github.io/Hex/web/index.html)
