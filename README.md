# ATM
Mini Project : ATM Simulation System

ATM Simulation System
A simple Python-based ATM Simulation System that mimics the basic operations of an Automated Teller Machine (ATM).
This project is designed for learning purposes and demonstrates user authentication, balance management, deposits, withdrawals, and optional features like transaction history and PIN changes.- Transaction History: View past deposits, withdrawals, and balance checks.


✨ Features
✅ Mandatory
- User Authentication: PIN-based login system.
- Balance Enquiry: Check current account balance.
- Cash Deposit: Add money to your account.
- Cash Withdrawal: Withdraw money with balance validation.
🔄 Optional
- Transaction History: View past deposits, withdrawals, and balance checks.
- Change PIN: Update your PIN securely.
- Daily Withdrawal Limit: Restrict withdrawals beyond a set daily limit.
- Exit Option: Gracefully exit the program.

🛠️ Requirements
- Python 3.x
- No external libraries required (uses only built-in modules like datetime and sys).

🚀 How to Run
- Clone or download this repository.
- Open a terminal/command prompt in the project folder.
- Run the program:
python atm.py
- Enter the default PIN (1234) to log in.
- Initial balance: ₹5000
- Daily withdrawal limit: ₹20000

📖 Example Usage
Enter your PIN: 1234
✅ Authentication successful!

===== ATM Menu =====
1. Balance Enquiry
2. Deposit Cash
3. Withdraw Cash
4. Transaction History
5. Change PIN
6. Exit
Select an option: 1
💰 Current Balance: ₹5000




🔑 Customization
- Change the default PIN, initial balance, or daily withdrawal limit in:
atm = ATM(pin="1234", balance=5000, daily_limit=20000)
- Extend functionality by adding:
- Multiple user accounts
- Interest calculation
- Account locking after failed attempts

📜 License
This project is open-source and free to use for educational purposes.

Thank you
