# RSI and TDI Alert Dashboard MT5

This code is a sample implementation of an indicator and dashboard for monitoring RSI (Relative Strength Index) and TDI (Traders Dynamic Index) values across multiple currency pairs and timeframes. It is designed to help professional Forex traders identify potential pullbacks or reversals in the market.

## Features
- Monitors RSI and TDI values for a list of currency pairs and timeframes.
- Allows customization of RSI and TDI threshold levels for identifying potential pullbacks or reversals.
- Provides functions for handling RSI and TDI levels above or below the defined thresholds.
- Can be used as a standalone indicator or integrated into a larger trading system.

## Usage
1. Set the `currencyPairs` variable to specify the list of currency pairs to monitor.
2. Set the `timeframes` variable to specify the list of timeframes to monitor.
3. Set the `rsiThresholds` variable to define the RSI threshold levels for potential pullbacks or reversals. The first value represents the upper threshold, and the second value represents the lower threshold.
4. Set the `tdiThresholds` variable to define the TDI threshold levels for potential pullbacks or reversals. The first value represents the upper threshold, and the second value represents the lower threshold.
5. Implement the necessary code within the `OnCalculate` function to calculate RSI and TDI values for each currency pair and timeframe.
6. Use the provided functions `HandleRSIAboveThreshold`, `HandleRSIBelowThreshold`, `HandleTDIAboveThreshold`, and `HandleTDIBelowThreshold` to handle RSI and TDI levels above or below the defined thresholds.

## Important Note
This code is provided as a sample and is not the official product developed by Forex Robot Easy Team. It serves as an example of how the RSI and TDI Alert Dashboard can be implemented. For detailed reviews and trading results of the official product, please visit [https://forexroboteasy.com/forex-robot-review/review-rsi-and-tdi-alert-dashboard-mt5-a-professional-forex-traders-essential-software/](https://forexroboteasy.com/forex-robot-review/review-rsi-and-tdi-alert-dashboard-mt5-a-professional-forex-traders-essential-software/).

To find the official developer of this product and obtain the official version, please refer to the MQL5 website.

For more information and support, please visit the developer's site: [forexroboteasy.com](forexroboteasy.com)
