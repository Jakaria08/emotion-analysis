1. Data is pre-processed using pandas, gensim and numpy libraries
2. Input data: text_emotion.csv and splitted into train and test set 
3. Collected from crowdflower website
## Preprocessing 

The targed of the following preprocessing is to create a Bag-of-Words representation of the data. The steps will execute as follows:

1. Cleansing
* Remove URLs
* Remove usernames (mentions)
* Remove tweets with *Not Available* text
* Remove special characters
* Remove numbers
2. Text processing
* Tokenize
* Transform to lowercase
* Stem
3. Build word list for Bag-of-Words

## BOW + Naive Bayes classification
