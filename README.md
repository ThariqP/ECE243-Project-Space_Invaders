# Space Invaders (ECE243 Final Project)

## ⚠️ Important Note on Running the Game

Before playing, please go through the PDF report to understand the game mechanics and controls.

### Key Function to Note: `wait_for_vsync()` (lines 418-422)
- On **line 419**, there is a comment with important instructions:
  1. **First**, compile and run the program as it is.  
     - If the VGA display appears to glitch, proceed to step 2.  
  2. **Then**, modify the last digit in line 419’s comment (change `2` → `3`) and recompile & run.

**Summary:**  
- Compile and run **once** as-is  
- If necessary, modify the last digit on line 419 from `2` → `3`, then recompile and run again  

**Why this is needed:**  
- The way the VGA driver was implemented in this project is slightly different.  
- This adjustment ensures that the initialized pixel buffer and memory locations are properly handled, preventing display glitches.

---

## 🎮 Enjoy the Game!
Have fun playing Space Invaders and experimenting with the FPGA implementation!
