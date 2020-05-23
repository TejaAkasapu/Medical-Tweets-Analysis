# Social Media Mining for Health Monitoring

Identifying and extracting ADRs from tweet if they exists and map to MedDRA ID. Also perform the same analysis on live tweets.


## Data Set

We took dataset from #SMM4H 2020 event.

## Pre-processing
Our preprocessing includes 
* Conversion of smilies to text    :-) => happy
* Conversion of general terms    em=> them 
* Removing hashtags   #trend => trend
* Removing punctuation
* Lemmatization using wordnet
* Word Tokenization
* Remove URLs present in the tweets
* Convert to Lowercase


