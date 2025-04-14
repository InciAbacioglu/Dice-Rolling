# Dice Roller (C Version)

A simple C program that simulates rolling three six-sided dice. Each die rolls a random number between 1 and 6. The program prints each individual roll and the total sum of all three dice.

---

How it works:
- The program uses `rand()` to generate random numbers and `srand(time(NULL))` to ensure different results on each run.
- A loop rolls 3 dice and stores the result in an array.
- After each roll, the result is printed and added to a total.
- At the end, the total of all rolls is displayed.

---

🧪 Example Output:

Roll 1: 4  
Roll 2: 2  
Roll 3: 6  
Total roll: 12

---

💻 Compile and Run:

gcc dice_roller.c -o dice  
./dice

---

✅ Requirements:
- A C compiler like GCC  
- Terminal / Command Line access  
- Works on Linux, macOS, Windows

---

Created with ❤️ by İnci Mercan Abacıoğlu  
Part of C Practice Projects – Randomization & Arrays
