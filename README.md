# Module 3 Challenge

## Overview of Election Audit

The election commission has requested to complete the audit:

- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the highest turnout

## Election Results

A total of 369,711 voters participated in the congressional elections.

The county with the highest turnout was Denver with 306,055 votes, 82.8% of the total turnout, followed by Jefferson with 38,855 (10.5%) and in last place we have Arapahoe with only 24,801 (6.7%) of the total votes.

![img](https://github.com/CarmenU18/Module-3-Challenge/blob/main/Resources/County%20Votes%25.PNG)

As for the candidates, Diana DeGette won the election with 272,892 votes, representing 73.8% of the total. In second place we have Charles Casper Stockham with 85,213 votes 23.0% of the total and in last place Raymon Anthony Doane with only 11,606 votes, only 3.1% of the total votes.

![img](https://github.com/CarmenU18/Module-3-Challenge/blob/main/Resources/Total%20of%20Votes.PNG)

## Election Audit Summary

This script can be used to obtain the results for any election, just consider:

1. Change the path and the file with the election results.

    file_to_load = os.path.join("Folder_Name", "File_Name.csv")

2. Change the path to save the file.

    file_to_save = os.path.join("Folder_Name", "File_Name.txt")
