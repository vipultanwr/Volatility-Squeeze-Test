
***********************************The Volatility Squeeze*********************************
__________________________________________________________________________________________

__________________________________________________________________________________________



The main code is an .ipynb extension Jupyter notebook which has been developed and tested in macOS environement using python 3


_______________________________DEPENDENCIES INFORMATION___________________________________

Following are the python libraries it is dependent upon:

os
pandas
numpy
matplotlib
prettytable
________________________________PARAMETERS INFORMATION____________________________________


Boolean variables:

RUN_ON_TRAIN_DATA--If True, it will take data files from data/train location for backtest
CONSIDER_ONLY_CLOSE -- If false, all the MA, bollinger band crossovers will be considered using high and low prices. Example: Sell when HIGH < MA etc. 

Following variables mean the same as the instructions pdf file given with problem statement. 

MA_LENGTH       
ST_DEV 
SQUEEZE_LOOK_BACK 
SQUEEZE_MEMORY 
ATR_LENGTH
ATR_STOP 


RISK_FREE_RATE --Average risk free rate considered for Sharpe Ratio calculation 
TRANSACTION_COST  -- Transaction cost in actual fractions (not bps or percentages)



_________________________________________HOW TO RUN_______________________________________

First cell consists of all the parameters and after that there are cells for function declarations. At the end of the notebook, last cell runs the backtest. After the code successfully runs, we can see a prettyTable with strategy performance data and an equity curve starting with 100 Rs of initial capital.



_____________________________________________END_________________________________________






