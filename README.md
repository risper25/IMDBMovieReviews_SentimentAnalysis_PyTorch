<html>
  <body>
    <h1>Sentiment Analysis with PyTorch</h1>
    <p>This repository contains a PyTorch implementation of a sentiment analysis model for movie reviews. The model was trained on the IMDB movie review dataset and achieved a test accuracy of 79%.</p>
    <h2>Requirements</h2>
    <p>To run the ___ notebook, you will need to have the following packages installed:</p>
    <ul>
      <li>Python</li>
      <li>PyTorch</li>
      <li>NumPy</li>
      <li>Pandas</li>
      <li>NLTK</li>
    </ul>
    <h2>Data</h2>
    <p>The IMDB movie review dataset is included in this repository. It consists of 50,000 movie reviews, evenly split between positive and negative sentiments. The dataset has already been preprocessed, with punctuation and stop words removed, the reviews converted to lower case, and lemmatization applied. The reviews were then encoded as sequences of integers. The data was split into training, validation, and test sets, with the training set being used to train the model and the validation and test sets being used for evaluation.</p>
    <h2>Model</h2>
    <pThe model used in this project is a neural network with an embedding layer and LSTM (long short-term memory). It takes in integer-encoded reviews and produces a prediction of the sentiment (positive or negative). The model achieved a test accuracy of 79% on the IMDB movie review dataset.The model was saved as </p>
    <h2>Predictions</h2>
    <ul>
      <li>"This is a bad movie." - <strong>NEGATIVE</strong></li>
      <li>"I am very happy today." - <strong>POSITIVE</strong></li>
      <li>"I don't like this product it has a bad quality." - <strong>NEGATIVE</strong></li>
    </ul>
  </body>
</html>



