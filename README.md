# Advanced CCI by Ioannis Xenos

![Advanced CCI](https://forexroboteasy.com/wp-content/uploads/2021/01/advanced-cci-by-xenos-ultimate-forex-bot-review.jpg)

This is a customizable Forex trading strategy that uses the Commodity Channel Index (CCI) indicator to determine overbought and oversold conditions in the market. The strategy opens buy trades when the CCI value is below -100 (oversold) and sell trades when the CCI value is above 100 (overbought).

## Features

- Customizable CCI period and parameters
- Adjustable lot size, stop loss, and take profit levels
- Account protection to prevent excessive drawdowns

## How it works

1. The program includes the necessary libraries and APIs for trading and using the CCI indicator.
2. Global variables are defined, including the moving average filter period, lot size, stop loss level, take profit level, maximum allowed drawdown, CCI indicator object, and trade object.
3. The customizable strategy function is defined, which calculates the CCI value for the specified symbol and period.
4. If the CCI value is above 100, a sell trade is opened with the specified lot size, stop loss level, and take profit level.
5. If the CCI value is below -100, a buy trade is opened with the specified parameters.
6. The account protection function calculates the drawdown percentage and checks if it exceeds the maximum allowed drawdown. If it does, all open trades are closed and a warning message is printed.
7. The OnTick event handler is called every tick to execute the trading strategy and account protection functions.
8. The OnInit event handler is called when the program is initialized to create and set up the CCI indicator.
9. The OnDeinit event handler is called when the program is deinitialized to clean up and destroy the CCI indicator.
10. The OnStart function is the program entry point, where event handlers are registered for the OnTick, AccountProtection, and OnDeinit events.

## Product Description

The Advanced CCI by Ioannis Xenos is a powerful and customizable Forex trading robot that utilizes the Commodity Channel Index (CCI) indicator to identify overbought and oversold conditions in the market. It has been developed by the Forex Robot Easy Team and is designed to provide traders with an automated solution for executing profitable trades.

With the Advanced CCI, traders can take advantage of the CCI indicator's ability to identify potential trend reversals and market extremes. The robot opens buy trades when the CCI value is below -100, indicating an oversold condition, and sell trades when the CCI value is above 100, indicating an overbought condition.

The robot offers various customizable parameters, including the CCI period, lot size, stop loss level, take profit level, and maximum allowed drawdown. Traders can adjust these parameters based on their risk tolerance and trading preferences.

Account protection is a key feature of the Advanced CCI robot. It continuously monitors the drawdown percentage and ensures that it does not exceed the maximum allowed drawdown. If the drawdown exceeds the specified limit, all open trades are closed to protect the trader's account.

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that demonstrates how this product can work as described. For detailed reviews and trading results of this product, please refer to the official developer's website: [Advanced CCI by Xenos - Ultimate Forex Bot Review](https://forexroboteasy.com/forex-robot-review/advanced-cci-by-xenos-ultimate-forex-bot-review/).

To find the official developer of this product and access the complete functionality, please visit the MQL5 website.

For any inquiries or support regarding this code, please contact the official developer, Ioannis Xenos, through their website: [forexroboteasy.com](https://forexroboteasy.com/).
