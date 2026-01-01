🏧 ATM Withdrawal Simulation (C Programming)

##  Project Title
ATM Withdrawal Simulation

##  Topic Name
Simulate ATM Withdrawal

---

 ## Objective
To simulate a basic ATM cash withdrawal system using **C programming**, where the program validates the withdrawal amount and updates the account balance accordingly.

---

##  Tech Stack
- **Programming Language:** C  
- **Code Editor:** VS Code  
- **Version Control:** Git & GitHub  

---

 📝 Project Description
This project simulates the core functionality of an **ATM withdrawal process**.

The user enters a withdrawal amount, and the program checks:
- Whether the entered amount is **positive**
- Whether **sufficient balance** is available  

If both conditions are satisfied:
- The withdrawal is processed  
- The updated account balance is displayed  

Otherwise:
- An appropriate error message is shown  

This project demonstrates the use of:
- Conditional statements (`if-else`)
- User input handling
- Arithmetic operations in C  

---

## Detailed Walkthrough (How to Approach the Problem)

1. Declare a variable `balance` and initialize it with a fixed amount  
2. Ask the user to enter the withdrawal amount  
3. Check if the entered amount is greater than zero  
4. If valid, check whether the withdrawal amount is less than or equal to the balance  
5. If both conditions are true:
   - Subtract the amount from the balance  
   - Display the updated balance  
6. If any condition fails:
   - Display an appropriate error message  

---

## Algorithm

1. Start  
2. Initialize balance  
3. Input withdrawal amount  
4. If amount ≤ 0  
   - Display error message  
5. Else if amount ≤ balance  
   - Deduct amount from balance  
   - Display updated balance  
6. Else  
   - Display insufficient balance message  
7. Stop  

---

## 💻 Sample Output
