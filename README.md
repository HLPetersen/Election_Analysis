# <b> Election Analysis </b>

## <u>Overview of Election Audit</u>
This is an election audit to analyze the results of a U.S. congressional preceinct election in Colorado. The votes were cast by three methods: mail-in ballots, punch cards, and DRE counting machines. This analysis includes the total votes, voter turnout for each county, percentages of total election votes for each county, the county with the highest voter turnout, the candidates, the percentage of votes each candidate received, the number of votes each candidate received, and the winner of the election.  

## Resources
- Data Source: election_results.csv
- Software: Python, Visual Studio Code   

## Election-Audit Results
The analysis of the election shows that:
- There were 369,711 votes in the election.
- There were three counties that voted in this election:
  - Jefferson
  - Denver
  - Arapahoe
- The county results were:
  - Jefferson County cast 10.5% of the votes which consisted of 38,855 votes.
  - Denver cast 82.8% of the votes which consisted of 306,055 votes.
  - Arapahoe cast 6.7% of the votes which consisted of 24,801 votes. 
- The county that had largest voter turnout was:
  - Denver
- The candidates were:
  - Charles Casper Stockham
  - Diana Degette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
  - Diana Degette received 73.8% of the vote and 272,892 votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.
- The winner of the election was:
  -Diana Degette who received 73.8% of the vote which was 272,892 votes.
 <img width="234" alt="Capture" src="https://user-images.githubusercontent.com/116980760/203691318-4552c2e1-5077-4596-9050-3328d3d4910b.PNG">

## Election Audit Summary
This script can be used, with some modification, for any election. Counties can be changed to any subset of the voter turnout, such as state or providence if it is a larger election, by replacing county by the new subset that is wanted. The script counts the occurances of the county so any subset would work the same way. Also, the script can be altered to display the percentage of registered voters that participated in the election by comparing the total votes to the total number of registered voters in the election boundaries. 
