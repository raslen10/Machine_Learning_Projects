# Language Detection using Multinomial Naive Bayes
## Overview
This project aims to classify the language of text data into English, German, or Spanish using a Multinomial Naive Bayes classifier. The model is trained on the Europarl corpus dataset, which contains text samples in multiple languages.

## Data
The dataset used for training consists of parallel texts from the Europarl corpus for English, German, and Spanish languages. Each language's text data is preprocessed by converting to lowercase, removing punctuation, and removing numerical digits.

## Model
The model architecture used is a Multinomial Naive Bayes classifier. Text data is converted into numerical form using CountVectorizer, which creates a Bag of Words model. The model is trained on the transformed text data and predicts the language of the input text.

## Evaluation
The model's performance is evaluated using accuracy, precision, recall, and f1-score metrics. A confusion matrix is also visualized to assess the model's performance across different languages.

## Usage
To use the model for language detection, follow these steps:

Clone the repository to your local machine.
Install the required dependencies listed in the requirements.txt file.
Load the trained model and CountVectorizer object.
Use the predict function to make language predictions for input text.
## Example:

python
from language_detection_model import predict

text = "Bonjour tout le monde"
predict(text)  # Output: "The language is in French"


## Future Improvements
Experiment with different models such as Support Vector Machines or Deep Learning architectures.
Include more languages in the training dataset to improve the model's language coverage.
