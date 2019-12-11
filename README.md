# CSCI5802_DataScienceTeam

The objective of this project is to develop a recommendation system for movies.The Kaggle competition and the datasets that we are working on can be found here : https://www.kaggle.com/prajitdatta/movielens-100k-dataset. The data set consists of 100,000 ratings (1 - 5) from 943 unique users on 1682 movies. Each user has rated at least 20 movies. Our dataset is divided into training and testing set. The training set has 90,570 ratings and the testing set has 9,430 ratings (10 ratings for each of the 943 unique users). We first train our model on the training set and then use the testing set to test its accuracy. Then, for each user we output the top n movies recommended by our model.


References -
https://medium.com/@contactsunny/label-encoder-vs-one-hot-encoder-in-machine-learning-3fc273365621
https://medium.com/@m_n_malaeb/recall-and-precision-at-k-for-recommender-systems-618483226c54
https://surprise.readthedocs.io/en/latest/FAQ.html#how-to-compute-precision-k-and-recall-k
