# Tracking Vote-by-Mail Ballot Status

*Oct. 13, 2020*
Inspired by random tweets and news reports describing ballots as being "rejected" in North Carolina, this is R code inside a markdown document that generates csv files in an attempt to better show how vote-by-mail ballots move through the system. With these csv files, you can see more easily that "spoiled" ballots doesn't mean what it means in common usage. 

"Spoiled" ballots are not permnanent rejections of a voter's attempt to vote. Instead, as you can see in these csv files, about a third of voters that "spoil" their ballots have already been able to submit a succesfully "accepted" ballot. On average, it takes about 12 days for a voter who "spoils" their ballot to have a fresh ballot "accepted."

Each csv file has one row for each voter and with columns that show the dates of various ballot statuses for that voter. This differs from the original source data, which may have several rows for each voter -- one row for each new ballot status. The rows in the source data are ballot statuses. The rows in these csv files are voters.

For the most part, ballots have just one date -- accepted -- bu some are "spoiled" or have "witness info incomplete" and are later accepted.

## FAQ

### What are some reasons ballots could get spoiled?
TK

### What do the different ballot statuses mean?
TK

