# Alphabet Soup Deep Learning Model Performance Report

## Project Description

The project involved creating a deep learning model using TensorFlow and Keras to predict the success of funding applicants for Alphabet Soup based on various input features. The goal was to achieve an accuracy higher than 75%.

## File Structure

AlphabetSoupCharity.ipynb

AlphabetSoupCharity.h5

AlphabetSoupCharity_Optimization.ipynb

AlphabetSoupCharity_Optimization.h5

All files are located in the main directory. The detailed report is written at the very bottom of AlphabetSoupCharity_Optimization.ipynb.

## Approach

Data Preprocessing:

Identified the target variable (IS_SUCCESSFUL) and features.

Dropped irrelevant columns (EIN and NAME).

Encoded categorical variables and split the data into training and testing sets.

Scaled the data using StandardScaler.

## Model Design and Training:

Built neural network models with varying complexities, adjusting the number of hidden layers and neurons.

Used ReLU activation for hidden layers and sigmoid activation for the output layer.

Trained the models and evaluated their performance using accuracy metrics.

## Optimization Attempts:

Adjusted binning for rare occurrences.

Explored different neural network architectures.

Increased the number of epochs for training.

## Results

Model Performance:

First model accuracy: 72.7%.
Second model accuracy: 72.4%.

Achievements:
Developed two models that provided valuable insights despite not meeting the 75% target.

Explored various optimizations, including adjusting binning, adding hidden layers and neurons, using different activation functions, and increasing epochs.

Demonstrated proficiency in TensorFlow and Keras for deep learning model development.

## Recommendations

Continue fine-tuning hyperparameters and exploring more complex neural network architectures.
Apply regularization techniques to improve model performance.

## Summary

The project aimed to develop a deep learning model to predict funding applicants' success for Alphabet Soup, achieving accuracies of 72.7% and 72.4% for the two models. Despite not meeting the 75% target, the models provided valuable insights and demonstrated proficiency in TensorFlow and Keras. Future efforts should focus on further optimizing hyperparameters and exploring more complex neural network architectures.





