# Café Application

A command-line Java application that simulates a café ordering system, built using clean architecture principles and proper logic separation.

## 📋 Project Requirements Met
* **Dynamic Menu:** Displays items with matching index numbers, names, and regional pricing (SEK).
* **Input Validation:** Prevents program crashes by explicitly validating user choices and quantities using looping checks (`while` loops).
* **Automated Discounts:** 
  * 15% discount automatically applied for verified loyalty members.
  * 10% discount automatically applied for non-members on orders exceeding 150 SEK.
* **Taxation Execution:** Applies a mandatory 12% VAT to the base price following discount deductions.
* **Method Separation:** Main orchestration handles project flow control while independent sub-methods execute computations and interface logs.

## 🛠️ How To Run
1. Open this project inside **IntelliJ IDEA**.
2. Navigate to `src/main/java/CafeApplication.java`.
3. Press `Shift + F10` or click the green **Play** arrow next to the class declaration.
4. Interact using the console window prompts at the bottom of the screen.
  
