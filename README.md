# MNIST Fashion Image Classification

This project focuses on building a machine learning model (Feedforward Neural Network, Convolutional Neural Network) to 
classify fashion items using the FashionMNIST dataset sourced from [Kaggle](https://www.kaggle.com/datasets/zalando-research/fashionmnist).
FashionMNIST is a dataset of Zalando's article images, consisting of 60,000 training examples and 10,000 test examples. 
Each example is a 32x32 grayscale image associated with a label from 10 classes.

In `train.csv` dataset the number of examples was reduced to 52500 entries.

## Dataset Overview

Zalando intends Fashion-MNIST to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking 
machine learning algorithms. It shares the same image size and structure of training and testing splits.

The original MNIST dataset contains a lot of handwritten digits. Members of the AI/ML/Data Science community love this 
dataset and use it as a benchmark to validate their algorithms. In fact, MNIST is often the first dataset researchers try. 
"If it doesn't work on MNIST, it won't work at all", they said. "Well, if it does work on MNIST, it may still fail on 
others."

Zalando seeks to replace the original MNIST dataset.

## Project Structure
The project is organized as follows:
- `train.csv`: Dataset in csv format
- `README.md`: This file providing an overview of the project (You are reading it right now!).
- `mnist_fashion_cnn.ipynb`: Jupyter Notebook containing the code for data preprocessing, EDA, model training, and evaluation.
- `requirements.txt`: List of Python packages required to run the notebook.
- `.gitattributes`: LFS tracking file for `train.csv` dataset.

## Setup and Usage
1. **Setup**
   - Clone this repository to your local machine.
      ```bash
      git clone https://github.com/vakandrii/mnist_fashion_cnn.git
      ```
   - Navigate to the project directory.
   - Install the required Python packages using pip:
     ```bash
     pip install -r requirements.txt
     ```
   - Launch Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Open `mnist_fashion_cnn.ipynb` in your browser.

## Acknowledgment
I extend my thanks to the Zalando Research team for creating the FashionMNIST dataset and making it accessible to the data 
science community. This project has been an enriching experience in developing machine learning solutions for image 
classification tasks.