# sentiment-analysis
Sentiment Analysis using BERT

This project demonstrates how to use the pre-trained BERT model from Hugging Face to perform sentiment analysis. The model predicts whether a given text is positive, neutral, or negative. The implementation utilizes the nlptown/bert-base-multilingual-uncased-sentiment model, which is designed for multilingual sentiment analysis. Sentiment analysis is a natural language processing task used to determine the emotional tone behind a piece of text. This project provides a Python script that leverages BERT to classify sentiments with high accuracy and confidence, making it suitable for various applications like customer feedback analysis, social media monitoring, and more.

Features

Pre-trained Model: Uses Hugging Face's nlptown/bert-base-multilingual-uncased-sentiment.

Sentiment Classes: The output sentiment is classified as positive, neutral, or negative.

Confidence Scores: The model provides a confidence score for the predicted sentiment.

Requirements

To run the project, ensure the following packages are installed:

Python 3.8+

torch (PyTorch library)

transformers (Hugging Face Transformers library)

You can install the dependencies using pip:

pip install torch transformers

How to Run

Clone the repository:

git clone <repository-url>
cd <repository-directory>

Run the Python script:

python sentiment_analysis.py

Enter any text to analyze its sentiment. Type exit to quit the program.
