# Spotify-Review-Rating-Prediction

This project aims at building an NLP machine that predicts the rating of the Spotify app based on the user reviews. A recurrent neural network will be used. Side information such as the number of upvotes and the time of publication will also be used as features.

This repository consists of three Jupyter Notbooks:

1. spotify_review_simple.ipynb

The recently included TextVectorization layer has been used to build the model, incorporating data preprocessing steps during training time.

2. spotify_review_tfdata.ipynb

Tensorflow Data module was used to allow possible application of Tensorflow dataset pipelines. StaticVocabularyTable was also used to provide greater flexibility in specifying the number of OOV buckets.

3. spotify_review_side_info.ipynb

Side information such as the number of upvotes for each review has been included as a feature to predict user ratings. Functional API was used.

Libraries used in this project:
1. Pandas
2. Numpy
3. Tensorflow
4. Keras
5. NLTK
