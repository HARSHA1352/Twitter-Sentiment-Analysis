

This project is an application of Support Vector Machines (SVMs) for sentiment analysis on Twitter data. The goal is to predict whether a given tweet expresses positive or negative sentiment.

## Installation

To run this project, you will need Python 3 and the following libraries:

* `numpy`
* `pandas`
* `nltk`
* `scikit-learn`
* `matplotlib`

You can install these libraries using `pip`. For example:

```
pip install numpy pandas nltk scikit-learn matplotlib
```

## Usage

The main file for this project is `svm_twitter.py`. This file contains the code to preprocess the data, train the SVM model, and test the model on a validation set. To run the program, simply execute the following command in the terminal:

```
python svm_twitter.py
```

The program will prompt you to enter the file path for the dataset. The dataset should be in CSV format with the following columns:

* `text`: the text of the tweet
* `sentiment`: the sentiment label (`positive` or `negative`)

Once you enter the file path, the program will preprocess the data, split it into training and validation sets, train the SVM model, and test the model on the validation set. It will then output the classification report, confusion matrix, and accuracy score of the model.

## Files

* `svm_twitter.py`: the main file for the project
* `dataset.csv`: a sample dataset for testing the program
* `README.md`: this file

