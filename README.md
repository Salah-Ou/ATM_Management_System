
## 🏧💳 ATM Simulation Project 💳🏧 
<strong><h3><mark> 🔎 Overview </mark></h3></strong> 
<p> This is a console-based ATM (Automated Teller Machine) simulation program written in C++. 
  It provides basic banking functionalities like account creation, login, balance checking, 
  deposits, withdrawals, and savings operations.
</p>

## <mark> 📌 Features </mark>
### 1. Account Management 

  - <strong> Create Account : </strong> Users can create a new bank account by providing :
  
    - Name 
    - Account number(masked input). 
    - PIN(masked input). 
    - Phone number. 
    - Address.
    - Initial balance. 
  
  - <strong> Login : </strong> Secure login with account number and PIN (both masked) 

### 2. Banking Operations 
  - ##### `Check Balance` : View account details and current balance. 
  - ##### `Desposit Money` : Add funds to your account.
  - ##### `Withdraw Money` : Take out money (with balance validation).
  - ##### `Savings` :  Special savings functionality to grow your balance. 


### 3. User Interface 
  - Color-coded console interface. 
  - Real-time clock display.
  - Loading animations with sound effects .
  - Input masking for sensitive information.  

### 4. Technical Details
#### a)- Dependencies
- Windows API (for console manipulation).
- Standard C++ libraries :
  -  ` <iostream> ` , ` <vector> ` , ` <iomanip> `.
  -  ` <conio.h> ` for keyboard input.
  -  ` <time.h> ` for time functions.
  -  ` <windows.h> ` for console and sound functions.
#### b)- Key Functions : 
- ` gotoxy() ` : Positions the console sursor.
- ` Time() ` : Displays current time.
- ` ATM ` class with all banking operations.
- Input masking for PIN and accounts numbers.

### 5. How to use
1. Compile the program using c++ compiler (testing on windows).
2. Run the executable.
3. Use the menu to :
    - First create an account (option 1).
    - Then login (option 2).
    - Perform banking operations (options 3-6).

## <mark>🗒️ Notes </mark>
- The program uses Windows-specific functions (like `Beep()` and console manipulation).
- All account data is stored in memory (not persisted to disk).
- The interface is designed for console with specific dimensions.

