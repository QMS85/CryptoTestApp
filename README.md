# Crypto Tracker Pro

This Crypto Tracker Pro App Allows You To Buy & Sell Crypto:
Bitcoin, Ethereum & Dogecoin


**Key HTML, CSS & JavaScript Code Components, Transaction system & Key features Explained:**

1. **HTML Structure:**
- Header: Shows app title and user balance
- Dashboard: Two-column layout
  - Left: Market prices display
  - Right: Portfolio and transaction interface
- Transaction form: Dropdown and input for trading

2. **CSS Styling:**
- Dark theme for better readability
- Responsive grid layout
- Clean card-based design for data presentation
- Interactive button states
- Consistent spacing and typography

3. **JavaScript Features:**
- **Mock Data:**
  - `cryptoData`: Simulates real cryptocurrency prices
  - `user`: Tracks user's balance and portfolio
- **Core Functions:**
  - `init()`: Initializes the application
  - `renderMarketData()`: Displays current crypto prices
  - `executeTransaction()`: Handles buy/sell logic
  - `updatePortfolioDisplay()`: Shows current holdings
  - `updateBalanceDisplay()`: Updates available funds

4. **Transaction System:**
- Buy: Converts USD to cryptocurrency
- Sell: Converts cryptocurrency back to USD
- Validation: Checks sufficient funds/holdings
- Real-time updates: Immediately reflects changes

5. **Key Features:**
- Real-time balance updates
- Portfolio tracking
- Simple buy/sell interface
- Input validation
- Holdings calculation
- Clean user interface

**How to Use Crypto Tracker Pro:**
1. Select cryptocurrency from dropdown
2. Enter USD amount
3. Click Buy/Sell
4. Watch portfolio and balance update


This implementation provides a foundation for a cryptocurrency investment platform. In a real-world scenario, you'd need to connect to actual cryptocurrency APIs for price data and implement proper security measures for financial transactions.
