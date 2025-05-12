# Human Activity Recognition using Smartphones - Machine Learning

## Overview
This project explores human activity recognition using accelerometer and gyroscope data from smartphones. The aim is to build a model that can accurately predict the activity performed by an individual based on sensor data.

![Data](https://raw.githubusercontent.com/Sjschhabra/Activity-Recognition-ML/refs/heads/main/Screenshot%202025-05-11%20191403.png)
## Data
The dataset consists of accelerometer and gyroscope readings collected from smartphones. It includes features such as mean and standard deviation of acceleration in different directions, as well as statistical measures derived from these readings.

## Methodology
1. **Data Loading and Exploration**: The dataset is loaded into a pandas DataFrame and explored to understand its structure and contents. Missing values, if any, are handled appropriately.
2. **Data Preprocessing**: Categorical labels are encoded numerically for model training. The dataset is split into features (X) and target labels (Y).
3. **Model Building**: A neural network model is constructed using the Keras Sequential API. It consists of multiple dense layers with relu activation for hidden layers and softmax activation for the output layer. The model is compiled with appropriate loss function, metrics, and optimizer.
4. **Model Training**: The model is trained on the training data for a specified number of epochs.
5. **Model Evaluation**: The trained model is evaluated on the test data to assess its performance. Metrics such as loss and accuracy are calculated.

## Results
- The model achieves an accuracy of approximately 98% on the test set, indicating its effectiveness in predicting human activities based on smartphone sensor data.

## Conclusion
The project demonstrates the feasibility of using machine learning models to recognize human activities using smartphone data. Such models have potential applications in various domains, including healthcare, fitness tracking, and behavior analysis.
