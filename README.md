# Night Swimmer

Night Swimmer is an advanced night scalping system developed by the Forex Robot Easy team. It is designed to trade during specific night trading hours and aims to profit from the mean reversion of prices.

## Product Description

Night Swimmer is a fully automated trading system that executes trades based on the mean price of a financial instrument during night trading hours. The system opens either sell or buy trades depending on the current price relative to the calculated mean price. It employs risk management features to limit losses and optimize profits.

The key features of Night Swimmer include:

- Night trading hours: The system only trades during specific night trading hours when market conditions are suitable for mean reversion strategies.
- Mean price calculation: Night Swimmer calculates the mean price of the financial instrument to determine trade entry points.
- Risk management: The system implements risk management features, including a maximum number of trades to open, take profit, and stop loss levels.
- Trade management: Night Swimmer tracks and manages all opened trades, closing underperforming trades to limit losses.
- Code optimization: The system incorporates code optimization techniques to ensure efficient and reliable performance.
- User-friendly interface: Night Swimmer provides a user-friendly interface for easy setup and configuration.
- Thorough documentation: The system includes comprehensive documentation to guide users in understanding and utilizing its features effectively.

Please note that Forex Robot Easy is not the official developer of Night Swimmer. We provide this sample code to demonstrate how the system can work based on the information available on the developer's site. For detailed reviews and trading results of Night Swimmer, please visit the official developer's site at [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/night-swimmer-ea-review-advanced-night-scalping-system/).

## Code Explanation

The provided code represents a simplified implementation of the Night Swimmer system. Here is a brief explanation of the code structure and key functions:

- Necessary libraries: The code includes the required libraries for trading and managing arrays.
- Constant variables: Constant variables are defined for take profit, stop loss, lot size, and maximum number of trades.
- Variables: Variables are declared for tracking the total number of trades and storing trade information in an array.
- Entry function (OnTick): This function is called on each tick and checks if there are maximum trades open and if it is within night trading hours. It calculates the mean price and opens a sell or buy trade based on the current price relative to the mean price.
- Night trading hours check (IsNightTradingHours): This function should be implemented to check if it is within the desired night trading hours.
- Mean price calculation (CalculateMeanPrice): This function should be implemented to calculate the mean price of the financial instrument.
- Closing underperforming trades (CloseUnderperformingTrades): This function iterates through the trades array and closes underperforming trades. It also removes the trade from the array and adjusts the total trades count.
- Underperforming trade check (IsUnderperforming): This function should be implemented to check if a trade is underperforming and returns true or false accordingly.
- Trade closing (CloseTrade): This function should be implemented to close a trade with the specified ticket.
- Other functions: The code includes placeholder functions for code optimization, user interface, risk management, documentation, code testing, gathering feedback, and code delivery.

The OnStart function calls the necessary functions in the desired order to manage trades, optimize code, provide user-friendly interface, implement risk management, provide documentation, test code, gather feedback, and deliver the completed code.

Please note that the code provided here is a simplified representation for demonstration purposes. The actual Night Swimmer system may have additional features and complexities implemented by the official developer. To find the official developer of Night Swimmer, please use MQL5.
