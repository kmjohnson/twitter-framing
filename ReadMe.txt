This project holds the Congressional Tweets Dataset which consists of the most recent tweets of the 114th U.S. Congress members (both the House of Representatives and Senate). Most of the tweets are from 2015-2016. These tweets have also been updated with the most accurate frames as of July 2017. If a politician is missing from the dataset it's because their tweets were protected and we couldn't pull them or the name files were accidentally overwritten.

The "congressional_tweets_dataset_2017" directory has two subdirectories: "labeled" and "unlabeled". 

The "labeled" directory contains the tweets that are labeled for frame. The format of the CSV files is as follows: 

Tweet ID, Issue, Second Issue (if there are 2 issues covered by the tweet), 1st Frame, 2nd Frame, 3rd Frame, Political Party (1 for Republican & 2 for Democrat), Time Stamp

Cells for second issue and the second and third frames are often empty. 

The issue labels represent the issues the tweet refers to as follows: 

aca -> Affordable Care Act (ACA) or Obamacare
guns -> Gun control or gun violence 
isis -> Terrorism 
lgbt -> LGBTQ 
abort -> Abortion
immig -> Immigration

The "unlabeled" directory contains the tweets that are not labeled. The format for these CSV files is as follows:

Tweet ID, Issue, Second Issue (if present), 4 empty cells, Political Party, Time Stamp


