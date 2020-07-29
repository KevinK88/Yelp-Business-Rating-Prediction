# Overview 
- The goal of this project was to predict business’ star ratings based on the given customer business reviews in the Yelp dataset. The reviews were converted to a TF-IDF Matrix which was then given to a neural network.
- Used different structures of neural networks such as activation functions, and optimizers to discover a model that best predicts the star ratings of the businesses.

# Methodology:
- Created a dataframe from the JSON file, review.json, containing all the reviews and their associated business ids.
- Created a TF_IDF vectorizer from the reviews and converted this into a dataframe
- A maximum document frequency of 95% was used to eliminate stop words
- Created different neural network models with different layers and early stopping for training.

# Result:
- RMSE for each model

[![Screen-Shot-2020-07-28-at-7-34-04-PM.png](https://i.postimg.cc/cLr1sKq1/Screen-Shot-2020-07-28-at-7-34-04-PM.png)](https://postimg.cc/NKvvDjfZ)

