# Timeframe Separator

This code is a script for the MetaTrader 5 platform that creates vertical lines on the chart to separate different timeframes. It is a simple tool that helps traders visually identify the boundaries of each timeframe.

## How it Works

1. The script calculates the starting time for each timeframe: H1, H4, D1, W1, and MN1.
2. It then draws a vertical line at each calculated time using the `DrawVerticalLine` function.
3. The `DrawVerticalLine` function creates a new line object with the specified label and time coordinates.
4. The line properties such as color, width, and style are set using the `CChartObjectLine` class.
5. The line object is added to the chart using `ChartObjectsRedraw` function.

## Product Description

**Timeframe Separator** is a simple script for MetaTrader 5 that helps traders visually separate different timeframes on the chart. It draws vertical lines at the beginning of each timeframe: H1, H4, D1, W1, and MN1.

This tool is especially useful for traders who analyze multiple timeframes simultaneously. By clearly marking the boundaries of each timeframe, it becomes easier to identify key levels, trends, and patterns.

**Features:**
- Automatically calculates the starting time for each timeframe.
- Draws vertical lines with customizable properties such as color and width.
- Works on any currency pair and timeframe.

**Disclaimer:** ForexRobotEasy is not the official developer of this product. We only provide this sample code that can work as described in the product. For detailed reviews and trading results of this product, please visit the official developer's website at [forexroboteasy.com/forex-robot-review/timeframe-separator-unbiased-review-real-results/](https://forexroboteasy.com/forex-robot-review/timeframe-separator-unbiased-review-real-results/). To find the official developer of this product, please refer to the MQL5 platform.
