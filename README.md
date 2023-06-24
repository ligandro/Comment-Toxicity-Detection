# Comment-Toxicity-Detection
## A Comment Toxicity Detection Model with Deep Learning and Python. LSTM model used 
## About Project:
This project is used to classify comments and assign true or false values to following labels:
toxic
severe_toxic
obscene
threat
insult
identity_hate

A model is created which predicts a probability of each type of toxicity for each comment. Data is from the Toxic Comment Classification Challenge on Kaggle.In the text preprocessing, a vectorizer is used to convert the text into vectors. It is then fed into the bidirectional LSTM model for training. 

![Screenshot 2023-06-23 at 9 39 42 PM](https://github.com/ligandro/Comment-Toxicity-Detection/assets/97714265/f90808c3-37af-443a-af39-4f945ab41d3d)

Precision: 0.9416884183883667
Recall:0.9151395559310913
Accuracy:0.4603811502456665

## Business Use case:
*   This project can be used to label toxic comments from social media sites such as youtube
*   Creates a detailed classification instead of just classifying as negative or positive


## Model
### LSTM Neural Network

Long Short Term Memory is a kind of recurrent neural network. In RNN output from the last step is fed as input in the current step. It tackles the problem of long-term dependencies of RNN in which the RNN cannot predict the word stored in the long-term memory but can give more accurate predictions from the recent information. As the gap length increases RNN does not give an efficient performance. LSTM can by default retain the information for a long period of time. It is used for processing, predicting, and classifying on the basis of time-series data.LSTM networks are capable of learning long-term dependencies in sequential data, which makes them well suited for tasks such as language translation, speech recognition, and time series forecasting.

Read more at https://www.geeksforgeeks.org/deep-learning-introduction-to-long-short-term-memory/


## TechStack Used(Python Libraries):
* Numpy
* Pandas
* Tensorflow
* Keras
* Gradio


## Loss over epochs

![Loss](https://github.com/ligandro/Comment-Toxicity-Detection/assets/97714265/035a3a25-3f48-4d63-84e4-58a90c0b08ae)

## Gradio interface

![Screenshot 2023-06-23 at 9 31 40 PM](https://github.com/ligandro/Comment-Toxicity-Detection/assets/97714265/698a3e15-f45e-43b3-837e-6a70321510d8)
