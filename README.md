# Sentiment Classification of IMDb Movie Reviews in Keras

## Introduction

This project focuses on sentiment classification of IMDb movie reviews using Keras. The goal is to build a model that can effectively determine the sentiment of movie reviews as either positive or negative.

## Getting Started

To run the notebooks in this project, you can use Google Colab. Make sure to upload the dataset to your Colab session before running the notebooks.

## Project Description

In this project, we employ GloVe 200D word embeddings and utilize WordCloud visualization techniques to gain insights into the data. The model architecture that yielded the best results consists of the following components:

- Embedding Layer
- Bidirectional LSTM layer
- Two Dense layers
- One Dropout Layer

## Results

After extensive hyperparameter tuning and model training, the following accuracy metrics were achieved:

- Training Accuracy: 87.45%
- Validation Accuracy: 85.24%

These results demonstrate the effectiveness of the chosen model architecture in accurately classifying IMDb movie reviews by sentiment.

## Notebook Descriptions

- `Sentiment_Classification_of_IMDb_Movie_Reviews.ipynb`: This notebook features a single Bi-LSTM layer with no Flatten Layer and no Batch Normalization.

- `Sentiment_Classification_of_IMDb_Movie_Reviews_v2.ipynb`: In this notebook, we implement a more complex model with double Bi-LSTM layers, a Flatten Layer, and Batch Normalization with momentum set to 0.9.

- `Sentiment_Classification_of_IMDb_Movie_Reviews_v3.ipynb`: This notebook explores a different approach with double Uni-LSTM layers, a Flatten Layer, and Batch Normalization with momentum set to 0.9.

- `Sentiment_Classification_of_IMDb_Movie_Reviews_v4.ipynb`: Here, we continue to experiment with double Bi-LSTM layers, a Flatten Layer, and Batch Normalization, but this time with momentum set to 0.999.

These notebooks provide detailed insights into the model development process and can serve as valuable references for understanding the project's progression.

---

Feel free to explore the notebooks and adapt the code to your specific needs. If you have any questions or feedback, please don't hesitate to reach out.

**Author:** Mohammad Tanzil Idrisi <br>
**Email:** tanzil.student.mail@gmail.com
