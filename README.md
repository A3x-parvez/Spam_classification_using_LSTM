
<div align="center">
  <h1 style="font-weight: 900; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; color: #1e90ff; text-shadow: 2px 2px 4px rgba(0,0,0,0.2);">
    Spam Classification using LSTM 
  </h1>
  <p>
    <strong>This repository contains a project for classifying SMS messages as either "spam" or "ham" (not spam) using a Long Short-Term Memory (LSTM) neural network.</strong>
  </p>

  <!-- Badges -->
  <p>
    <a href="https://github.com/a3x-parvez/flipkart_review_sentiment_web/actions"><img src="https://img.shields.io/github/actions/workflow/status/a3x-parvez/flipkart_review_sentiment_web/main.yml?branch=main&style=for-the-badge" alt="Build Status"></a>
    <a href="https://github.com/a3x-parvez/flipkart_review_sentiment_web/blob/main/LICENSE"><img src="https://img.shields.io/github/license/a3x-parvez/flipkart_review_sentiment_web?style=for-the-badge" alt="License"></a>
    <a href="https://github.com/a3x-parvez/flipkart_review_sentiment_web/issues"><img src="https://img.shields.io/github/issues/a3x-parvez/flipkart_review_sentiment_web?style=for-the-badge" alt="Issues"></a>
    <a href="https://github.com/a3x-parvez/flipkart_review_sentiment_web/stargazers"><img src="https://img.shields.io/github/stars/a3x-parvez/flipkart_review_sentiment_web?style=for-the-badge" alt="Stargazers"></a>
  </p>
</div>

## 👤 Author
<!-- Add this in your HTML <head> to load the font -->
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">

<div align="center">
  <h2 style="font-family: 'Pacifico', cursive; font-size: 2.2em; color: #4108edff; text-shadow: 2px 2px 4px rgba(0,0,0,0.2);">
  Rijwanool Karim
</h2>
  <p style ="font-weight: 900; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; color: #34ed13ff; text-shadow: 2px 2px 4px rgba(0,0,0,0.2); font-size: 1.2em">AIML Developer & AI Enthusiast</p>
  <p align="center" style="margin-top: 10px;">
  <a href="https://github.com/a3x-parvez" target="_blank" style="margin: 0 10px;">
    <img src="https://img.shields.io/github/followers/a3x-parvez?style=social&label=GitHub" alt="GitHub Followers" height="30"/>
  </a>
  <a href="https://www.linkedin.com/in/rijwanool-karim" target="_blank" style="margin: 0 10px;">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=social&logo=linkedin" alt="LinkedIn" height="30"/>
  </a>
  <a href="https://my-portfolio-2-alpha-sandy.vercel.app/" target="_blank" style="margin: 0 10px;">
    <img src="https://img.shields.io/badge/Website-Visit-orange?style=social&logo=google-chrome" alt="Website" height="30"/>
  </a>
</p>

</div>

---

## Description

The project uses a dataset of SMS messages to train an LSTM model that can accurately predict whether a new message is spam or not. The model is built using Python and the TensorFlow/Keras library.

---

## Dataset

The dataset used for this project is `SPAM_text_message_20170820.csv`. It contains two columns: "Category" (specifying if a message is "ham" or "spam") and "Message" (the content of the SMS).

---

## Requirements

The following libraries are required to run the project:

* pandas
* numpy
* seaborn
* matplotlib
* nltk
* tensorflow
* scikit-learn

---

## Usage

1.  Clone the repository:
    ```
    git clone https://github.com/a3x-parvez/spam_classification_using_lstm.git
    ```
2.  Install the required libraries:
    ```
    pip install pandas numpy seaborn matplotlib nltk tensorflow scikit-learn
    ```
3.  Run the Jupyter Notebook `Spam_classification_using_LSTM.ipynb`.

---

## Model Architecture

The model is a sequential neural network with the following layers:

1.  **Embedding Layer:** Converts text into dense vectors of fixed size.
2.  **LSTM Layer:** A type of recurrent neural network (RNN) that is well-suited for sequence data like text.
3.  **Dense Layer:** A fully connected layer with a sigmoid activation function for binary classification.

---

## Results

 **The trained model achieves a test accuracy of approximately 93%.**

 **The model effectively distinguishes spam from non-spam SMS messages.**

## Suggestions for Improvement

 - Add a sample input/output section to show how predictions are made.

 - Add data preprocessing steps in the README for clarity (tokenization, padding, stopwords removal).

 - Consider including confusion matrix or precision/recall metrics for a better understanding of model performance.

 - Include instructions on saving and loading the trained model for future inference.
