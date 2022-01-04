# Twitter user report

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1zTEQUdC5gWU8osT17VQ3hw9jSJsJQHI7?usp=sharing)


## Objective
The purpose of the project is to provide a quick overview about the activity and the engagement related to a twitter profile. The account analyzed is related to the italian politician Matteo Salvini because his profile is placed among the most active Twitter profiles in Italy.

Here's the pipeline

## Pipeline

![pipeline](https://user-images.githubusercontent.com/60407477/147119638-33dcc4df-cc99-40ae-96c7-5acd4c1fd95c.PNG)

## Methods Used

* Scraping: gather tweets with the library Twint. This library allows to collect almost the entire activity of a user without limitations
* Data Profiling: quick transformations (casting and field drop/rename) made with Pandas and PdPipe
* Data Visualization: made with Plotly and obtained the following plots:
  * Tables exposing:
      * All the collected tweets
      * Top 5 retweeted posts
      * Top 5 replied posts
      * Top 5 liked posts
  * Engagement overview over the time
      * Number of tweets progression
      * Number of likes progression
      * Numbers of retweets progression
      * Number of replies progression
  * Waffle chart to show the overall activity on weekday and month 
* Data Consumption: static report made with Datapane

## Libraries

|Name     | Link   | 
|---------|-----------------|
| Twint | https://github.com/twintproject/twint|
| pdPipe | https://pdpipe.github.io/pdpipe/|
| pysqldf | https://pypi.org/project/pysqldf/ |
| Seaborn | https://seaborn.pydata.org/|
| Ploltly | https://plotly.com/ |
| Datapane | https://datapane.com/ |

## Results
### DataPane
https://datapane.com/u/airaghidavide/reports/M7bQbw3/twitter-profile-report-matteo-salvini/
