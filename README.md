# Wrangle-and-Analyze-Data
This repo contains files that show the different steps in data wrangling - gathering, assessment and cleaning. The use case is to wrangle data for WeRateDogs twitter account.
After wrangling, the data is analyzed to generate insights regards what type of dog breeds attract the most engagement on social media platforms like Twitter.

## Data Gathering
The data used is gathered from three different sources - 
* The `twitter_master_archive.csv` dataset that contains most of the data needed for analysis. This was provided for manual download in the Udacity classroom.
* The `images_prediction.tsv` dataset contains predictions of the dog breed from the images provided in the tweets.
* The last dataset used which contains the retweet and favorite counts for each tweet was gathered by querying Twitter's API directly'
<br>
Libraries such as `requests`, `tweepy` and `json` were used during the data gathering phase. 
The codes used in wrangling and analyzing the data are contained in the `wrangle_act.ipynb` notebook. Steps taken to wrangle the data and a report of nsights gotten from
the analysis are contained in the `wrangle_report.ipynb` and `act_report.ipynb` notebooks respectively.
