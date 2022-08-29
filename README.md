# Election-Analysis-PyPoll

## Overview of Project
The purpose of the project is to assist Colorado Board of Elections in analyzing the election results and complete the election audit of a local congressional election involving three counties. Analysis includes
  * Calculating total number of votes
  * Calculating total votes cast for each county and percentage
  * Calculating the county with highest turnout
  * Calculating total votes cast for each candidate and percentage
  * Determine the winner of the election

 ## Election-Audit Results
 
 ![Election_Analysis_Challange_Terminal](https://user-images.githubusercontent.com/76926148/187254230-23d231a3-7eb6-443d-a021-d77e0390cd7e.PNG)
 
 * How many votes were cast in this congressional election?
    The total number of votes in this election WAS 369,711.
     -------------------------
     Total Votes: 369,711
     -------------------------

 * Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
    - County Votes:
        * Jefferson county has 10.5% total percentage with 38,855 votes
        * Denver county has 82.8% total percentage with 306,055 votes
        * Arapahoe county has 6.7% total percentage with 24,801 votes
  
 * Which county had the largest number of votes?
    Denver had the highest number of votes with total of 306,055.

 * Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
    - Candidate votes
        * Charles Casper Stockham has 23.0% total percentage with 85,213 votes
        * Diana DeGette has 73.8% total percentage with 272,892 votes
        * Raymon Anthony Doane has 3.1% total percentage with 11,606 votes

 * Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
    Diane DeGette won the election with total percantage of 73.8% and 272,892 total votes

 ## Election Audit Summary
    The python script designed for this project determines the winner, votes counts and percantages for each candiadate and county. While this python script satisfies     the current requirement for this election,  with few modifications this script can be used for any election.

    * Possible modifications:
       1. The current script identifies the candidate name and county columns with coumn index hardcoded in th script which can be a problem if the data      changes.Conditions can be applied to determine the columns and related data.

       2.Similarly, the location of the CSV file is hardcoded for accessing the data which can be a problem if the location changes! Interactive user input elements can be included for the user to specify the path to the file instead of hardcoding it.
       
       
