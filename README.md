# Spotify-genre-classifier

CLASSIFYING SONG GENRES FROM AUDIO DATA.

# Spotify Song Genre Classification

This project uses PCA, decision tree, and logistic regression algorithms to classify and predict Spotify song genres within a dataset.

## Dataset

The dataset used in this project is the Spotify Song Attributes dataset from Kaggle. It contains over 232,000 songs with 16 features such as danceability, energy, key, loudness, mode, speechiness, acousticness, instrumentalness, liveness, valence, tempo, duration_ms, time_signature, chorus_hit, sections, and target (the genre of the song).

## Preprocessing

Before applying the classification algorithms to the dataset, we first preprocess the data by scaling the features using StandardScaler and reducing the dimensionality of the data using PCA.

## Classification

We then apply decision tree and logistic regression algorithms to classify the songs into their respective genres. We use cross-validation to evaluate the performance of each algorithm.

## Results

Our results show that logistic regression outperforms decision tree in terms of accuracy and F1 score. We also find that certain features such as danceability and energy are more important than others in predicting song genres.

## Conclusion

In conclusion, this project demonstrates how PCA and classification algorithms can be used to predict Spotify song genres with high accuracy. The code for this project can be found in this repository.

