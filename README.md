# CHSTA
COVID-19 Hate Speech Twitter Archive (CHSTA)

Repository for Lizhou Fan, Huizi Yu and Zhanyuan Yin for the analysis of anti-Asian Hate Speech on Twitter. "Stigmatization in Social Media: Documenting and Analyzing Hate Speech for COVID-19 on Twitter" ASIST 2020. The paper can be found here (later add link and citation instruction). 

## Data Collection
During the critical period between coronavirus's emergence and ensuing outbreak (January 31, 2020 to April 7, 2020), we've conducted six waves of data collection, each lasting approximately one week. We have queried the Twitter API using the keyword "coronavirus+and+china" and collected 3,482,197 unique tweets across six waves. In accordance with Twitter's [Terms of Service](https://developer.twitter.com/en/developer-terms/agreement-and-policy), we only publically release the tweet ID and the date on which the tweet is created. 

## How to Hydrate
Please refer to the [DocNow Hydrator Github repository](https://github.com/DocNow/hydrator) for instructions on how to obtain the complete information corresponding to each Tweet ID.

## Data Usage Agreement

## Statistics Summary
Number of Tweets : **3,482,197**

Language breakdown of top 10 most prevalent languages : 
| Wave        | Start Date     | End Date       | Total Number of Tweets|
|-------------|----------------|----------------|-----------------------|
| 1           |2020-01-31      |2020-02-07      |445,893                |
| 2           |2020-02-07      |2020-02-17      |297,654                |
| 3           |2020-03-03      |2020-03-12      |422,146                |
| 4           |2020-03-15      |2020-03-22      |1,031,969              |
| 5           |2020-03-22      |2020-03-29      |673,625                |
| 6           |2020-03-31      |2020-04-07      |610,910                |

*** Wave 4 data is split into 4A and 4B due to the complete data file exceeding the maximum data size on Github. 

## Contact
Please contact Lizhou Fan at **lizhou@ucla.edu** if you have any question. 

## Acknowledgement
We thank [UCLA Digital Research Consortium](https://drc.ucla.edu/) for their support in scraping and storing the data. We thank Dave Shepard and Ed Summers for thier inspiring suggestions and resources of the scraping processes.

