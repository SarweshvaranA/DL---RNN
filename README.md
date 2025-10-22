# DL- Developing a Recurrent Neural Network Model for Stock Prediction

## AIM:
To develop a Recurrent Neural Network (RNN) model for predicting stock prices using historical closing price data.


## DESIGN STEPS:
### STEP 1: 

Import libraries for data processing, visualization, PyTorch, and machine learning operations.

### STEP 2: 

Load training and testing datasets from CSV files containing stock closing prices.

### STEP 3: 

Extract and reshape closing prices for training and testing datasets properly.

### STEP 4: 

Normalize data using MinMaxScaler based only on training dataset values.

### STEP 5: 

Create sequences of 60 previous prices to predict next stock price.

### STEP 6: 

Convert sequences and targets into PyTorch tensors for model training.

### STEP 7: 

Create TensorDataset and DataLoader for batch processing during model training.

### STEP 8: 

Define RNN model with two layers, hidden size 64, and linear output.

### STEP 9: 

Initialize model, move to GPU if available, and define MSE loss.

### STEP 10: 

Train model: forward pass, compute loss, backpropagate, optimize parameters iteratively.

### STEP 11: 

Evaluate model on test set without gradients, predict and inverse transform prices.

### STEP 12:

Plot actual versus predicted stock prices and display last predicted value.


## PROGRAM:

### Name: SARWESHVARAN A

### Register Number: 212223230198



### OUTPUT:

## Training Loss Over Epochs Plot

<img width="550" height="520" alt="image" src="https://github.com/user-attachments/assets/04e70d01-64e9-4d83-97c7-8dc40edda72f" />


## True Stock Price, Predicted Stock Price vs time

<img width="550" height="520" alt="image" src="https://github.com/user-attachments/assets/64e951b8-fd43-4886-aa93-3c4a18ca4177" />


### Predictions

<img width="126" height="25" alt="image" src="https://github.com/user-attachments/assets/004353d1-f567-4ad1-9427-775b23571be9" />


## RESULT

VGG19 model was fine-tuned and tested successfully. The model achieved good accuracy with correct predictions on sample test images.
