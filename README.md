# Current Price Indicator

This code is a custom indicator for the MQL5 platform that displays the current spread of a currency pair. It also includes options to customize the font size and name, as well as the ability to hide the pipette symbol.

## Global Variables
- `font_size`: The size of the font used for the indicator label.
- `font_name`: The name of the font used for the indicator label.
- `hide_pipette`: A boolean variable that determines whether the pipette symbol is hidden or not.

## Custom Indicator Initialization Function
The `OnInit()` function is called when the indicator is initialized. It sets up the indicator buffer and creates the indicator label on the chart.

## Custom Indicator Deinitialization Function
The `OnDeinit()` function is called when the indicator is removed from the chart. It removes the indicator label from the chart.

## Custom Indicator Calculation Function
The `OnCalculate()` function is called every time a new tick is received. It calculates the current spread of the currency pair and updates the indicator value and label text accordingly.

## Product Description
The Current Price Indicator is a custom indicator for the MQL5 platform that displays the current spread of a currency pair on the chart. It provides real-time information about the difference between the bid and ask prices, allowing traders to quickly assess the liquidity and cost of trading a particular currency pair.

This indicator is highly customizable, allowing users to adjust the font size and name according to their preferences. It also includes an option to hide the pipette symbol, giving traders a cleaner and more focused view of the spread information.

Please note that ForexRobotEasy is not the official developer of this product. We are only showcasing a sample code that can work as described in this product. To find the official developer of this product, please refer to the MQL5 platform.

For detailed reviews and trading results of this product, please visit [here](https://forexroboteasy.com/forex-robot-review/current-price-forex-software-detailed-review-real-results/).
