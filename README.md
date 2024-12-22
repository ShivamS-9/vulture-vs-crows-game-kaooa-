# Vulture vs Crows Game (Kaooa game)

This is a simple turn-based game built using `pygame` where two players (Vulture and Crows) take turns placing and moving pieces on a geometric board. The objective is for either the Vulture or Crows to win by meeting specific adjacency conditions.

## Requirements

- Python 3.x
- `pygame` library
- 
## How to Play

### Players:
- **Vulture (Pink):** Controlled by player 1.
- **Crows (Orange):** Controlled by player 2.

### Objective:
- The Vulture's goal is to occupy specific points on the board.
- The Crows aim to block the Vulture's movement and occupy certain points to prevent the Vulture from achieving its objective.

### Gameplay:
- Players take turns selecting points on the board to place their pieces.
- The Vulture can move to adjacent points.
- Crows try to block the Vulture's path.
- The Vulture has the ability to "double" its move to another piece, which adds a strategic element.

### Endgame:
The game ends when one side completes its objective:
- If the Vulture places enough pieces in the required positions, the Vulture wins.
- If the Crows successfully block the Vulture, the Crows win.

## Board Layout

The board consists of connected points (represented by blue circles). Each point has an index and a set of adjacent points that determine the valid moves for each player.

### Color Coding:
- **Pink:** Vulture's pieces
- **Orange:** Crows' pieces
- **Blue:** Empty points
- **Black:** Lines forming the grid
