<h1>Sentiment Analysis on IMDB Movie Reviews using PyTorch</h1>
<p>In this project, I built a sentiment analysis model on IMDB movie reviews using PyTorch. The dataset consisted of 50,000 movie reviews, with 25,000 for training and 25,000 for testing. The reviews were labeled as either positive or negative, and the task was to predict the sentiment of a given review.</p>
<h2>Requirements</h2>
<p>To run this project, you will need to install following packages: </p>
<ul>
  <li>Python</li>
  <li>PyTorch</li>
  <li>NumPy</li>
  <li>Pandas</li>
  <li>NLTK</li>
</ul>
<h2>Data Preprocessing</h2>
<p>The following are the text prerocessing techniques used on the data:</p>
<ul>
  <li>Removing HTML tags and punctuation.</li>
  <li>Converting all reviews to lowercase.</li>
  <li>Removing stopwords</li>
  <li>Lemmatizing the reviews</li>
  <li>Tokenizing the reviews</li>
  <li>Padding or truncating the reviews to a fixed length</li>
  <li>Converting the tokens to integers</li>
</ul>
<h2>Model</h2>
<p>The model used in this project is a multi-layer LSTM network that was trained on IMDB movie reviews with the goal of predicting the sentiment of a given review. The model was also evaluated on a validation set during the training process to ensure it was not overfitting. Finally, the model was evaluated on the test set, and the evaluation metric was accuracy. The model achieved an accuracy of approximately 79%.</p>
<h2>Predictions</h2>
<p>Here are some predictions made by the model on the following sentenses:
</p>
<ul>
<li>This is a bad movie. <strong>NEGATIVE</strong></li>
<li>I am very happy today.<strong>POSITIVE</strong></li>
<li>I don't like this product it has a bad quality.<strong>NEGATIVE</strong></li>
</ul>
