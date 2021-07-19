# Election_Analysis

## Overview of Election Audit

### Purpose

The client was looking for a Python script that would calculate the winner of a recent election from the .csv file provided. I was able to determine the winner of the election and the number of votes/percentage of total votes each candidate received; as well as a breakdown of election results by county to determine which county had the highest turnout. 

## Election Audit Results

* There were 369,711 total votes cast in the 3 counties (Jefferson, Denver, and Arapahoe)
* Denver County had the highest turnout, with 82.8% of the votes (306055 votes)
* Jefferson County had the second highest turnout with 10.5% of the votes cast (38855 votes)
* Arapahoe County had the smallest turnout, with only 6.7% of the votes (24801 votes)
* Of the candidates, Diana DeGette was the clear winner with 73.8% of the vote, or 272,892 votes
* Charles Casper Stockham was a distant second place with 23% of the vote, or 85,213 votes
* Raymon Anthony Doane had the least votes of all the candidates, only 3.1% of the vote, or 11,606 votes


![image](https://user-images.githubusercontent.com/82191831/126106719-b26bb92b-3236-47c0-bb6e-0ce2a5584b12.png)


## Election Audit Summary

The code used for this election could be used for any election with a similarly formatted source document, minor tweaks can be added to pull data from different columns if necessary by altering these sections:

![image](https://user-images.githubusercontent.com/82191831/126107260-17d95426-654c-4132-b086-10444083cab9.png)

We could also calculate candidate performance by county, this information could be useful for planning strategies for future campaigns. This could be done by using if statements and for loops to determine the percentage of votes for each candidate by county, similar to these:

![image](https://user-images.githubusercontent.com/82191831/126107785-87199466-2bd6-4bf4-9c4b-fa199773871b.png)

![image](https://user-images.githubusercontent.com/82191831/126107860-bbb41817-4dc6-4abb-be1b-7b1b1fa51ec1.png)
