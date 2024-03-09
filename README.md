# Legend Wall Street MT5 ReadMe File

[![Developer's Site](https://forexroboteasy.com/wp-content/uploads/2019/02/cropped-logo-1.png)](https://forexroboteasy.com/)

## Developer Information

- Developer's Site: [forexroboteasy.com](https://forexroboteasy.com)
- Development by: Forex Robot Easy Team

## Code Overview

This code represents the Legend Wall Street MT5 Expert Advisor (EA). The EA is designed to trade in the Forex market using dynamic Fibonacci zones to identify potential market reversals. It includes various features such as setting trading hours, opening and closing positions, managing manual orders, and using the hedge feature for simultaneous buying and selling.

## Input Parameters

- `TradingHours`: Number of hours for the EA to trade (default: 8)
- `StartHour`: Start hour for the EA to trade (default: 0)
- `EndHour`: End hour for the EA to trade (default: 23)
- `MagicNumber`: Unique number for EA's positions (default: 123456)

## Expert Initialization

The `OnInit()` function is responsible for initializing the EA. It checks if the current time is within the specified trading hours and returns an initialization status. If the EA is not allowed to trade during the specified hours, it prints a message and returns `INIT_FAILED`. Otherwise, it initializes other necessary features and indicators and returns `INIT_SUCCEEDED`.

## Expert Tick Function

The `OnTick()` function is called on each tick and contains the main trading logic of the EA. It waits for a confirmation signal from high or low price levels, opens positions based on set parameters, closes positions by take profit or Fibonacci level, manages manual orders if settings allow it, and uses the hedge feature to buy and sell simultaneously. Additionally, it checks if the current time is outside the specified trading hours and closes all positions, providing feedback to the user.

## Custom Functions

The code includes several custom functions to enhance the functionality of the EA. These functions are responsible for identifying potential market reversals using dynamic Fibonacci zones, opening positions based on set parameters, closing positions by Fibonacci level, managing manual orders, and buying and selling simultaneously (hedge feature).

## Custom Indicators

The code includes custom indicators used by the EA. These indicators are responsible for providing confirmation signals from high or low price levels and determining the take profit level.

## Product Description

[Legend Wall Street MT5](https://forexroboteasy.com/forex-robot-review/legend-wall-street-mt5-review-dynamic-fibo-zones-for-market-reversals/) is an expert advisor developed by the Forex Robot Easy Team. It is designed to trade in the Forex market using dynamic Fibonacci zones to identify potential market reversals. The EA includes various features such as setting trading hours, opening and closing positions, managing manual orders, and using the hedge feature for simultaneous buying and selling.

**Please note:** ForexRobotEasy is not the official developer of this product. We only provide a sample code that demonstrates how the Legend Wall Street MT5 EA can work as described. To find the official developer of this product, please use the MQL5 platform.

For detailed reviews and trading results of this product, please visit the [Forex Robot Review](https://forexroboteasy.com/forex-robot-review/legend-wall-street-mt5-review-dynamic-fibo-zones-for-market-reversals/) page on the Forex Robot Easy website.
