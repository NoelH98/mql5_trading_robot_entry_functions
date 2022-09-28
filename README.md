# MQL5 Entry Functions.
Useful entry functions for a trding robot in MQL5.

Included Functions:
* Chaikin
* ADX
* iTrix
* Standard Deviation
* CCI
* RVI
* SFI
* Williams
* MACrossover
* DEMA
* BollingerBands
* Momentum
* MACD
* TripleSMA
* PSAR
* VolumeFilter
* TradingRange
* RSI
* ATR
* Stochastic
* Other useful functions such as trailing SL,margin required anong others


## License
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

## Requirements
* MQL5 Trading platform.

## Installation

1: Press the Fork button (top right the page) to save a copy of this project on your account.

2: Download the repository files (project) from the download section or 

clone this project by typing in the bash the following command:

```bash
git clone https://github.com/NoelH98/mql5_trading_robot_entry_functions.git
```
3: Copy the Custom_Functions.mqh file into (/Includes ) folder of your MQL5 MetaEditor.

4: Import the Custom_Functions.mqh file into your script:

  ```
  include <CustomFunctions.mqh>;
  ```
5: Call the function you want to use in your own script:

  ```
  if(checkEntryTripleSMA() == "buy") 'Your buy function'
  if(checkEntryTripleSMA() == "buy") 'Your sell function') 
  ```

