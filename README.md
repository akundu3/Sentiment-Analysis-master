# Movie-Reviews-Sentiment-Analysis
Sentiment analysis of movie reviews i.e. if a review is positive or negative.
# Introduction
Automated sentiment analysis of text is used in fields where products and services are reviewed by customers and critics. Thus, sentiment analysis becomes important for businesses to draw a general opinion about their products and services. Our analysis helps concerned organizations to find opinions of people about movies from their reviews, if it is positive or negative.
# Problem
We use machine learning techniques to classify such sentences and try to find answers to the following questions:
1. What machine learning techniques are useful for this purpose? Which one out of them performs the best and which techniques are better than the others?
2. What are some of the advantages and disadvantages of traditional machine learning techniques for sentiment analysis?
3. How difficult the task of extracting sentiment from short comments or sentences can be as compared to the traditional topic based text classification?
# Data
We used the Internet Movies Database (IMBD) movie review dataset. This data consists of unprocessed, unlabeled html files from the IMDb archive of the rec.arts.movies.reviewsnewsgroup, http://reviews.imdb.com/Reviews. In The dataset we have 2000 processed down-cased text files. These files are divided in two categories with respect to their classification as "pos" and "neg", indicating the true classification (sentiment) of the component files. Each line in each text file corresponds to a single sentence, as determined by “Adwait Ratnaparkhi's” sentence boundary detector MXTERMINATOR. We used the first version of the dataset which has 10,000 reviews.

Other Data

We used the AFINN data which is a list of English words rated for valence with an integer between minus five (negative) and plus five (positive). The words have been manually labeled by Finn Årup Nielsen in 2009-2011.
URL of this data is here: http://www2.imm.dtu.dk/pubdb/views/edoc_download.php/6010/zip/imm6010.zip

# Result and Conclusion
We learned that the traditional machine learning classification algorithms do not work very well with sentiment analysis of text as compared to their performance with topic based classification. The three standard techniques performed as follows in terms of accuracy:
1. Naïve Bayes: 61.99%
2. Support Vector Machines: 59.308%
3. Random Forest: 61.78%
4. One-three words ngrams: 75.333%
The proposed solution for feature selection by using n-grams and then classifying by logistic regression performed much better than the traditional approaches.

# References
1. Bo Pang Lee, Lillian Lee and Shivakumar Vaithyanathan. “Thumbs up? Sentiment Classification using Machine Learning Techniques,”	in Proc. EMNLP, Philadelphia, 2002, pp. 79-86.
2. Bo Pang and Lillian Lee. “Seeing Stars: Exploiting Class Relationships For Sentiment Categorization With Respect To Rating Scales” in Proc. ACL, 2005, pp. 115-124.
3. B. Pang and L. Lee. “Opinion Mining and Sentiment Analysis”. Now Publishers Inc, July 2008.
4. Informatics and Mathematical Modelling, Technical University of Denmark. Internet: http://www2.imm.dtu.dk/pubdb/views/publication_details.php?id=6010 
5. Finn Årup Nielsen. “ A New: Evaluation of a word list for sentiment analysis in microblogs", Proc. ESWC Workshop on 'Making Sense of Microposts', 2011 May, 93-98.
6. Bo Pang and Lillian Lee. “Movie Review Data”. Internet: http://www.cs.cornell.edu/people/pabo/movie-review-data/ .
