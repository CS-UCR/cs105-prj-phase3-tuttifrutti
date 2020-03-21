## Name: Steven Joseph SID: 862083506 <br>
## Name: Rahul Nair  SID:  862050219<br>
## Name: Christian Solorio  SID: 861313460  <br>

# Project Phase 3 <br>
  For phase 3 we followed up on our phase 2 this time analyzing the data. First we analyzed our nba data by performing clustering linear regrssion then we used this data to try and find patterns related to the twitter data.<br>
  
  ## NBA Players and Stats <br>
https://www.basketball-reference.com/leagues/ <br>
We will be adding this dataset, more specifically the sets from advanced statistics (https://www.basketball-reference.com/leagues/NBA_2020_advanced.html) as it allows us to check statistical measurements of a players performance. These measurements are known as BPM (Box Plus/Minus, VORP (Value over Replacement Player) among others. Like the other data we have, cleaning and EDA will be performed on it. <br>

## team Contributions <br>
### Name: Steven Joseph <br>
Participated in the identfying of sources to scrape or retrieve data from, as well as helped with data cleaning and checking for details of scraped data, and performing EDA on some of said data, and focus mainly on the scoring, age, and percieved ability of the players through these focus.
### Name: Rahul Nair<br>
For phase 1, used the twitter API to scrape data for the 450 players in the NBA in 2019. For the 350 players with active twitter accounts, recorded, their number of followers, statuses, and other twitter info. In phase 2, I merged the dataset scraped by Christian for 2019 player stats with the 2019 twitter data I got to make a cohesive dataframe, and removed outliers that skewed data. Also did basic comparisons on player statistics vs twitter for EDA to get a general idea of the data. In phase 3,first found the player statistic with the greatest correlation to follower counts by calculating the Pearson coefficient for each. Then used kfold algorithm to increase the usage of limited test data for twitter data. Finally used the new test data to perform linear regression to determine follower counts for players based on a player’s stats.

### Name: Christian Solorio<br>
For phase 1, used scrapy to get nba data from basketball-reference.com. This data spanned from 1995 - 2020. For phase 2 I combined this data into one file, cleaned the data, and then performed EDA on it to see patterns in the data, specifically key columns such as OBPM (offensive box plus/minus), DBPM (defensive box plus/minus), and BPM (box plus/minus). This data is best for analyzing a player's performance. For phase 3 I used this data alongside the twitter data to see which indicator (bpm, true shot %, etc.) was a better indicator of a player's popularity. For example, I could use DBPM to test how defensive players stack up against offensive players with high OBPM. This way we could see if there was any correlation between players playing style and their popularity. I used clustering to compare different columns alongside twitter data and make predictions from it.
The files I worked on for the project are nbaref file, where I use scrapy to get data. See file ESPN.py under spiders.
Then the other file I worked on was the Phase3_Scrape.ipynb file in the front page.
