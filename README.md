## Description

In a banking system, creating a new bank account requires providing the account number, the account
holder's name, and an optional initial deposit. If the account holder does not have funds to deposit at the
moment of account creation, the initial deposit is simply not performed, and the account balance starts at zero.

Once a bank account is created, the account number can never be changed. The account holder's name, however, may be updated 
(for example, due to a legal name change).

The account balance cannot be modified arbitrarily. It must be protected by proper mechanisms:

- The balance increases only through deposits.
- The balance decreases only through withdrawals.
- Each withdrawal incurs a fixed fee of $5.00.
- The account is allowed to become negative if the balance is insufficient to cover the withdrawal and/or the fee.

This program registers a new bank account, allowing the user to choose whether to provide an initial deposit.
After the account is created, the program performs a deposit and then a withdrawal, displaying the updated account data after each operation.
