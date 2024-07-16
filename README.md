# ATM Application

This is a simple ATM application written in Java. The application allows users to create accounts, log in, view balances, withdraw funds, deposit funds, and transfer funds between accounts. 

## Features

- Create a new account with a customer number and PIN.
- Log in using a customer number and PIN.
- Access checking and savings accounts.
- View account balances.
- Withdraw and deposit funds.
- Transfer funds between checking and savings accounts.

## Prerequisites

- Java Development Kit (JDK) installed on your system.
- A Java IDE or text editor (e.g., IntelliJ IDEA, Eclipse, VS Code).

## How to Run

1. **Clone the repository** (or download the source code).

    ```sh
    git clone https://github.com/manishkmr49/Simple--ATM--Application.git
    ```

2. **Navigate to the project directory**.

    ```sh
    cd Simple--ATM--Application
    ```

3. **Compile the Java files**.

    ```sh
    javac OptionMenu.java Account.java
    ```

4. **Run the application**.

    ```sh
    java OptionMenu
    ```

## Usage

1. **Main Menu**:
   - **Type 1**: Log in to an existing account.
   - **Type 2**: Create a new account.

2. **Account Access**:
   - **Type 1**: Access Checking Account.
   - **Type 2**: Access Savings Account.
   - **Type 3**: Exit.

3. **Checking/Savings Account Menu**:
   - **Type 1**: View Balance.
   - **Type 2**: Withdraw Funds.
   - **Type 3**: Deposit Funds.
   - **Type 4**: Transfer Funds.
   - **Type 5**: Exit.

## Example Accounts

Two example accounts are pre-loaded into the system for testing purposes:

1. Customer Number: `952141`, PIN: `191904`
2. Customer Number: `123`, PIN: `123`

## Code Overview

- **OptionMenu.java**: Contains the main menu and options for account management.
- **Account.java**: Represents an account with methods for balance management and transactions.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

---

Feel free to customize this README file according to your specific needs.
