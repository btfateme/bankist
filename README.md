# Bankist App

## Overview

The Bankist App is a JavaScript-based banking application that demonstrates fundamental concepts of JavaScript, including DOM manipulation, event handling, data formatting, and more. The application allows users to simulate banking operations such as deposits, transfers, loans, and account management.

This project provides a hands-on way to learn and practice JavaScript in a real-world scenario, showcasing interactive features and data handling.

## Features

- **User Authentication**: Login with a username and PIN.
- **Account Overview**: Display of account movements, balance, and transaction summaries.
- **Money Transfer**: Transfer funds between accounts.
- **Loan Application**: Request a loan if certain conditions are met.
- **Account Closure**: Close the current account.
- **Sorting Transactions**: Sort and display transactions in ascending/descending order.
- **Logout Timer**: Automatic logout after a period of inactivity.

## Technologies Used

- HTML
- CSS
- JavaScript (ES6+)

## Setup

1. **Clone the repository**:

   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the project directory**:

   ```bash
   cd bankist-app
   ```

3. **Open `index.html`** in your preferred browser.

## Code Overview

### Data

The app uses two predefined accounts (`account1` and `account2`) with attributes such as `owner`, `movements`, `interestRate`, `pin`, `movementsDates`, `currency`, and `locale`.

### Functions

- `formatDate(date, locale)`: Formats date into a human-readable format based on locale.
- `formatCur(value, locale, currency)`: Formats currency values based on locale and currency.
- `startLogoutTimer()`: Initializes and manages the logout timer.
- `displayMovements(acc, sort = false)`: Displays account movements with optional sorting.
- `displayBalance(acc)`: Displays the current balance of the account.
- `calcDisplaySummary(acc)`: Calculates and displays the summary of transactions (incomes, outgoings, and interest).
- `creatUsernames(accs)`: Generates usernames from account owners' names.
- `updateUI(acc)`: Updates the UI with the latest account data.

### Event Listeners

- **Login Button**: Authenticates users and displays account information.
- **Transfer Button**: Handles fund transfers between accounts.
- **Close Account Button**: Closes the account if the correct username and PIN are provided.
- **Loan Button**: Processes loan applications.
- **Sort Button**: Toggles sorting of transaction history.

## Usage

1. **Login**: Enter a username and PIN to log in.
2. **Transfer**: Input a recipient's username and the amount to transfer.
3. **Apply for Loan**: Specify the amount for the loan.
4. **Close Account**: Enter your username and PIN to close your account.
5. **Sort Transactions**: Click the sort button to toggle between ascending and descending order of transactions.

<!-- ## Demo

A live demo can be viewed [here](#). (Replace with your actual demo link if available) -->

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Jonas Schmedtmann](https://github.com/jonasschmedtmann) for inspiration and guidance.
- [MDN Web Docs](https://developer.mozilla.org/en-US/) for JavaScript references and documentation.

Feel free to contribute to the project by submitting pull requests or opening issues if you encounter any problems or have suggestions for improvements.

---

If you have any questions or need further assistance, please reach out via [email](mailto:btfateme@gmail.com) or open an issue on GitHub.
