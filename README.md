## Movie Sentiment Analysis


A tutorial and kaggle InClass competition to help participants learn and also practice building a sentiment classifier.

* **SF Project Night**: https://www.meetup.com/sfpython/events/234956048/

* **Competition**: https://www.kaggle.com/c/movie-sentiment-analysis

* **Date**: Oct'18th 2017


### Dataset

This dataset of Movie Reviews is from Stanford AI group.  http://ai.stanford.edu/~amaas/data/sentiment/

This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. We provide a set of 25,000 highly polar movie reviews for training, and 25,000 for testing.

#### Publications using the dataset:

Andrew L. Maas, Raymond E. Daly, Peter T. Pham, Dan Huang, Andrew Y. Ng, and Christopher Potts. (2011). [Learning Word Vectors for Sentiment Analysis](http://ai.stanford.edu/~amaas/papers/wvSent_acl2011.pdf). The 49th Annual Meeting of the Association for Computational Linguistics (ACL 2011).

* Benchmark Accuracy for the dataset in 2011 is 88.90%.  Can we get close to that or even beat that?


### Notebooks:

* **00-build-dataset-kaggle.ipynb**:
Steps I took to build the dataset for Kaggle Competition


* **01-count-classifier.ipynb**:
    * Load Data, vectorize reviews to numbers
    * Build a basic model based on counting
    * Evaluate the Model
    * Make a first Kaggle Submission
    * Other forms of Vectorizations - TF-IDF


* **02-sklearn-models-model.ipynb**:
    * Build a more roubust model using - Logistic Regression, Trees, Naive Bayes are more..
    * Build an Emsemble Model
    * Make a updated Submission


* **03-neural-nets-model.ipynb**:
    * Using Scikit-Learn Feed Forward Neural Nets
    * Any improvements over what we already have?

* **04-deep-neural-nets.ipynb**:
    * Using Keras or TensorFlow or PyTorch
    * Sequence Embeddings to preserve order of words
    * Any improvement over traditional methods?

* **05-compete.ipynb**:
    * Using any or all of the techniques try to beat the competition :-)


### Next steps:

Can you apply these techniques to other Kaggle Competitions.  Give a lightning talk next time?

### End