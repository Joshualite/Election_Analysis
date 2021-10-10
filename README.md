# Election_Analysis

## Overview of Project

For this project we were given a database with information about the voting carried out in the state of Colorado, with which we must deliver a summary to know who won the elections among all the participants. the main objectives were the following:

- The total number of votes cast
- A complete list of candidates who received votes
- The percentage of votes each candidate won
- The total number of votes each candidate won
- The winner of the election based on popular vote

## Resources
- Data source: election_results.csv
- Software: Python 3.7.0 , Visual Studio Code


## Summary
**(To be able to analyze the code with which the project was carried out, you have to open the file "Pypoll.py")**

After performing the analysis of the database, the results to be shown are the following:

- The total vote count was 369,711
- The candidates who participated in the elections were:
    - Charles Casper Stockham 
    - Diana DeGette  
    - Raymon Anthony Doane

- The result of the voting was as follows:
   - Charles Casper Stockham  obtained  23.0% resulting in a number of votes  of 85,213
   - Diana DeGette  obtained 73.8% resulting in a number of votes of 272,892
   - Raymon Anthony Doane obtained 3.1% resulting in a number of votes of 11,606

- The winner of the election was:
  - Diana DeGette won the elections with a  73.8%  of the votes , resulting in an amount of  272,892 votes


## Challenge Overview
After finishing the main analysis, it was propouse the idea of giving a more complete summary of the database that was given to us . Now what needed to be added to the report were the following objectives:
- How many counties participated in the election?
- Which county was the most participatory?

## Challenge Summary
**(To be able to analyze the code with which the challenge was carried out, you have to open the file "PyPoll_Challenge.py" and if yoy want to see the summary in a text file you can do it by opening "election_analysis.txt" at the "Analysis" folder)**

The analysis of the challenge showed the following:

The counties who participated in the election were:
- Jefferson
- Denver
- Araphoe


The result of the vote count by county was as follows:
- Jefferson county obtained a total percentage of 10.5% with a vote share of 38,855
- Denver county obtained a total percentage of 82.8% with a vote share of 306,055
- Araphoe county obtained a total percentage of 6.% with a vote share of 24,801


The county with the highest participation in the elections was:
- Denver county had the highest participation with a total percentage of 82.8%, showing up in an amount of 306,055 votes.

### The summary of the proyect
 
![image](https://user-images.githubusercontent.com/66183125/136711733-121c0692-d4e8-4da7-9207-3a61a92014e5.png)


## Election-Audit Summary:
As we can see, the code used for this project works successfully, so it could be used on a larger scale and would also serve to provide more information.

If we were provided with a file with election information for all the states in Amercia, we could use the same code, with the difference that we would have to update the lists and dictionaries from counties to states. In the case that the databases did not have the same order of columns since the files will present a greater amount of information with a greater number of columns, the only thing that will have to be done is to update the column from which the data is extracted. This code works and can be applied in different areas with its due modifications depending on the objective you want to reach.



