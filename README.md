ATM Simulator
This program simulates an ATM machine where users can perform basic banking functions such as withdrawing money, depositing money, viewing their balance, and changing their PIN. The user must enter a card number that is present in the ATM_DETAILS.csv file to access the ATM functions. If the user wants to add or delete card numbers, they must do so manually in the ATM_DETAILS.csv file.

Getting Started
To use this program, you will need to have a C compiler installed on your computer. Once you have the compiler installed, you can download the program files and compile the program using the following command:

bash
Copy code
gcc atm.c -o atm
After compiling the program, you can run it using the following command:

bash
Copy code
./atm
Usage
When you run the program, you will be prompted to enter a card number. You must enter a card number that is present in the ATM_DETAILS.csv file. If the card number is invalid, the program will display an error message and exit.

If the card number is valid, you will be prompted to enter the 4-digit PIN associated with the card. If the PIN is incorrect, the program will display an error message and exit.

If the PIN is correct, you will be presented with the following menu:

Withdraw Money
Deposit Money
View Balance
Change PIN
You can choose the option that you want by entering the corresponding number. If you choose to withdraw or deposit money, you will be prompted to enter the amount. If you choose to view your balance, your balance will be displayed. If you choose to change your PIN, you will be prompted to enter a new PIN.

After you have performed the desired functions, the program will write the updated details to the ATM_DETAILS.csv file.

Contributing
If you find any bugs or issues with the program, feel free to create a pull request or submit an issue. Any contributions are welcome.


