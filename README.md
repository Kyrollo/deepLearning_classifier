# Dogs vs. Cats Classifier

This repository contains a machine learning project for classifying images of dogs and cats using various neural network models. The dataset used for this project is from the [Kaggle Dogs vs. Cats competition](https://www.kaggle.com/c/dogs-vs-cats).

## Project Structure

- **data/**: Directory containing the dataset.
- **notebooks/**: Jupyter notebooks for data exploration and preprocessing.
- **models/**: Saved trained models.
- **src/**: Source code for training and evaluating models.
- **README.md**: Project documentation.

## Dataset

The dataset for this project can be downloaded from the [Kaggle Dogs vs. Cats competition](https://www.kaggle.com/c/dogs-vs-cats). It contains labeled images of dogs and cats.

## Models

The project includes the following models:
1. **Model 1**: Simple ANN with 1 hidden layer.
2. **Model 2**: ANN with 3 hidden layers.
3. **Model 3**: ANN with 2 hidden layers.
4. **Model 4**: Single-layer ANN.
5. **Model 5**: Convolutional Neural Network (CNN).

Each model is trained and evaluated to determine the best performing one.

## Training

The models are trained on the dataset using the following steps:

1. **Data Preprocessing**:
    - Load and preprocess images.
    - Split the dataset into training and testing sets.
    - Reshape and scale the data as required by each model.

2. **Model Training**:
    - Train each model using the training data.
    - Evaluate the model on the validation set.
    - Save the trained models.

3. **Model Selection**:
    - Compare the accuracy of all models.
    - Select the model with the highest accuracy for predictions.
