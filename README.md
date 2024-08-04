Introduction : 

This project implements a movie recommender system using Autoencoders. The core idea is to learn a compressed representation (latent space) of user-movie interactions, which can be used to predict user preferences for unseen movies.

Autoencoder Architecture

An Autoencoder is a neural network architecture composed of two main components:

    Encoder: Maps input data (user-movie ratings matrix) to a lower-dimensional latent space representation.
    Decoder: Reconstructs the original input data from the latent space representation.

