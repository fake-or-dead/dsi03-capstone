# Transactions predict for Vending Machine

## Disclaimer
This project for learning data science course, welcome for any suggestion and advice 

## Objective 
Vending Machine need to re-supply each POS when depleted but Warehouse and Logistics process need time to planning route and prepare stock that will leave a gap of availability for sale 

So if we can predict when each POS deplete beforehand for Warehouse planning and Logistics routing team can planning and prepare to re-supply daily or any periods 

## Source of Data and EDA

From Drink Vending Machine Company
Sample transaction logs from 3 different vending machine between `2023-10-01` to `2023-10-31`

## EDA 
Explore all data aspects and split each machine's transaction logs to observe characteristics

## Feature engineering 
add weekday, 
then save to `datasets/compute` folder 

## Model

### Linear regression
you can see more detail at `2.LinearRegression.ipynb`

### ARIMA
you can see more detail at `3.ARIMA.ipynb`
 
### RNN
you can see more detail at `4.RNN.ipynb`
with LSTM model from 2 implementation

## Limitation and Improvement
1. Still use rough indicator (CUPs) instead of in each ingredient details from drinking menus eg. matcha is run out
2. Lack of menu recipe and machine capacity for each ingredients
3. Limit on Time series information to 1 month OCT if we can gather more so we can analysis trends and seasonal 
4. Can add surround  data to add more features eg. Weather, Building populations and characteristics,  
5. Finish this Proof of concept and pack into Application to use internal with MLOps





