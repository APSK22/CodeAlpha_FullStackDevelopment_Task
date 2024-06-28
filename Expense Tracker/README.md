# Expense Tracker

## Overview

The Expense Tracker is a React application that assists you in managing your finances by monitoring your income and expenses. It offers a clear summary of your balance and a detailed list of all transactions.

## Features

- Display current balance
- Separate tracking for income and expenses
- Add new income or expense transactions
- View all transactions in a list
- Delete transactions from the list
- State management using Context API

## Installation

### Requirements

- Node.js installed on your machine
- npm (Node Package Manager) or yarn

### Installation Steps


1. **Install dependencies**

    Using npm:
    ```bash
    npm install
    ```

    Using yarn:
    ```bash
    yarn install
    ```

2. **Run the application**

    Using npm:
    ```bash
    npm start
    ```

    Using yarn:
    ```bash
    yarn start
    ```

   

## Usage


1. **Manage your financial records**

    - View your current balance displayed at the top.
    - Check a breakdown of your income and expenses.
    - Add new transactions via the provided form.
    - View and delete transactions from the list.



### Components

- **Header**: Displays the application's header.
- **Balance**: Shows the current financial balance.
- **IncomeExpenses**: Displays a breakdown of income and expenses.
- **TransactionList**: Lists all the transactions.
- **AddTransaction**: Form to add new transactions.

### Context API

- **GlobalProvider**: Manages the global state for the application using Context API.

### Styling

- **App.css**: Contains all the styles for the application.

### Application Layout

The `App` component wraps all other components with the `GlobalProvider` to manage the global state. Each component serves a specific purpose:

- `Header`: Displays the app title.
- `Balance`: Computes and displays the current balance by subtracting expenses from income.
- `IncomeExpenses`: Shows the total income and total expenses separately.
- `TransactionList`: Renders a list of transactions, each with a delete button.
- `AddTransaction`: Form to add new transactions (income or expense).
