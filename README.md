# Sentiment Analysis on Amazon Fine Food Reviews

## Introduction
This repository contains code for performing sentiment analysis on the Amazon Fine Food Reviews dataset. The dataset consists of user reviews for various food products on Amazon, and the goal of the analysis is to predict the sentiment (positive or negative) based on the text of the reviews.

## Dataset
The dataset used in this project is the [Amazon Fine Food Reviews](https://www.kaggle.com/snap/amazon-fine-food-reviews) dataset available on Kaggle. To use the dataset, you need to download it from Kaggle and follow the steps provided in the code to set up the environment.

## Setup
To run the code, follow these steps:
1. Install the Kaggle library by running `!pip install -q kaggle`.
2. Upload your Kaggle API key (`kaggle.json`) using the provided upload widget.
3. Make a directory to store the Kaggle API key by running `!mkdir ~/.kaggle` and copy the key using `!cp kaggle.json ~/.kaggle/`.
4. Download the dataset into the Colab environment using the provided Kaggle API command.

## Analysis
The code covers the following steps:
- Data preprocessing: Cleaning and handling missing values.
- Exploratory Data Analysis: Analyzing the distribution of review scores and the number of unique users and products.
- Sentiment Labeling: Converting the review scores into a binary sentiment label (positive or negative).
- Feature Engineering: Using Bag of Words (BoW), TF-IDF, and n-grams for feature representation.
- Model Training: Training a logistic regression model on different feature representations.
- Evaluation: Assessing the model performance using accuracy and ROC-AUC metrics.

## Results
The analysis demonstrates the effectiveness of different feature representations and highlights the improvement in model performance when using n-grams for sentiment analysis.

## Conclusion
This project serves as a foundation for sentiment analysis tasks on textual data and can be extended to other datasets or customized for specific applications. Feel free to explore and modify the code to suit your needs.

## Dependencies
- Python 3
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, wordcloud

## License
This project is licensed under the [Your License Name] - see the [LICENSE.md](LICENSE.md) file for details.

#Author_Shashank_Shekhar_Pandey
