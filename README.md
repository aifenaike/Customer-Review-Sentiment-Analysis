# Customer-Review-Sentiment-Analysis
 A sentiment analysis model for product reviews by customers.

## Review Dataset
Our dataset consists of reviews written by customers for various food products. The reviews, originally given on a 5 point scale, have been adjusted to a +1 or -1 scale, representing a positive or negative review, respectively. Here are two examples from the dataset:

Review 1 – Label **-1 (Negative sentiment)**

**Nasty No flavor. The candy is just red, No flavor. Just plan and chewy. I would never buy them again**

Review 2 – Label **1 (Positive sentiment)**

**YUMMY! You would never guess that they’re sugar-free and it’s so great that you can eat 1 them pretty much guilt free! i was so impressed that i’ve ordered some for myself (w dark chocolate) to take to the office. These are just EXCELLENT**


## Requirements
There are some general library requirements for the project and some which are specific to individual methods. The general requirements are as follows.

- numpy
- scikit-learn
- nltk

The library requirements specific to some methods are:

- Pytorch 

Note: It is recommended to use Anaconda distribution of Python.

## Information about  files

- data/reviews_train.tsv: Train set of reviews
- data/reviews_val.tsv: validation set of reviews
- data/reviews_test.tsv: test set of reviews

