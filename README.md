# Shahnameh RNN Poetry Generation

## Overview
This repository contains an implementation of a Recurrent Neural Network (RNN) designed to generate verses of Shahnameh, a classic Persian epic poem. The goal is to train the RNN on sequences from Shahnameh and enable it to generate text with similar structure and style.

## Features
- **Data Preparation**
  - Collecting and preprocessing text data from Shahnameh.
  - Creating sequences for training the RNN.

- **Model Creation and Training**
  - Building an RNN model using TensorFlow and Keras.
  - Compiling the model with an appropriate loss function.
  - Training the model on the prepared text data.

- **Text Generation**
  - Generating new verses by feeding a sequence of text to the trained RNN.
  - Evaluating the generated text to assess the model's performance.

## Dataset
The dataset used in this project is extracted from the Shahnameh, an epic Persian poem written by Ferdowsi around 1000 AD. Shahnameh, also known as "The Book of Kings," is a monumental work that tells the history of the Persian Empire from its mythical beginnings to the Arab conquest. The text file `shahnameh.txt` contains the verses used for training and evaluating the RNN model.

- **`shahnameh.txt`**: The text file containing verses of Shahnameh used for training the RNN.

## Pretrained Model
The repository also includes a pretrained model saved after 650 epochs of training. This model can be used to generate verses without the need for retraining the network from scratch.

- **`650epochs.hdf5`**: The pretrained model file.

## Files
- **`RNN_Poetry_Generation.ipynb`**: Jupyter Notebook containing the implementation of the RNN for poetry generation.
- **`shahnameh.txt`**: The dataset file used for training the RNN model.
- **`650epochs.hdf5`**: The pretrained model file after 650 epochs.

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Python 3.6 or higher
- Libraries: numpy, tensorflow, keras, tqdm

You can install the required packages using the following command:
```bash
pip install numpy tensorflow keras tqdm
