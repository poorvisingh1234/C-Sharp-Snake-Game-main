# 🐍 Retro Snake Game in C#

A classic retro-style Snake game built using C#.
This console-based project focuses on clean object-oriented programming, real-time input handling, and fundamental game loop logic — all rendered with simple ASCII characters.

---

## 🎮 Features

- ✅ Object-oriented structure with a custom `Point` class
- ✅ Console-based rendering of walls and snake
- ✅ Real-time snake movement via arrow keys
- ✅ Snake direction logic and prevention of instant reversal
- ✅ Snake body tracking using history list
- ✅ Collision detection with walls and self
- ✅ Game Over condition and screen reset

---

## 📺 Chapters / Development Steps

1. **Create a New Class**  
   Defined a `Point` class with operator overloading for equality checks.

2. **Create Playing Area**  
   Designed a bounded console grid using coordinate constraints.

3. **Print the Walls**  
   Rendered the play area borders using ASCII symbols.

4. **Print the Head**  
   Placed and updated the snake’s head at each move.

5. **Fix Equal Operator**  
   Implemented proper equality logic to compare positions correctly.

6. **Snake Movement**  
   Used a game loop and directional vectors to move the snake.

7. **Snake Direction**  
   Captured keyboard inputs using `Console.ReadKey()` to change direction.

8. **Snake History**  
   Tracked the snake’s body using a list of past positions.

9. **Game Over Conditions**  
   Ended the game when the snake hit a wall or its own body.

---

## 🧠 What I Learned

- How to structure a C# console application using object-oriented principles  
- Implementing real-time input handling in a loop  
- Using lists to represent and update dynamic game elements  
- Creating game logic from scratch without external libraries

---

