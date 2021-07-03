# youtube_coments_sentiment_analysis
A Sentiment analysis model on the video of the first Presidential US Debate

1. First run youtube_comments_extraction to get the .csv file of the respective video
videoId and channelId can be changed respectively and enter the respective auth key from the Youtube Data API: https://developers.google.com/youtube/v3

(If using colab, upload the file onto the google drive and mount it for the file to be read or use 
from google.colab import files to upload the files respectively)

2. The Sentiment Analysis of the Presidential Debate can be found in the .ipynb file

Features such as Vader, TextBlob are used for text extraction and sentiment analysis.

Exploratory Data Anlysis was done for comparing the different methods.

KMeans Clustering of the comments is done and from the nltk libraries Stemmer and WordNetLemamtizer was used for comparison.

Elbow method was used to find the ideal number of k clusters.

Word Clouds were generated as well based on the comments and their respective cluster values.


