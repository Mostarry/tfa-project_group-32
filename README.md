# Tools For Analytics Final Project
This project is intended to practice basic data analytics using the 311 calls dataset in 2020 published by NYC. 

## Group name & section
Group 32 

Section 002

## Group Member & UNI
Motong Yu (uni: my2687)

Jiaxin Li (uni: jl5747)

## File Description
There are three files included in this repository:

1. README.md file contains info about the group as well as generally descirbes what we have done for the whole project.

2. Top10.ipynb file which shows what the top 10 causes of calls to 311 are in zip code 10019. For each of the top 10 causes, calculate the total number of incidents in 2020. The output is a serie called "top10" with top 10 causes and keys and corresponding amounts as values. 

3. Parking.ipynb file which analyzes whether illegal parking incidents are a larger fraction of total 311 incidents in the zip code 10019 than they are across all zip codes. The output is a boolean named "higher_parking_proportion" which return True if it is the cause and return false elsewise. 

## Variable Description
In Top 10.ipynb:
1. variable "df" is the dataframe converted from csv using pandas
2. variable "chosenzip" contains all dataframe where zip code is 10019
3. variable "top10" is pandas.Series. Its keys are the top 10 causes of calls to 311 are in 10019. Its values are the total incidents of each of these 10 types


In Parking.ipynb:
1. variable "df" is the dataframe converted from csv using pandas
2. variable "chosenzip" contains all dataframe where zip code is 10019
3. variable "zipparking" is the number of parking incidents in zip code 10019
4. variable "zipall" is the number of all incidents in zip code 10019
5. variable "zipparkingfraction" is the ratio of parking incidents compared to all incidents in zip code 10019 
6. variable "allparking" is the number of parking incidents of all zip code
7. variable "generalall" is the number of all incidents across all zip code
8. variable "allparkingfraction" is the ratio of parking incidents compared to all incidents acorss all zip code
9. variable "higher_parking_proportion" is the ratio that compare if parking incidents in zip code 10019 contains a higher proportion of parking incidents than the global value