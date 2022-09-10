# Election_Analysis


## Project Overview
A Colorado Board of Elections employee has asked for the following information to complete the audit of a recent congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who recieved votes.
3. Calculate the total number of votes each candidate receieved.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. The voter turnout for each county
7. The percentage of votes from each county out of the total count
8. The county with the highest turnout

This project will use Python to find the information above from a raw CSV file of election results. 

## Resources
Data Source: election_results.csv
Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Election Audit Result
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
-The counties represented were:
  -Arapahoe 
  -Jefferson
  -Denver
-The county results were:
  -Jefferson: received 10.5% of the vote (38,855 votes).
  -Denver: received 82.8% of the vote (306,055 votes).
  -Arapahoe: recieved 6.7% of the vote (24,801 votes).
-The county with the largest turnout was:
  -Denver
- The candidate results were:
  - Charles Casper Stockham: received 23.0% of the vote, (85,213 votes).
  - Diana DeGette: received 73.8% of the vote (272,892 votes).
  - Raymon Anthony Doane: received 3.1% of the vote (11,606).
- The winner of the election was:
  - Diana DeGette, with 73.8% of the vote and 272,892 total votes.

## Election Audit Summary
The election commission may use this script whenever they have a .csv file that collects the candidate name and county of each voter associated with a unique voter ID. The script will determine the number of candidates and number of counties, and will print the total votes/percentage of the total vote for each candidate and county. The script will also print our the winner of the election and the county with the highest turnout.

  -For use in future elections, the script can be modified in the following ways:

    1. Changing the join() function for the "file_to_load" and "file_to_save" variables to reflect the correct file path/csv file. 

    2. Changing the "candidate_name" and "county_name" variables to reference the correct index number according to the csv file. 