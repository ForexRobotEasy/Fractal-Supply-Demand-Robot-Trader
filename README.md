# Fractal Supply Demand Robot Trader

This code is a sample implementation of a robot trader that uses the Fractal Supply Demand strategy. It is intended to be used in the MQL5 trading platform.

## Global Variables

- `RiskPercent`: The risk percentage per trade.
- `StopLossPercent`: The stop loss percentage.
- `TakeProfitPercent`: The take profit percentage.

## OnTick Handler

The `OnTick` function is the entry point for the robot. It is called on every tick of the market. In this function, the code checks if the current price is within a key rotation zone and if so, it executes the trading strategy.

## Check Rotation Zones

The `IsKeyRotationZone` function is responsible for determining if the current price is within a key rotation zone. It should be implemented with the necessary logic to identify these zones. It returns `true` if the price is within a rotation zone and `false` otherwise.

## Execute Strategy

The `ExecuteStrategy` function is responsible for executing the trading strategy. It should include logic to identify supply and demand zones, support and resistance levels, and execute buy/sell orders at discount/premium prices. It should also handle risk management and portfolio trading.

## Initialization

The `OnInit` function is called when the robot is initialized. It should include any necessary initialization code.

## Deinitialization

The `OnDeinit` function is called when the robot is deinitialized. It should include any necessary cleanup code.

**Note:** ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. For detailed reviews and trading results of this product, please visit [here](https://forexroboteasy.com/forex-robot-review/fractal-trader-review-optimizing-forex-with-supply-demand/). To find the official developer of this product, please use MQL5.

Please note that this is a sample code and may need to be customized to fit your specific trading needs.
