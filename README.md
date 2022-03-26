# Election_Analysis
## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. The total number of votes cast
2. A complete list of candidates who received votes
3. The percentage of votes each candidate won
4. The total number of votes each candidate won
5. The winner of the election by popular vote.

The election commision requested some additional data to complete the audit:
    6. The voter turnout for each county
    7. The percentage of votes from each county out of the total count
    8. The county with the highest turnout


## Resources
- Data Source: elections_results.csv
- -Softare: Python 3.10.3, Visual Studio Code, 1.65.2

## Summary
The analysis of the election shows that:
-There were 369,711 votes cast in the election.
-The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
   - Charles Casper Stockham received 23.0% of the votesand 85,213 votes.
   - Diana DeGette received 73.8% of the votes and 272,892 votes.
   - Raymon Anthony Doane received 3.1% of the votes and 11,606 votes.
-The winner of the election was:
  Diana DeGette who received 73.8% of the votes and 272,892 votes.
  
  ## Challenge Overview
 
  The additional data provides more depth to the analysis.
    - Jefferson had 10.5% of the vote with 38,855 total votes
    - Denver had 82.8% of the vote with 306,055 total votes
    - Arapahoe had 6.7% of the vote with 24,801 total votes
    
  Denver had the highest voter turnout of the three counties. 
  
  The final Terminal readout looked like this:
  
  ![Terminal_readout](https://user-images.githubusercontent.com/100727593/160220604-cec02979-31a3-4e47-91cf-689279283e5d.png)

  
   ## Challenge Summary
   The election committee could use this script in another election as long as the provided csv files was formatted in a similar structure and simple adjustments could be made for where to pull the data from (instead of county in column [1] and candidate in column [2]. With edits to where the file paths are.  
   This script could be modified to provide a further breakdown of percentage of votes for each candidate within each county. If more data was provided (postal code) this could provide detailed analysis. Both could assist, along with more data on demographics, in finding voting patterns among age ranges and location. 
