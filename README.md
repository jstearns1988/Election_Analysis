# Election Analysis
## Overview of Election Audit
A Colorado board of Elections employee gave me the following tasks to complete the election audit of a recent local congressional election

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote
6. Calculate the voter turnout for each county
7. Calculate the percentage of votes from each county out of the total count
8. Determine the couny with the highest turnout

## Resources
- Data Source: election_results.csv
- Software: Python 3.7, Visual Studio Code, 1.66.2

## Election Audit Reults
#### Screenshots of results printed to the election_results.txt provided below for easy viewing

### There were 369,711 votes cast in the election.

![Election Results](https://github.com/jstearns1988/Election_Analysis/blob/main/Resources/Election%20Results2.png)


#### The total number and percentage of votes cast in each county:
  - Jefferson: 38,855 (10.5%)
  - Denver: 306,055 (82.8%)
  - Arapahoe: 24,801 (6.7%)

![County Results](https://github.com/jstearns1988/Election_Analysis/blob/main/Resources/County%20Results.png)
  
### Denver County had the largest number of votes

![Denver County](https://github.com/jstearns1988/Election_Analysis/blob/main/Resources/Largest%20County%20Turnout.png)

#### The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane

#### The candidate results were:
  - Charles Casper Stockham received 23.0% of the votes, totalling 11,606 votes
  - Diana DeGette received 73.8% of the votes, totalling 272,.892 votes
  -  Raymon Anthony Doane received 3.1% of the votes, totalling 11,606 votes

![Candidate Results](https://github.com/jstearns1988/Election_Analysis/blob/main/Resources/Candidate%20Results.png)

### The winner of the election was Candidate Diana DeGette, who received 73.8% of the vote, totalling 272,892 votes

![Winner](https://github.com/jstearns1988/Election_Analysis/blob/main/Resources/Election%20Winner.png)

 

## Election Audit Summary
The script used to complete this election audit is very versitile and efficient! It can be edited to be used in smaller city elections, or larger federal elections. For smaller elections, instead of analyzing counties, we could change the code to determine election results from different neighborhoods in one city. For federal elections, the counties could be ammended to represent states. 

This code could also be used with different types of election data. If provided voter demographics, such as age and income, we could analyze the success of candidates within more specific populations. This could be useful for campaigns to find their voters and areas of opportunity in the future!

We could also adjust the script to calculate how well each candidate performed in the specified territorial regions, i.e. counties, neighborhoods, or states. This would present a picture of who is more popular in different areas. I believe this to be especially useful in determining target areas for better campaigning for a successful run in the future. With just a few tweaks, the code has near endless possibilities.

The provided code below shows where simple edits can be made based on unique data provided for many different kinds of elections!
![Example Code](https://github.com/jstearns1988/Election_Analysis/blob/main/Code%20Example.png)


