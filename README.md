# Sentiment Analysis using LSTM

**Project Overview**
This project Build deep learning model for sentiment analysis using Long Short-Term Memory (LSTM) networks. The model classifies text into either positive or negative sentiment.

**Dataset**
[Dataset is IMDB Dataset,shape is 50000 Rows 2 Columns, format :- .csv]

**Model Architecture**
* Embedding layer with a vocabulary size of 5000 and embedding dimension of 128.
* LSTM layer with 128 units.
* Dense layer with sigmoid activation for classification.


**Training**
The model is trained using the Adam optimizer and binary_crossentropy loss. Early stopping is implemented to prevent overfitting.

**Dependencies**
* Python 3.x
* TensorFlow
* Pandas
* NumPy
* Matplotlib
* Seaborn
* NLTKs

**Results**
* Accuracy 0.88
* Avg precision  0.88
* Avg Recall 0.88
