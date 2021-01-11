# Election_Analysis

## Project Overview
A colorado Board of Elections has given us the task of completing the election audit of a recent local congressional election. 
For this we wrote a Python script that delivers the following information when it is ran:

  1. Total number of votes cast.
  2. A complete list of candidates who received votes.
  3. Total number of votes each candidate received.
  4. Percentage of votes each candidate won.
  5.The winner of the election based on popular vote.
  6. Voter turnout for each county.
  7. The percentage of votes from each county out of the total count.
  8. The county with the highest turnout
  
  ## Resources
  - Data Source: election_results.csv
  - Software:  
    - Python 3.9.1. 
    - Visual Studio Code 1.52.1
  
  ## Election-Audit Summary
  According to the analysis of the election: 
  
  - There were 369,711 votes cast in the election.
  
  - The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
    
  - The candidate results were:
    - Charles Casper Stockham: 23.0% (85,213)
    
    - Diana DeGette: 73.8% (272,892)
    
    - Raymon Anthony Doane: 3.1% (11,606)
    
  - The results for coynty turnover were:
    - Jefferson: 10.5% (38,855)
    
    - Denver: 82.8% (306,055)
    
    - Arapahoe: 6.7% (24,801)
    
  - The winner of the election was:
    - Candidate Diana DeGette who received 73.8% of the vote and 272,892 number of votes.
    
  - The county with the largest turnout was:
    - Denver county with a turnout of 82.8% of the votes and 306,055 number of votes.
    
    ## Challenge Overview
      - Business proposal: With the objective to automate processes and reduce costs, we can use this script in order to effectively count how many votes each candidate got during elections and determine who was the winner. Likewise, we can analyse how votes where distributed around counties or states. This script was made for an election in the state of Colorado but it has enless potentianl because we can refactor ir to work at the federal level or in other state, we would only need the corresponding data set. 
      
      - Uses for other elections: As stated above, in order to use this script for other elections we would only need the corresponding data set to the election of choice and corroborate that the .csv file's columns and rows are in the correct order for the code to pick up the values as it iterates through the items. In case you wanted to make a regional analysis of a county you could add another loop to extract where are the votes coming from inside the county, if you have the data available. 
