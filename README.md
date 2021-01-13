# Election_Analysis
Module 3 Practice

## Project Overview
A Colorado Board of Elections employee requested an audit of a recent local congressional election.  The analysis required a review of the following:

* Calculation of the total votes cast.
* Breakdown of the number of votes and the percentage of total votes for each county.
* County which had the largest number of votes.
* Breakdown of the number of votes and the percentage of the total votes received by each candidate.
* The winning candidate  including their vote count and their percentage of total votes.

## Resources
* Data Source: election_results.csv
* Software: Python 3.8
* Visual Studio Code 1.52.1

## Election Audit Results
The analysis performed shows that:
* There were 369, 711 votes cast in this congressional election.

* The breakdown of votes and the percentage of total votes for each county in the precinct were:
  * Jefferson 38,855 with votes representing 10.5% of the total votes cast
  * Denver 306,055 with votes representing 82.8% of the total votes cast
  * Arapahoe 24,801 with votes representing 6.7% of the total votes cast
  
* Denver county had the largest number of votes with 306,055 votes representing 82.8% of the total votes.

* The breakdown of votes and the percentage of total votes for each candidate in the precinct were:
  * Charles Casper Stockham with 85,213 votes representing 23.08% of the total votes cast
  * Diana DeGette with 272,892 votes representing 73.8% of the total votes cast
  * Raymon Anthony Doane with 11,606 votes representing 3.1% of the total votes cast
  
* Diane DeGette won the election with 272,892 votes representing 73.8% of the total votes.

 A summary of the above results is contained within the file "election_analysis.txt" which can be found using the following link:
 https://github.com/bedwardssmith/Election_Analysis/tree/main/analysis
 
 ## Election Audit Summary
 The code used in this analysis can be used for any election with minor modification.  
 
 1.  The code could be expanded to include additional jursidictions through the use of an additional dictionary to capture the information and the looping through of the rows to capture the data.
 
 2.  Provided the underlying information is available the code could be expanded upon to include analysis on type of voting; mail in ballots, in person ballots and advance ballots.  Once again this can easily be done through the use of an additional dictionary and the looping through of the rows of data to capture the information.
 
 
 
 
