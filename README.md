# Mini-Pacman 🎮

![Gameplay Demo](demo.gif)


A small **Pac-Man**-style game built in **C** using the **MiniLibX (MLX)** graphics library.

---

## 📜 Project Description

This project is a simple 2D game where the player controls a character moving around a maze, collecting points while avoiding enemies.  
The goal is to collect all points without getting caught!

The project was mainly created to practice:
- C programming fundamentals
- Working with graphics libraries (MLX)
- Basic game development logic

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone <repo copied>
   cd mini_pacman_inC

2. Clone MLX library if you haven't already.

         git clone https://github.com/42Paris/minilibx-linux.git mlx
  
3. Compile the project:
      
        make

5. Run the game:
   
         ./pac_man <map_path.ber>
   or:
   
         ./pac_man map.ber

---



🎮 Controls:

        Key | Action  
        ↑   | Move Up  
        ↓   | Move Down  
        ←   | Move Left  
        →   | Move Right  
        p   | Speed Up  
        m   | Speed Down  
        ESC | Quit the game  



📈 Features:  

        Player movement with collision detection
        
        Collectable dots (score system)
        
        Basic enemy move horizontal
        
        Victory and game-over conditions
        
        Smooth frame rendering



✨ Future Improvements:  

        - Enenemy follows the player
        - Screens for player loses or success
