# SpamClassification
A Machine Learning model to classify spam vs real news

The goal of this model is to read in news articles and blog posts to label it as spam or not spam. This model could be useful for social media sites to filter news to keep people well informed.

The dataset:
[Fake and real news dataset] has ~18,000 observations with 4 columns.

[Fake and real news dataset]: https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset

Some content in the Jupyter notebook:
* Features selection and reasoning

* Several baseline models were compared based on accuracy scores. In the end, the LightGBM model was chosen to tune its hyperparameters to best fit this problem.

* A discussion on feature importances and precision scores.

