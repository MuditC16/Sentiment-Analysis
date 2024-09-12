# Sentiment Analysis

This project performs sentiment analysis on the IMDB movie reviews dataset using a neural network model built with Keras and TensorFlow. The dataset contains positive and negative movie reviews, and the project aims to classify them.

## Project Structure

- `sentiment_analysis.py`: Main script for data preprocessing, model building, and training.
- `IMDB Dataset.csv`: The dataset containing movie reviews and their sentiments.
### Note 
As the dataset is big, I am sharing the link to access the dataset - https://www.kaggle.com/datasets/vishakhdapat/imdb-movie-reviews

## Running the Project
1. Ensure the IMDB Dataset.csv file is in the project directory.
2. Run sentiment_analysis.py to preprocess the data and train the model.
3. The results will include sentiment classification for movie reviews.

## Libraries Used
Pandas
NumPy
Seaborn
NLTK
TensorFlow/Keras
scikit-learn

## Model Details
Model Type: Sequential neural network (Conv1D + LSTM)
Loss Function: Binary Crossentropy
Optimizer: Adam

## Requirements

To install the dependencies, run:

```bash
pip install -r requirements.txt
