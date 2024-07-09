# WatchWise-Collaborative-Filtering
This project implements a movie recommendation system using collaborative filtering techniques. Collaborative filtering is a method for making automatic predictions (filtering) about the interests of a user by collecting preferences or taste information from many users (collaborating).

The system is implemented using PyTorch, leveraging embeddings to represent users and movies and training a neural network to predict movie ratings based on these embeddings.

# Training
The model is trained using stochastic gradient descent (SGD) with the Adam optimizer. Training parameters such as learning rate, batch size, and number of epochs can be adjusted in the train.py script.
