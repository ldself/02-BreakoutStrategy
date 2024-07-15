# Breakout Strategy

Python program that creates a simple breakout trading strategy.  Strategy creates a long/short portfolio based on the high and low prices within a specified lookback period.  If a stock closes below (above) the minimum (maxiumum) lookback close, then a long (short) position is taken in the stock.  To prevent signals from occurring too frequently, repeated signals that occur withing a specified period are ignored.  

## Getting Started

The project_2_starter.ipynb notebook was modified in VS Code and uses the Python 3.10.14 library.  A requirements.txt file is included.  Libraries can be installed by installing the contents of this file or by executing the first line of the notebook.
