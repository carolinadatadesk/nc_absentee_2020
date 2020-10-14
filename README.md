# Tracking Vote-by-Mail Ballot Status

Inspired by random tweets and news reports describing ballots as being "rejected" in North Carolina, this is R code inside a markdown document that generates csv files in an attempt to better show how vote-by-mail ballots move through the system. With these csv files, you can see more easily that "spoiled" ballots doesn't mean what it means in common usage. Instead, as you can see in these csv files, about 20% of voters that "spoil" their ballots have already been able to submit a succesfully "accepted" ballot. (As of October 13.)

Each csv file has one row for each voter and with columns that show the dates of various ballot statuses for that voter. This differs from the original source data, which may have several rows for each voter -- one row for each new ballot status. The rows in the source data are ballot statuses. The rows in these csv files are voters.

For the most part, ballots have just one date -- accepted -- bu some are "spoiled" or have "witness info incomplete" and are later accepted.

## What are some reasons ballots could get spoiled?
TK
