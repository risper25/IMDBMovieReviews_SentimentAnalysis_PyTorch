<h1>Sentiment Analysis on IMDB Movie Reviews using PyTorch</h1>
<p>In this project I built a sentiment analysis model on IMDB movie reviews using PyTorch. The dataset consists of 50,000 movie reviews, with 25,000 for training and 25,000 for testing. The reviews are labeled as either positive or negative, and the task is to predict the sentiment of a given review.</p>
<h2>Requirements</h2>
<p>To run this project, you will need the following packages:</p>
<ul>
  <li>Python</li>
  <li>PyTorch</li>
  <li>NumPy</li>
  <li>Pandas</li>
  <li>NLTK</li>
</ul>
<h2>Data Preprocessing</h2>
<p>Before training the model, the data must be preprocessed. This includes:</p>
<ol>
  <li>Removing HTML tags and punctuation.</li>
  <li>Converting all reviews to lowercase.</li>
  <li>Removing stopwords</li>
  <li>Lemmatizing the reviews</li>
  <li>Tokenizing the reviews</li>
  <li>Padding or truncating the reviews to a fixed length</li>
  <li>Converting the tokens to integers</li>
</ol>
<h2>Model</h2>
<p>The model used in this project is a multi-layer LSTM network that is trained on IMDB movie reviews with the goal of predicting the sentiment of a given review. The model is also evaluated on a validation set during the training process to ensure it is not overfitting. Finally, the model is evaluated on the test set, and the evaluation metric is accuracy.The model achieved an accuracy of approximately 79%.</p>
<h2>Predictions</h2>
<p>These are some outputs given by the model </p>
