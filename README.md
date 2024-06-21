# Task - 1 : Predicting Student Scores Based on Study Hours

This repository contains a simple linear regression model that predicts the percentage of marks a student is expected to score based on the number of hours they studied. This project demonstrates the use of basic machine learning techniques for predictive analysis.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Evaluation](#evaluation)
- [Contributing](#contributing)

## Introduction

This project aims to predict the percentage of marks that a student is expected to score based on the number of hours they studied. The task is performed using simple linear regression, which is a type of supervised learning algorithm.

## Dataset

The dataset used in this project is sourced from [this link](http://bit.ly/w-data). It contains two columns: 'Hours' (number of hours studied) and 'Scores' (percentage score).

## Installation

To run this project, you need to have Python installed along with the following libraries:

- pandas
- numpy
- matplotlib
- scikit-learn

You can install the necessary libraries using pip:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/student-score-prediction.git
```


## Results

After training the model, you will see the scatter plot of the data along with the regression line. The model's R^2 score (coefficient of determination) is approximately 0.9454, indicating that the model explains about 94.54% of the variance in the scores based on the number of hours studied.

### Prediction Example

If a student studies for 9.25 hours, the model predicts that they will score approximately 93.69%.

## Evaluation

The model's performance is evaluated using the Mean Absolute Error (MAE), which is 4.1839. This indicates that, on average, the predictions are off by about 4.18 percentage points.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. We welcome improvements, bug fixes, and additional features.
