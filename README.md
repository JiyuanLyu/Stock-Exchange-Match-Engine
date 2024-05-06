# Stock-Exchange-Match-Engine
This project is an exchange matching engine for a stock/commodities market. It matches buy and sell orders based on given conditions and ensures all transactions are processed in a robust and scalable manner.

## Features

- **Symbol Management**: Handles unique symbols representing different stocks or commodities.
- **Account Management**: Manages accounts with unique IDs, balances, and positions. Ensures no account goes into a negative balance.
- **Order Handling**: Processes buy and sell orders, ensuring that transactions respect the financial constraints of accounts and market conditions.
- **Concurrency and Scalability**: Efficiently manages multiple requests simultaneously using multi-threading to ensure scalability.

## Technical Details

- **Programming Languages**: Implement in C++.
- **Concurrency**: Utilizes multi-threading to handle multiple concurrent market transactions.
