# Brute-Force Password Strength Calculator v0.0 🛡️

A high-performance, C-based security tool designed to analyze and visualize password resilience against modern brute-force attacks. This program calculates the total number of possible combinations and estimates the exact theoretical time required for a hacker system to breach the password.

## 📊 Theoretical Estimation Benchmarks

The calculator operates under the cybersecurity "Worst-Case Scenario" rule, assuming the attacker knows the exact length and character types used:
* **Attack Speed:** 1,000,000,000,000 (1 Trillion) guesses / second
* **Complexity Handling:** Automatically adjusts calculations based on the password's character pool size (numbers, lowercase, uppercase, and special characters) and detects them auto.

## 🛠️ Installation & Usage

To compile and run this project, you need a standard C compiler (such as GCC or Clang) installed on your system.

1. Clone this repository:
   ```bash
   git clone git@github.com:AX10M-PH4R4D0X/Brute-Force_Password_Strength_Calculator-v0.0.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Brute-Force_Password_Strength_Calculator-v0.0
   ```
3. Compile the source file using standard C rules (`.c` extension):
   ```bash
   gcc main.c -o calculator
   ```
4. Run the executable:
   ```bash
   ./calculator
   ```

## ⚖️ License
This project is developed solely for "EDUCATIONAL PURPOSES" and to "RAISE CYBERSECURITY AWARENESS". Distributed under the **GNU GPLv3 License**. See the `LICENSE` file for details.
