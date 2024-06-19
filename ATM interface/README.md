1. **BankAccount Class**:
   - Manages the account balance.
   - Methods: `withdraw(double amount)`, `deposit(double amount)`, `getBalance()`.

2. **ATM Class**:
   - Interacts with `BankAccount` to perform transactions.
   - Methods: `withdraw(double amount)`, `deposit(double amount)`, `checkBalance()`.

3. **ATMinterface Class**:
   - Runs the application.
   - Initializes `BankAccount` with a starting balance.
   - Provides a console menu for user interaction.
   - Processes user choices: withdraw, deposit, check balance, or exit.
   - Repeats the menu until the user chooses to exit.
