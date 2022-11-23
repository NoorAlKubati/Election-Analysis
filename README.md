# Election-Analysis
## Overview of Election Audit
Primarily, this analysis aimed to check the voter turnout for each county, the percentage of votes from each county out of the total count, and the county with the highest turnout. This was mainly the soul purpose of this election audit.
## Election-Audit Results
### How many votes were cast in this congressional election?
The votes were 369,711 in total.
### Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct?
The percentage of total votes for each county is:

Jefferson: 10.5% (38,855).

Denever: 82.8% (306,055).

Arapahoe: 6.7% (24,801).
### Which county had the largest number of votes? 
Denever had the highest and the largest number of votes. 
### Provide a breakdown of the number of votes and the percentage of the total votes each candidate received?

Charles Casper Stockham: 23.0% (85,213).

Diana DeGette: 73.8% (272,892).

Raymon Anthony Doane: 3.1% (11,606).
### Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
Diana DeGette won the clection  with 272,892 of votes count with 73.8% of total votes. 
## Election-Audit Summary
The code used for this audit job could potentially be utilized in other elections as well. However, in order to ensure that it works properly, the data feeded into the path need to be saved into a CSV and name should be provided (see the code snippet below).
```
# Add a variable to load a file from a path.
file_to_load = os.path.join("Resources", "file_name.csv")
```

Additionally, this project dealt with candidates and counties, we could also add city as another variable to study. In so doing, we will have to replicate the same code that was used for either the candidates or counties (see code below).
```
# 1: Create a county list and county votes dictionary.
city_list=[]
city_votes={}

# 2: Track the largest county and county voter turnout.
winning_city = ""
winning_city_count = 0
winning_city_percentage = 0
```
After that. all is needed is to read the data and filter it by city and print the output... :wink:	
