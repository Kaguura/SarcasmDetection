# SarcasmDetection
This research group project was completed in partial fulfilment of the requirements for the CMPE257 Machine Learning course at the San Jose State University and under the careful supervision of Dr. Mahima Agumbe Suresh.<br />

Natural Language Processing (NLP) is a common theme in research and applications nowadays. Chatbots, voice assistants, product recommender systems based on opinion mining - all these require computers to understand human language. A sarcastic sentence means the opposite of its literal meaning. Even for humans, it is hard sometimes to recognize sarcasm if the context is not provided.  That is why sarcasm detection remains a challenge in NLP.<br />

Sarcasm detection is a binary classification problem. The labeled datasets available to researchers allow Linear Model classification algorithms to be used. The most popular algorithm, among those who chose Machine Learning over Rule-Based approach, is Support Vector Machines (SVM). Logistic Regression and Naive Bayes are the next most popular classifiers, followed by Decision Tree algorithm. Researchers compare the performance of different classifiers and combine them together to achieve a better sarcasm detection score. Most of the existing works from 2010 till 2016 concentrate on datasets from Amazon and/or Twitter. For example, Sulis et al use a dataset of 12,532 tweets. Buschmeier et al use a dataset of 1,254 Amazon reviews. Those datasets look meager comparing to sarcasm database made available in 2017 that contains 1.3 million labeled sarcastic statements.<br />

We investigated various methods to detect sarcasm in sentences, using both traditional machine learning (SVMs and Logistic Regressors on discrete features). In our project, we intend to use relatively new database acquired from Reddit. As per our knowledge, not much research has been done on this data. The database creators have only tried Logistic Regression for sarcasm detection. We, in turn, plan to try Ensemble methods such as Random Forest and Bootstrap Aggregation applied on SVM and Logistic Regression classifiers. The results is evaluated with precision and recall metrics along with accuracy to get a better understanding of the performance of our approach.


## Installation and Running
Download the [DataSet](https://www.kaggle.com/danofer/sarcasm#train-balanced-sarcasm.csv) and save as train-balanced-sarcasm.csv and upload it to jupyter notebook in the same directory Sarcasm_Detection.ipynb


## Disclaimer
The main purpose of this project is not to produce an optimal solution for Sarcasm Detection. However, it is fast enough for most purposes. The dataset that we have chosen for this project, Reddit, is relatively new dataset as comparision to amazon, twitter, kaggle etc. The database creators have only tried Logistic Regression for sarcasm detection. Besides, We have tried Ensemble methods such as Random Forest and Bootstrap Aggregation applied on SVM and Logistic Regression classifiers. The results has been evaluated with precision and recall metrics along with accuracy to draw some useful conclusions about sarcasm detection. Although the code has been tested using various testcases, we cannot guarantee that the code is bugfree. So, use the code on your own responsibility.

## References

@unpublished{SARC,
  authors={Mikhail Khodak and Nikunj Saunshi and Kiran Vodrahalli},
  title={A Large Self-Annotated Corpus for Sarcasm},
  url={https://arxiv.org/abs/1704.05579},
  year=2017
}
https://www.kaggle.com/danofer/sarcasm#train-balanced-sarcasm.csv
