Fake News Prediction

Overview

This project is focused on developing a machine learning model to detect whether a news article is fake or real. The model is trained using a dataset of news articles, and various NLP techniques are applied to process the text data. The project is implemented entirely in a Jupyter notebook. 


The dataset i used were from: https://www.kaggle.com/c/fake-news/data?select=train.csv

Data
The dataset consists of labeled news articles, categorized as either "Real" or "Fake". The data is split into training and testing sets, which are used in the notebook for model training and evaluation.

Installation
To run the notebook, ensure you have Python 3.7+ and Jupyter Notebook installed. Clone the repository and install the necessary dependencies:

bash
Copy code
git clone https://github.com/yourusername/FakeNewsPrediction.git

cd FakeNewsPrediction

pip install -r requirements.txt

Additionally, you may need to download the NLTK stopwords dataset:

python:
import nltk
nltk.download('stopwords')
Usage
To start working with the project, open the Jupyter notebook:

bash
jupyter notebook
Navigate to the Fake_news_prediction.ipynb notebook and run the cells sequentially. The notebook covers:

Loading the Dataset: Import the data into a Pandas DataFrame.

Text Preprocessing: Clean the text data by removing stopwords and stemming words.

Feature Extraction: Use TF-IDF vectorization to convert the text data into numerical features.

Model Training: Train a Logistic Regression model on the processed data.

Evaluation: Assess the model's performance using accuracy metrics.

Model Training and Evaluation

The model is trained using Logistic Regression, which is a robust classifier for binary classification tasks. The evaluation includes calculating the accuracy of the model on the test set, which is displayed at the end of the notebook.

Results
The results of the model, including accuracy, are documented within the notebook. The model provides a reliable indicator of whether news articles are likely to be fake or real.



