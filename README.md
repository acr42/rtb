# Bid optimisation methods for real-time bidding in online display advertising.
-------

## CONTRIBUTERS:

- Alexander Cowen-Rivers ([GitHub](https://github.com/acr42)) 
- Lynray Barends ([GitHub](https://github.com/travelLynz))
- Tim Warr ([GitHub](https://github.com/ghurts))

-------

## Instructions

Pre-processed Dataset

1. Download the files https://drive.google.com/drive/folders/165CDcG3pTd07-XUFon5M2cWS47hvLMnR?usp=sharing
2. You must then create a subfolder Data/. 
3. Split the downloaded data into the subfiles Data/train.csv, Data/validation.csv and Data/test.csv. 

Full Dataset

1. To get the full dataset, download the data dump (6.6 GB zip) from http://data.computational-advertising.org/. 
2. You must then create a subfolder Data/. 
3. In a seperate notebook you will then need to split the downloaded data into a pandas dataframe, with columns for the user profiles, click information and payprices. 
4. Into the subfiles Data/train.csv, Data/validation.csv and Data/test.csv. 

For:
- **Reports** see [GROUP](https://github.com/uclwe/rtb/blob/master/Reports/group_01_report.pdf) / [ACR](https://github.com/uclwe/rtb/blob/master/Reports/acowen-rivers_report.pdf) / [LB](https://github.com/uclwe/rtb/blob/master/Reports/lynray_barends_report.pdf) / [TW](https://github.com/uclwe/rtb/blob/master/Reports/twarr_report.pdf)
- **Data Exploration** see [ACR](https://github.com/uclwe/rtb/blob/master/i-ACR/Individual_Data_Exploration_ACR.ipynb) / [LB](https://github.com/uclwe/rtb/blob/master/i-LB/Individual%20-%20Lynray-DataExploration.ipynb) / [TW](https://github.com/uclwe/rtb/blob/master/i-TW/TW-data-exploration.ipynb)
- **Basic Bidding Strategies** see [this](https://github.com/uclwe/rtb/blob/master/Code/Basic_Bidding_Strategies-Lynray.ipynb)
- **Linear Bidding Strategy** see [this](https://github.com/uclwe/rtb/blob/master/i-TW/LinearStrategy.ipynb)
- **Indiv Bidding Strategies** see [ACR](https://github.com/we/) / [LB](https://github.com/we/tree/master/i-LB) / [TW](https://github.com/uclwe/rtb/tree/master/i-TW)
- **Group Bidding Strategies** see - - - - [NEURAL](https://github.com/uclwe/rtb/blob/master/i-ACR/ACR_BestBiddingStrategy.ipynb) / [MULTI-AGENT](https://github.com/uclwe/rtb/blob/master/i-ACR/Reinforcement_Learning-Agents-ACR.ipynb) (By ACR, located after the single agent experiment)- - 

-------

## Dependencies

- tbc
