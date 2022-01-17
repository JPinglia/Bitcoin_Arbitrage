# Jas's Bitcoin Arbitrage Opportunity Finder
As Bitcoin trades on markets across the globe, we are looking capitalize on simultaneous price dislocations and find opportunities for profits. This program ingests historical data from two exchanges:
  1) Bitstamp
  2) Coinbase

**Data is the analyzed to find price dislocations for bitcoin. The based on opportunities present, a detailed analysis of price dislocations can be conducted. We look at specific data and dates for in-depth profitability analysis.**


## Technologies
The program is written using Jupyter notebooks, for ease of code reading and code execution via code blocks. The program lays out a step-wise reporting and program execution. The code is run in a (Dev) environment with the use of the following libraries:
  1) Pandas
  2) Pathlib
  3) Matplotlib

## Installation Guide
Python 3.7.11 - base installation is required.
PIP install jupyterlab

## Usage
*Assumptions:*

1) Analysis is based on closing price only, we can buy and sell based on the daily open, high and low price to provide a more in depth analysis. 

**The program is built as report. It reports on the arbitrage prospects between Jan-Mar 2018.**

**Single example program results summary:**

*As an example the program intakes date from both the Coinbase and Bitstamp csv datasets. The data is then sorted and overlaid to help determine arbitrage opportunities. 
Here is a overlay of prices over a three month period.* 

![image_1_BTC_Bitstamp_vs_Coinbase](https://user-images.githubusercontent.com/95830866/149705436-79432826-f903-43bb-af4e-c6adbcf150e8.PNG)

we can see price dislocations between the two exchanges. Lets dive deeper into the month of January.
![image_2_BTC_Bitstamp_vs_Coinbase_Jan](https://user-images.githubusercontent.com/95830866/149705571-e4e54494-afef-4b0f-a981-0f257df80a04.PNG)

Lets dive further still to Jan 27 2018 and we find large dislocations between the two said exchanges. 
![image_3_BTC_Bitstamp_vs_Coinbase_Jan_27_2018](https://user-images.githubusercontent.com/95830866/149705652-7bc4645c-63ac-469e-a196-461c5ed99c47.PNG)

A box plot is created to help understand the data set. 
![image_4_BTC_Bitstamp_vs_Coinbase_Early](https://user-images.githubusercontent.com/95830866/149705700-887c9817-c0ed-4120-8605-3e73f6bd5feb.PNG)

Profits for this day during the "Early" period in the data set are considered. 

![image_5_BTC_Bitstamp_vs_Coinbase_Early_profits](https://user-images.githubusercontent.com/95830866/149705758-4b89dca0-ebf4-489c-a357-b398f5a3e999.PNG)

A summary of the cumulative profits is determined. 

![image_6_BTC_Bitstamp_vs_Coinbase_Early_profits_cumulative](https://user-images.githubusercontent.com/95830866/149705810-24ff7710-4cf4-4819-8609-dc858187fed9.PNG)

*The same analysis is completed for a day in the middle (Feb-27-2018) of the data set and a day at the end (Mar-28-2818) of the data set. We attempt to reach conclusion about the data and what arbitrage opportinuites can be found.* 

For this data set, we find there are arbitrage opportunities between the two exchanges. We find high trading profits during the months of January and Febuary with pleaty of positive trade, however in March we see the trading risk rise as the number of successful trade and the profits to be made drop dramatically. 

Please see the Jupyter Notebook for further analysis and outcomes from such an analysis.


## Contributors
This program was developed with base code developed by the Rice-boot-camp. Code was created and added by JPinglia. 

## License

License for this project and associated file is public.
