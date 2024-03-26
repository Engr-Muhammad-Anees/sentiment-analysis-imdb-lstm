# LSTM Sentiment Analysis Model for IMDB Reviews
This model is trained on the IMDB dataset of 50,000 movie reviews, and can be used to predict the sentiment of a given movie review.

## Model Architecture
The model is a sequential model with the following layers:
- Embedding layer with 10000 input features and 128 output features
- Dense layer with 64 units and ReLU activation
- Dropout layer with a dropout rate of 0.5
- Dense layer with 1 unit and sigmoid activation

## Training
The model was trained for 5 epochs with a batch size of 32.

## Evaluation
The model achieved an accuracy of 88% on the test set.

## Usage
To use the model, simply pass a list of movie reviews to the  method.
The model will return a list of predictions, where each prediction is a probability between 0 and 1.

## Saving the Model
The model can be saved using the  method.
The saved model can be loaded using the  method.
