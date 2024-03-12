# Disaster Tweet Detection
#NLP #TextClassification

### Context
According to the United Nations, several hundred natural and man-made disasters occur around the world each year. Disasters can result in loss of life and long-term social 
and environmental consequences, hence the need for efficient disaster response.  

Over the years, social media has proven to be an important channel to access information on disasters and emergencies. AI professionals have explored ways to utilise 
social media, especially twitter, for effective disaster response strategies.  

By utilizing Deep Learning Techniques to classify user-generated data from Twitter, significant information can be obtained to assist emergency responders in creating 
effective relief efforts and aiding victims.  

### Objective
The aim for this project is to compare the performance of the combination of word vectorizers - CountVectorizer and TfidfVectorizer with Naive Bayes over word 
embedding techniques - GloVe and Word2Vec with BiLSTM in classifying disaster tweets as genuine or irrelevant.  

Evaluation metrics such as accuracy, precision, recall and f1-score would be used and the best combination model would be optimized and evaluated.   

### The data 
**id**: Tweet unique identification number  
**keyword**: A disaster-related keyword from the tweet
**location**: The location the tweet was sent from  
**text**: The text of a tweet. Tweets about real disasters and irrelevant information are present in the data.  
**target**: This is a binary label where `1 represents a disaster tweet` and `0 represents a non-disaster tweet`
