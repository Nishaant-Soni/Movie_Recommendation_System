# Movie Recommendation System

## Overview

The **Movie Recommendation System** project leverages collaborative filtering techniques using PyTorch to provide personalized movie recommendations to users. By utilizing user interactions and movie metadata, the system predicts user preferences and suggests movies that align with their tastes. This project demonstrates the implementation of Neural Collaborative Filtering (NCF) to generate accurate and relevant movie suggestions.

## Features

- **Data Processing:**
  - **User Data:** Loads and preprocesses user information including demographics.
  - **Movie Data:** Loads and processes movie details such as titles and genres.
  - **Ratings Data:** Incorporates user ratings to understand preferences.
  
- **Modeling:**
  - **Neural Collaborative Filtering (NCF):** Implements an embedding-based neural network to model user-item interactions.
  - **Custom Dataset:** Utilizes PyTorch's `Dataset` and `DataLoader` for efficient data handling.
  
- **Training & Evaluation:**
  - **Training Loop:** Trains the NCF model using Mean Squared Error (MSE) loss and Adam optimizer.
  - **Performance Metrics:** Evaluates the model using Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE).
  
- **Recommendation Engine:**
  - **Personalized Recommendations:** Generates top-N movie recommendations for a specified user based on predicted ratings.

## Installation

### Prerequisites

- **Python 3.7 or higher**
- **pip** package manager
- **PyTorch:** Ensure that PyTorch is installed. Visit [PyTorch Installation](https://pytorch.org/get-started/locally/) for instructions tailored to your system.
