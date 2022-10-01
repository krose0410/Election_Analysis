# Election_Analysis
Create an Election Analysis "PyPoll" using Python.
## Project Overview
To provide written analysis of the election audit of a recent local election.
## Summary
The analysis os the election show that:

Using Python and reading in the CSV election data set we determined out of the 369,711 votes some patterns and analysis.

We created a python script and would read and write data, performed calculations on the counts, and used loops and conditional statements to report our analysis.

- There were 369,712 votes cast in the election.
- The three candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- With the candidate results being:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Candidate 3 received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

## Election Results
With the out file located in the resources folder we answer the following points and questions:

- How many votes were cast in this congressional election?
  - Total Votes: 369,711
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  - County Votes:
  - Jefferson: 10.5% (38,855)
  - Denver: 82.8% (306,055)
  - Arapahoe: 6.7% (24,801)
- Which county had the largest number of votes?
  - Denver
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  - Charles Casper Stockham: 23.0% (85,213)
  - Diana DeGette: 73.8% (272,892)
  - Raymon Anthony Doane: 3.1% (11,606)
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  - Winner: Diana DeGette
  - Winning Vote Count: 272,892
  - Winning Percentage: 73.8%
Colorado saw three counties tally up to 369,711 votes. The biggest of the counties with a 82.8% was Denver. We processed the votes for three candidates of Charles, Diana, and Raymon. With 73.8% of the votes towards Diana DeGette, that is 272,892 of the 369,711 total votes.
<img width="367" alt="PyPoll Results" src="https://user-images.githubusercontent.com/109715441/193431510-b5acea19-04c5-4c3e-a792-174fe81b7ca3.png">

## Challange Summary
We helped Seth and Tom submit the election audit results to the election commission.
- The data we need to retrieve.
- Capture and calculate the total number of votes cast through looping.*
- Get a complete list of candidates who received votes.
- Calculate the total number of votes each candidate received.
- Calculate the percentage of votes each candidate won.
- Determine the winner of the election based on popular vote.

This script could be easily modified to run a check for a supermajority, greater than or equal to 66.7% of the votes as the election criteria. A second
way to change the code, with the county data, weights could be assigned to the counties to represent the weights of the electoral college votes. With
these 2 changes to the script, perhaps the election commission would consider a business proposal to make these two adjustments, and the script could 
calculate almost any election.
