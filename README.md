# Election Analysis

## Overview of Election Audit
The purpose of this project was to complete an audit of a recent local Colorado congressional election and generate a vote count report using Python. The tasks included:
1. Calculating the total number of votes cast.
2. Gathering a complete list of candidates who received votes.
3. Calculaing the total number of votes each candidate received.
4. Calculating the percentage of votes each candidate won.
5. Determining the winner of the election based on popular vote. 

### The Data
The results were gathered with three primary voting methods.
  1. **Mail-in ballots**, that are hand-counted at the central office.
  2. **Punch cards**, that are collected and fed into a machine that tabulates votes and then sends the results to the central office.
  3. **DRE** (direct-recording electronic counting) **memory cards**, that are read by a computer, and sent to the central office.

Altogether the votes cast by these methods determined the final election results. After the votes were counted, all results were gathered in this **csv file** - [Election Analysis](https://github.com/morganfredrick/election_analysis/blob/main/PyPoll_Challenge.py). This file contains three columns with the following headers: **Ballot ID** (Column A), **County** (Column B), and **Candidate Name** (Column C).


## Election Audit Results
Below is a visual breakdown of total votes, votes per county, largest county, and candidate vote count with percentages. 

![Election Results](https://github.com/morganfredrick/Election_Analysis/blob/main/Analysis/election_results.PNG.PNG)

The total amount of votes that were cased in the congressional election was 369,711. As you can see, Denver county had the most votes at 82.8%, totaling 306,055. Jefferson came in next at 10.5% of the total votes, whereas Arapahoe only came in at 6.7% of the total votes.

As for the candidates, Diana DeGette received the most votes, at 73.8% of all votes or 272,892 votes. The second place candidate, Charles Casper Stockham, received 23% of the total votes. With the third candidate, Raymon Anthony Doane, only receiving 3.1% of the overall votes. 

## Election Audit Summary
This script can be modified to find the most number of votes for different filters other than candidates and county. If the data included other characteristics, such as demographics and geography, the script can be modified to include these characteristics and the analysis can be broken down even further.

This script can also be modified to determine patterns among the characteristics. We could test the percentage of voters by county against each candidate. This would allow us to see which candidate was the most popular within a county or geographical area. 
