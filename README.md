## Information
1. Data is pre-processed using pandas, gensim and numpy libraries
2. Input data: text_emotion.csv and splitted into train and test set 
3. Collected from crowdflower website
4. Step by step works done in here: https://github.com/Jakaria08/emotion-analysis/blob/master/IOT_PROJECT.ipynb
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
![6](https://user-images.githubusercontent.com/7825643/39469519-dce32516-4cf5-11e8-93f4-6418107d2f07.png)
