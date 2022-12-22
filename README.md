# Election-Results-2
## Project Overview
A Colorado Board of Elections employee gave me the following tasks to complete as part of an election audit of a recent election.

1. Calculate the total number of ballots cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes that each candidate received.
4. Calculate the percentage of votes that each candidate received.
5. Determine the winner of the election based on the popular vote.

## Resources
data source - election_results.csv
Software: Python 3.6.1, Visual Studio Code

## Summary
The analyses of the election show that 369, 711 votes were cast.

The candidates who received votes were
Charles Casper Stockham
Diana DeGette
Raymon Anthony Doane

The election results were (percentage of votes, along with percentage of votes)
Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)

Therefore, based on this data, the winner was as follows:
Winner: Diana DeGette
Winning Vote Count: 272,892
Winning Percentage: 73.8%

## Challenge Overview
The election commission for this election has requested some additional data from this set of data to complete the audit.  This includes the following:
1. The voter turn-out for each county.
2. The percentage of votes from each county out of the total count
3. The county with the highest turnout

## Challenge Summary
To achieve these results, additional variables and for loops were added to the existing code.  These included one loop to iterate through the spread sheet to find the name of each county, another loop to count the number of votes per county as the other county iterated through the list, and finally a decision statement to to determine which county had the highest turnout.

These results were then published on a line in the command terminal of the code as well as written to a separate text file.
