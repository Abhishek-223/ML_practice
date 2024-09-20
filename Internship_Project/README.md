# Sentiment Analysis Project

This repository contains a comprehensive sentiment analysis project that includes an HTML app for user input, a machine learning model for training and testing, and data analysis for sentiment analysis.

## Project Overview

The project aims to develop a sentiment analysis model that can classify reviews as positive or negative. The model is trained on a dataset of reviews and uses various preprocessing techniques such as lowercasing, removing stop words, lemmatization, and stemming to prepare the text data for modeling. The model is then deployed as an HTML app that takes user input reviews and provides sentiment analysis.

## Project Structure

The project structure is as follows:

📁 app: # This folder contains the HTML app for user input and sentiment analysis. 📁 data: # This folder contains the dataset of reviews used for training and testing the model. 📁 models: # This folder contains the machine learning model used for sentiment analysis. 📁 notebooks: # This folder contains Jupyter notebooks for data analysis and model development. 📁 preprocessing: # This folder contains scripts for preprocessing the text data. README.md: # This file provides an overview of the project.


## How to Use

To use the project, follow these steps:

1. **Clone** the repository to your local machine:
```bash
   git clone https://github.com/your-username/sentiment-analysis-project.git
```
Open the app folder and run the HTML app in a web browser.

Enter a review in the input field and click the "Analyze" button.

The app will display the sentiment analysis of the review.

Model Development
The machine learning model used for sentiment analysis is a Multinomial Naive Bayes classifier. The model was trained on a dataset of reviews using TF-IDF vectorization to transform the text into numerical features. The performance of the model was evaluated using the accuracy score and a detailed classification report.

Preprocessing Steps
Lowercasing: Converts all text to lowercase.
Removing stop words: Common words (e.g., "the", "is") are removed as they do not contribute much to sentiment.
Lemmatization: Converts words to their base form (e.g., "running" becomes "run").
Stemming: Reduces words to their root form (e.g., "fishing" becomes "fish").
Data Analysis
The data analysis was conducted using Jupyter notebooks. These notebooks contain scripts for:

Data preprocessing: Cleaning and preparing the dataset for model training.
Feature engineering: Extracting useful features from the text data.
Model development: Implementing and fine-tuning the sentiment analysis model.
Technologies Used
The project utilizes the following technologies:

HTML/CSS: For building the app interface.
JavaScript: For adding interactivity and functionality to the app.
Python: For machine learning model development and data analysis.
Jupyter Notebooks: For exploring and analyzing the dataset.
TF-IDF Vectorization: For converting text data into numerical form.
Multinomial Naive Bayes: A machine learning algorithm used for sentiment analysis.
License
This project is licensed under the MIT License.

Acknowledgments
This project was developed using various online resources and tutorials. Special thanks to github.com and github.com for providing inspiration and guidance.

Contributing
Contributions to the project are welcome! If you'd like to contribute, please follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix.
Submit a pull request with your changes.
We appreciate your contribution!
