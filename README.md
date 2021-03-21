# Election_Anaylsis

## Project Overview
A colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calcuate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of vites each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Overview of Election Audit:
The purpose of this election audit analysis was to go through a large data set that included the Ballot ID, County, and Candidate and count the total number of votes for each candidate and county, calculate the percentage of total votes, and finally conclude a winner of the election. This was completed by using Visual Studio to code the program in Python. 

## Election-Audit Results:
![Terminal](resources/Terminal_results.JPG) ![Text File](resources/txt_results.png) 
The analysis of the election show that:
- There were 369,711 votes cast in the election
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The County total votes received were:
    - Jefferson received 10.5% of the votes with 38,855 votes.
    - Denver received 82.8% of the votes with 306,055 votes.
    - Arapahoe received 6.7% of the votes with 24,801 votes.
- The largest County turnout was:
    - Denver with a total of 306,055 votes. 
- The candidates results were:
    - Charles Casper Stockham received 23.0% of the vote with 85,213 votes.
    - Diana DeGette received 73.8% of the vote with 272,892 votes.
    - Raymon Anthony Doane received 3.1% of the vote with 11,606 votes.
- The winner of the election was:
    - Diana DeGette, who received 73.8% of the vote with 272,892 votes.
    
## Challenge Summary
This script can be used for larger data sets with more candidates as the script is not defined to a certain number of candidates. In the case where a certain candidate that represents a particular party, we would have to adjust the script to display the party each candidate represents whether it be included in the same data set or from an external source. Another modification would be if there are several candidates running for multiple roles, we would have to modifiy the script to caputure the position of each candidate and compare their voting numbers to each candidate running for the same position. All these modifications allow this script to be versatile based on the elections on hand.
