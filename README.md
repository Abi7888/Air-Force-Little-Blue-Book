# README.Rmd
December 26, 2015  

Introduction and explanation of the paper...

The contents of this repository include:

1. 19XXr.txt files - These text files are the Air Force "Little Blue Book" documents for the four available years (1983, 1997, 2012, & 2015). An online version of the most recent (2015) document can be found [here](http://www.e-publishing.af.mil/shared/media/document/AFD-150826-047.pdf). 
2. Basic Stuff XXXX.R files - These scripts import the Air Force Blue Book text document of interest and assesses the commonality of the key words "you" and "our". The final output provides the keyword count and the ratio of keywords to total word count for these specific keywords along with the top 10 most common words in this document.
3. XXXX Detail.R - These script import the Air Force Little Blue Book text document of interest and pre-processes the text into a corpus for n-gram analysis. The script then identifies the 1-4 grams in the document and then visualizes the most frequent n-grams.
4. Euclidean Distance.R - This script plots for comparison the use of the directive term "you" versus the inclusive term "our" across the four Air Force Little Blue Book documents.
5. Polarity Assessment XXXX.R files - These scripts import the Air Force Little Blue Book text document of interest and pre-processes the text for sentiment analysis. We use the `sentiment` package which allows us to classify the polarity (e.g. positive or negative) of a set of texts using a naive Bayes classifier trained on Janyce Wiebe's subjectivity lexicon. The positive vs negative word list used in this process can be viewed at sentiment/data/subjectivity.csv



