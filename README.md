# Number Guessing Game

## Description
The **Number Guessing Game** is a simple Java console application where the player has to guess a randomly generated number. The system provides feedback on whether the guessed number is too high or too low. The game continues until the player guesses correctly or runs out of attempts.

## Features
- Generates a random number between 1 and 100.
- Provides feedback if the guess is too high or too low.
- Limits the number of attempts.
- Displays the score based on the number of attempts.
- Allows multiple rounds.

## How to Run
1. Compile the Java file:
   ```sh
   javac NumberGuessingGame.java
   ```
2. Run the program:
   ```sh
   java NumberGuessingGame
   ```

## Game Flow
1. The program generates a random number.
2. The player guesses the number.
3. The system provides feedback.
4. The game ends when the player guesses correctly or runs out of attempts.

---

# ATM Interface

## Description
The **ATM System** is a Java-based console application that simulates basic ATM functionalities. Users can log in, check their balance, withdraw and deposit money, transfer funds, and view transaction history.

## Features
- User authentication with user ID and PIN.
- View account balance.
- Withdraw and deposit money.
- Transfer funds between users.
- View transaction history.

## How to Run
1. Compile the Java file:
   ```sh
   javac ATMSystem.java
   ```
2. Run the program:
   ```sh
   java ATMSystem
   ```

## User Interaction Flow
1. The user enters their **user ID** and **PIN** to log in.
2. They select an option from the menu:
   - View Balance
   - Withdraw Money
   - Deposit Money
   - Transfer Money
   - View Transaction History
   - Exit
3. The system performs the selected operation and updates the balance.
4. The user can perform multiple operations until they choose to exit.

## Example Users
- **User1**: PIN - 12345, Balance - $0
- **User2**: PIN - 67890, Balance - $1000
- **User3**: PIN - 01234, Balance - $32000
- **User4**: PIN - 56789, Balance - $400000

## Notes
- Transactions are stored in a history log.
- Invalid inputs are handled properly.
- The system prevents overdrawing funds.

---

