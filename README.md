# Election_Analysis

## Project Overview
A Colorado Board of Elections employee wanted us to make a program that will read a .csv file and output the following:

1. Calculate the total number of votes cast
2. Get a complete list of candidates who recieved votes.
3. Calculate the total number of votes each candidate and county received.
4. Calculate the percentage of votes each candidate won and county votes.
5. Determine the winner of the election based on popular vote.
6. Determine the county with the largest turnout

## Election-Audit Results
The analysis of the election show that:
- Votes Cast:
  - 369,711 votes were cast
- County Votes:
  - Jefferson county had 38,855 votes (10.5%)
  - Denver county had 306,055 votes (82.8%)
  - Arapahoe county had 24,801 votes (6.7%)
- Largest County Turnout-rate:
  - Denver
- Candidate Votes:
  - Charles Casper Stockham had 85,213 votes (23%)
  - Diana DeGette had 272,892 votes (73.8%)
  - Raymon Anthony Doane had 11,606 votes (3.1%)
- Election Winner:
  - Diana DeGette had 272,892 votes (73.8%)

## Election-Audit Summary
With this program, you only need to make a few edits to the code to make this work for any Election! Some examples are
- (![git1](https://user-images.githubusercontent.com/83259639/119295860-73ee4280-bc1d-11eb-90fc-5bfda7f4fc68.PNG)
  - In this block of code, you can change the output to be f"Largest State Turnout: {largest_state}\n" If you want to use it in a Presidential Eleciton, as long as you change the following variables
    - largest_county_winner
    - county_results
    - votes_for_county
    - winning_county
    - county_name
    - largest_county
    - county_vote_percentage
    - county_votes
