# Keltner-Channels-ATRs-and-EMAs

Keltner Channels with EMAs
This chart study in TradingView plots Keltner Channels with Exponential Moving Averages (EMAs) to help with technical analysis and identify potential buy and sell signals based on the price action relative to the Keltner Channels and EMAs.

Inputs
The following inputs are configurable when adding this study to a chart in TradingView:

Keltner Channel Length (default: 20) - the length of the Keltner Channels.
Keltner Channel Multiplier (default: 2.0) - the multiplier used to calculate the upper and lower Keltner Channel bands.
EMA Length 1 (default: 9) - the length of the first EMA.
EMA Length 2 (default: 14) - the length of the second EMA.
EMA Length 3 (default: 21) - the length of the third EMA.
EMA Length 4 (default: 50) - the length of the fourth EMA.
EMA Length 5 (default: 100) - the length of the fifth EMA.
How it Works
The script first calculates the upper, middle, and lower Keltner Channel bands using the ema() and stdev() functions based on the input values for length and mult. It then calculates five EMAs using the ema() function based on the input values for emaLength1 through emaLength5.

In addition to the EMAs, the script also calculates a slower EMA with a length of 22, which is used to calculate the average true range (ATR) bands. The ATR bands are then plotted as atrPlus1 through atrPlus3 for the upper bands and atrMinus1 through atrMinus3 for the lower bands.

The script uses the plot() function to display the Keltner Channels, EMAs, slow EMA, and ATR bands in different colors and line widths.

Usage
To use this chart study in TradingView, simply copy and paste the code into a new Pine script, or import it from the TradingView Public Library. You can then add the study to any chart and configure the inputs as desired.

Conclusion
The Keltner Channels with EMAs chart study in TradingView can be a useful tool for technical analysis and identifying potential buy and sell signals based on the price action relative to the Keltner Channels and EMAs. With configurable inputs and customizable display options, this study can be tailored to suit a variety of trading styles and strategies.
