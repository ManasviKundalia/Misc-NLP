Author- Manasvi Kundalia

Information about various codes:
All files have been written in Python3 usind open source libraries and packages depending on the task.

1. Web Scraping
The file webscraping.ipynb is an ipython notebook which uses urllib and bs4 to scrape news websites to scrape articles related to specific topics. The link in the code can be changed to scrape different websites for different topics.

Required libraries : urllib, BeautifulSoup (bs4)

2. NLP Tasks

*The files article_classifier_tfidf.ipynb  and pretrain_wordvec_news_classifier.py are  two approaches for multi-class supervised  classification of news articles.

 Required libraries : nltk, gensim, sklearn, pandas

*Machine Translation- I am currently  attempting machine translation (English- Spanish) using two separate word2vec models  for each language. This work is currently   in progress.
 
 Required libraries : python word2vec,pandas

3. Machine Learning

The file loandata_oversampling.ipynb performs classification on the Imperial College London dataset (available on Kaggle). The dataset is highly imbalanced (majority class=90% approx.) and hence I have used various oversampling techniques to resample the data before training. The trained models have been tested on a section of the original imbalanced dataset.

Required Libraries : imblearn, sklearn, pandas, numpy
