# Raffle Prize Picker

This program collects five participant names and three prize names from the user. The last prize entered is treated as the Grand Prize. After collecting all inputs, the script uses `random.sample()` to randomly select three unique winners. Each winner is matched to a prize in the same order the prizes were entered. The first two winners receive regular prizes, and the third randomly selected winner receives the Grand Prize. This project practices loops, user input, list handling, and random selection without repeats.

---

## How It Works
1. The program asks the user to enter five participant names, each stored in a list.
2. The user then enters three prize names, with the final prize being the Grand Prize.
3. The program randomly selects three different winners from the participant list.
4. Winners are paired with prizes in order:
   - Winner 1 → Prize 1  
   - Winner 2 → Prize 2  
   - Winner 3 → Grand Prize  
5. The results are printed, clearly marking the Grand Prize winner.

---
## Skills Practiced

- for loops
- List creation and storage
- User input handling
- Random selection with random.sample()
- Conditional logic for special-case winners
