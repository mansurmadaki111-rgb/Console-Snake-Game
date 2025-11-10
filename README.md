                                 Console Snake Game in C++

Project Overview:

This is a classic Snake game built in C++ for Windows consoles.  
The player controls a snake that moves around a 20x20 grid, eats fruits , grows longer, and avoids colliding with itself.  
The game keeps track of your score in real-time.  

Controls

- W → Move Up
 
- A → Move Left
  
- S → Move Down

- D → Move Right
  
- X → Exit the game  

 How It Works

The game uses:  

- C++ for logic and console output
  
- `<conio.h>` for keyboard input detection
  
- `<windows.h>` for `Sleep()` and console handling
  
- Arrays to track the snake's head and tail positions
  
- Simple game loop:
  
  1. Draw the board
     
  2. Take input
     
  3. Update game logic (movement, collision, fruit, tail)
     
  4. Repeat until game over  

 Game Features:

- Live console display of snake and fruit
  
- Growing tail when eating fruit
  
- Real-time score display
  
- Wrap-around screen edges (snake appears on opposite side)
  
- Self-collision detection ends the game



 How To Run:

1. Copy the code into a `.cpp` file, e.g., `snake.cpp`
   
2. Open it in a C++ IDE (Visual Studio, Code::Blocks, etc.)
   
3. Compile and run the program in a Windows console
   
4. Use the controls to play and watch your score grow!
   
