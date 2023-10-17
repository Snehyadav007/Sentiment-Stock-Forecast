# Sentiment-Stock-Forecast


# Stock Price Movement Prediction Using Random Forest and Headlines

![Random Forest](https://img.shields.io/badge/Random%20Forest-1.0-brightgreen.svg)
![Python](https://img.shields.io/badge/Python-3.7%2B-blue.svg)

## Introduction

This repository contains a Python script for predicting stock price movement based on historical news headlines. The code uses a Random Forest Classifier and a Bag of Words (BOW) approach for text analysis.

## Prerequisites

Before you begin, make sure you have the following installed:

- Python (version 3.7 or higher)
- Jupyter Notebook (recommended for an interactive development environment)
- Necessary Python libraries such as pandas, sklearn, and numpy. You can install them using `pip`.

## Data

The code reads historical news headlines and stock price data from a CSV file named `Data.csv`. Ensure the dataset is properly structured with columns for dates, headlines, and labels for stock price movement.

## Data Preprocessing

- The code preprocesses the data by filtering it for the training and test periods.
- It removes punctuations and converts text to lowercase for ease of analysis.
- Text data is organized into a Bag of Words (BOW) representation.

## Bag of Words

The Bag of Words (BOW) approach is implemented using the `CountVectorizer` from scikit-learn. It converts the text data into numerical vectors suitable for machine learning.

## Random Forest Classifier

A Random Forest Classifier is used to predict stock price movement. It's trained on the BOW representation of news headlines.

## Evaluation

The code evaluates the model's performance using confusion matrices, accuracy, and classification reports.

## Contributing

Contributions are welcome! If you find any issues, have feature requests, or want to improve the project, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

Feel free to use, modify, and share this code for stock price movement prediction using a Random Forest Classifier and news headlines. If you have any questions or need further assistance, please don't hesitate to reach out.
