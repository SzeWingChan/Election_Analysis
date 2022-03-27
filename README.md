# Election Analysis

## Overview of Election Audit
An audition of a recent local congressional election was conducted using the data provided by a Colorado Board of Election employee.  The outcome of the election including the total number of votes cast, vote cast and respective percentage of votes in each county, list of candidates, the total number of votes each candidate received, the percentage of votes each candidate won and the winner of the election based on the popular vote are presented in the election_results (text) file.

## Resources
- Data Source: election_results.csv
- Software: Python 3.10.2, Visual Studio Code 1.65.2

## Election-Audit Results
- There were 369,711 votes cast in the election.
  
  ![Total_votes](https://github.com/SzeWingChan/Election_Analysis/blob/main/Resources/Total_votes.png)

- Breakdown of the number of votes and the percentage of total votes for each county in the precinct:
  - The number of votes for Jefferson county is 38,855 and it accounts for 10.5% of the total votes.
  - The number of votes for Denver county is 306,055 and it accounts for 82.8% of the total votes.
  - The number of votes for Arapahoe county is 24,801 and it accounts for 6.7% of the total votes.
  ![County_votes](https://github.com/SzeWingChan/Election_Analysis/blob/main/Resources/County_votes.png)

- Denver county had the largest number of votes.
  
  ![Largest_county_turnout](https://github.com/SzeWingChan/Election_Analysis/blob/main/Resources/Largest_county_turnout.png)

- Breakdown of the number of votes and the percentage of the total votes each candidate received:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
  - Diana DeGette received 73.8% of the vote and 272892 votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,666 votes.
  
    ![Candidates_votecount](https://github.com/SzeWingChan/Election_Analysis/blob/main/Resources/Candidates_votecount.png)

 -  Diana DeGette, who received 73.8% of the vote and 272892 votes, won the election.

## Election-Audit Summary
- The audit script can be reused in other elections, for example, federal elections, with some level of adaptations or modifications.  
  - Instead of calculating the number of votes in each county, the script could be changed to calculate the number of votes in each electoral district.  
  - The number of votes for each candidate won could be modified to calculate the number of votes each party won.
