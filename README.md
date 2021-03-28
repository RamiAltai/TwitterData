# COVID-19 UAE Twitter Data
 
This repository includes UAE Covid-19 data collected on an hourly basis. The languages targeted in our analysis, so far, are Arabic and English. We categorize Tweets based on language into two folders. These are: arTweets and enTweets. Inside each folder, hourly data is organized into files formatted using comma delimited format (i.e., *.CSV) with the following naming convention: year-month--hour --> [YYYY-MM-DD--HH.csv]. Each file contains the following columns:
* NO.: Developer-defined serial number.
* Tweet Text: COVID-19, UAE-specific Twitter chatter data filtered from URLs, Hashtags, and Emojis 
* Tweet ID: Twitter unique Tweet ID
* Date: Tweet’s date
* Likes: Number of likes received for the specific Tweet
* Retweets: number of times the Tweet got retweeted
* Place: includes the full geotag provided by Twitter in JSON format. 

Spatiotemporal Analytics conducted on the data is available on: [UAE-SentiMeter](https://www.adu.ac.ae/UAE-Sentimeter)

All personal identifiable information have been removed as per Twitter's Developer [Agreement and Policy](https://developer.twitter.com/en/developer-terms/agreement-and-policy)

The data is released for non-commercial research use.

## Data Organization

The repository is organized as follows:
* The "arTweets" and "enTweets" directories include the CSV files of the Arabic and English tweets respectively.
* In each directory a set of CSV files can be found, and the files are named using the following conversion [YYYY-MM-DD--HH.csv]

## Data Availability

The Arabic data is available since 10/Oct/2020, and the English data is available since 11/Oct/2020. 

## Statistics 

Number of English Tweets : **171,873**
Number of Arabic Tweets : **363,214**

## Key words 

The key words used to filter tweets
Arabic : وباء , جائحة , كورونا , تعقيم , حجر , ووهان 
English : corona, coronavirus, COVID, Covid, Corona

## Inquiries

Please read through the README and the closed issues to see if your question has already been addressed first. 

If you have technical questions about the data collection, please contact Rami Altai at **1071991[at]students[dot]adu[dot]ac[dot]ae**.

If you have any further questions about this dataset please contact Dr. Heba Ismail at **Heba[dot]Ismail[at]adu[dot]ac[dot]ae**.
