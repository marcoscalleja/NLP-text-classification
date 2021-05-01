# NLP-text-classification
“AG News” dataset is a collection of news articles categorized into
four classes: Science (id 0), Sports (id 1), World (id 2), and Business (id 3).

Each news article in the collection is categorized into one of the four classes. The data has a “text”
column that has the textual content, and additional columns indicating the label. Like in the movie
1
reviews, column “label” and “label_int” indicate the label of the article, now using a numbering
from 0 to 3 in “label_int”. Additionally, you can view that each article is labeled with four binary
labels, one per category: the “science_int”, “sports_int”, “world_int” and “business_int” columns
have a binary value indicating if the article is of the corresponding category (value 1) or not (value
0).

The training set has 109,999 examples, and the test set has 10,000 examples. The datasets are
balanced, meaning that each category is represented in roughly 25% of the examples.

This dataset is from the “AG News” collection: http://www.di.unipi.it/~gulli/AG_corpus_of_news_articles.html
. The exact choice of 4 categories for comparing text classification methods was proposed in
the following paper: “Character-level Convolutional Networks for Text Classification”, by
Zhang, Zhao and LeCun (https://arxiv.org/abs/1509.01626). We took the dataset from Kaggle
(https://www.kaggle.com/amananandrai/ag-news-classification-dataset).
