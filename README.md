# Tracking Vote-by-Mail Ballot Status

*Oct. 13, 2020*

Inspired by random tweets and news reports describing ballots as being "rejected" in North Carolina, this is [R code inside a markdown document](https://github.com/carolinadatadesk/nc_absentee_2020/blob/main/nc_abst_ballot_status_2020.Rmd) that generates csv files in an attempt to better show how vote-by-mail ballots move through the system. With these csv files, you can see more easily that "spoiled" ballots doesn't mean what it means in common usage. 

"Spoiled" ballots are not permanent rejections of a voter's attempt to vote. Instead, as you can see in these csv files, about a third of voters that "spoil" their ballots have already been able to submit a successfully "accepted" ballot. On average, it takes about 12 days for a voter who "spoils" their ballot to have a fresh ballot "accepted."

Each csv file has one row for each voter and with columns that show the dates of various ballot statuses for that voter. This differs from the original source data, which may have several rows for each voter -- one row for each new ballot status. The rows in the source data are ballot statuses. The rows in these csv files are voters.

For the most part, ballots have just one date -- accepted -- but some are "spoiled" or have "witness info incomplete" and are later accepted.

The repository has two csv files:
* [ncid_status_tracker201013.csv](https://github.com/carolinadatadesk/nc_absentee_2020/blob/main/ncid_status_tracker201013.csv) -- 21 MB file with one row for each unique voter. It contains no demographic information, only "ncid" and "voter_reg_num". You can get the full demographics of each voter by joining it back to the original source data or making some slight modifications to the code.
* [witness_accepted201013.csv](https://github.com/carolinadatadesk/nc_absentee_2020/blob/main/witness_accepted201013.csv) -- 9 KB file that shows the elapsed number of days between the day a voter's ballot status is "witness info incomplete" and when it is "accepted". This is only 169 voters.

## FAQ

### What are some reasons ballots could get spoiled?
TK

### What do the different ballot statuses mean?
TK

