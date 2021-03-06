# Election-Results

## Election Audit Overview
In this project a Colorado Baord of Elections employee has requested that the following taskes be completed to audit a recent local congressional election:

1. Total number of votes cast
2. A complete list of candidates who received votes
3. Total number of votes each candidate received
4. Percentage of votes each candidate won
5. The winner of the election based on popular vote
6. The voter turnout for each county
7. The percentage of votes from each county out of the total count
8. The county with the highest turnout

## Resources
* Data Source: election_results.csv
* Software: Python 3.7.6, Visual Studio Code, 1.51.1

## Election Audit Results 
The analysis of the election showed that:

* There were 369,711 votes cast in th election*
*The Candidates were:
  * Charles Casper Stockham
  * Diana DeGette
  * Raymon Anthony Doane 

* The results for each Candidate are as follows:
  * Charles Casper Stockham recieved 23.0% of the total vote or 85,213 votes
  * Diana DeGette recieved 73.8% of the total vote or 272,892 votes
  * Raymon Anthony Doane recieved 3.1% of the total vote or 11,606 votes
  
* The winner of the election was:
  * **Diana DeGette who received 73.8% of the vote (272,892 votes)**
  
* The vote count and percentage of the vote for each county in the election:
  * Denver: 82.8% (306,055)
  * Jefferson: 10.5% (38,855)
  * Arapahoe: 6.7% (24,801)

* County with the highest voter turnout:
  * **Denver County with 306,055 votes**

* Summary from Command Line is below:
![](https://github.com/AsaHolley/Election-Results-/blob/main/PyPoll%20Challenge/Python%20Terminal%20for%20Election%20Audit.png)


## Election Audit Summary
The Colorado election commission should be able to use this script for future elections with only limited changes necessary to make usable in a varity of situations.  First and foremost the  file path must be changed to the resource used for each new election. To do that the file_to_load variable should be updated from file_to_load = os.path.join("Resources", "election_results.csv") to the folder name location on the user machine the election data is located (replacing “Resources”) and name on the new election data (replacing “election_results.csv”). Another modification that commission could make to use this this data in the future is add another script to add the congressional districts and the voter turnout in those districts. To add congressional districts the same style of variables would need to be added to the scripts using the same structure of loops and if statements that was used for candidates and counties. The resource used would also need to include congressional district so that the script could pull this variable from the appreciate row. 
