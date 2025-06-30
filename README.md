
Box Pushing Game (Terminal Implemetation)

This is my simple implementation of the classic box-pushing puzzle game **Sokoban** using C++.

## 🎮 How to Play

- Move the player (`@`) using:
  - `W` – Up
  - `A` – Left
  - `S` – Down
  - `D` – Right
- Push boxes (`B`) onto target spots (`x`).
- When a box is on a target, it turns into `O`.
- Win the game by placing all boxes correctly.
- The game ends if a box gets into a deadlock position.

## 🧱 Game Elements

- `@` – Player
- `B` – Box
- `x` – Destination
- `O` – Box on Destination
- `#` – Wall
- `' '` – Empty space

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/sokoban.git
   cd sokoban
   ```

2. Compile the code:
   ```bash
   g++ let_2.cpp -o sokoban
   ```

3. Run the game:
   ```bash
   ./sokoban
   ```
   
Feel free to fork or modify this game. Have fun solving Sokoban puzzles in your terminal!
