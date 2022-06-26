# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local 
congressional elecion.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who recieved votes.
3. Calculate the total number of votes each candidate received.
4. Calcualte the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Determine voter turnout for each county.
7. Calculate the percentage of the vote each county comprises.
8. Determine the couty with the highest turnout.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Results
The analysis of the election show tha:
- There were 369,711 votes cast in the election.
- The  candiates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
    - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The county breakdown of the votes were:
    - Jefferson county turned out 38,855 votes and 10.5% of the total vote.
    - Denver county turned out 306,055 votes and 82.8% of the total vote.
    - Arapahoe county turned out 24,801 votes and 6.7% of the total vote.
- Highest turnout:
    - Denver county had the largest number of votes with 306,055.
- Election Winner
    - Diana DeGette won the election with 272,892 votes and 73.8% of the vote.

## Summary
This script wtih a few modification could be used to audit other elections in the future. One would need
to change the resource folder to include a new set of election data. And update the path to join to the
new file for file_to_load and file_to_save variables. For county_name and candidate_name the row index may
need changed depending on how the data is formatted. For smaller or larger elections the county varirables
could be changed to states or precincts depending on the size, but the base code would be same.




