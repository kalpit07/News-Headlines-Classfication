# News-Headlines-Classfication

News-Headlines-Classification classifies the *News Headlines* into 4 different news categories using ***Naive Bayes Algorithm***.

**News Categories :**
1. Business
1. Entertainment
1. Health
1. Science & Technology

You can download the dataset from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/News+Aggregator).

In this [UCI](https://archive.ics.uci.edu/ml/index.php) Dataset, The unnecessary columns have been removed and a *.csv* file has been uploaded to this project with two columns :

- TITLE
- CATEGORY



### News Headlines Pre-Processing
Text is pre-processed effectively where the unstructured text data is initially obtained, which mostly is the combination of both garbage and useful data. The text data is made free from all noisy and useless information, which include punctuation marks, semicolons, irrelevant texts, quotes, exclamation marks, dates etc.

##### Pre-Processing Steps :
1. Headlines Tokenization
1. Diacritics/Punctuations Removal
1. Stop words Removal from News Headlines

        a. Removal on basis of concepts
    
        b. Removal from existing list (545 stop words)
    
        c. Removal on basis of word frequency
1. Words Stemming

        a. S-Stemmer
    
        b. Lovins Stemmer (1st Stemmer, suffix removal)
    
        c. Porter Stemmer (The Most Appropriate Stemmer)
    
        d. Paice/Husk Stemmer (Iteration-Based Algorithm, 5 Parts)
