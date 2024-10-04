# Car Price Prediction

## Overview

This project implements a linear regression model to predict car prices based on various features using a dataset loaded from a CSV file (`craprice.csv`). The code includes data preprocessing, exploratory data analysis, model training, evaluation, and visualization of results.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Visualization](#visualization)
- [License](#license)

## Installation

To run this project, you will need Python installed along with the following libraries:

- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn

You can install the required libraries using pip:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Usage

1. Clone the repository or download the code file.
2. Make sure the `craprice.csv` file is in the same directory as your script, or provide the correct path to the file in the code.
3. Run the Python script using your preferred IDE or from the command line:

```bash
python car_price_prediction.py
```

## Dataset

- The dataset used in this project is `craprice.csv`, which contains various features related to cars, including but not limited to:
  - `make`: The manufacturer of the car (categorical)
  - `model`: The specific model of the car (categorical)
  - `year`: The year of manufacture (numerical)
  - `mileage`: The mileage of the car (numerical)
  - `price`: The price of the car (target variable)

## Exploratory Data Analysis

The project includes a section for exploratory data analysis (EDA) which covers:

- **Distribution of Car Prices**: A histogram visualizing the distribution of car prices.
- **Correlation Heatmap**: A heatmap displaying the correlation between different features and the target variable.

## Model Training

A linear regression model is used to predict car prices based on the features in the dataset. The steps include:

- Splitting the dataset into training and testing sets.
- Training the model on the training set.
- Displaying model coefficients and intercept.

## Evaluation

The model's performance is evaluated using:

- **Mean Squared Error (MSE)**: Measures the average squared difference between actual and predicted prices.
- **R-squared (R²)**: Indicates the proportion of variance in the target variable that can be explained by the features.

## Visualization

A scatter plot is generated to compare actual prices against predicted prices, along with a 45-degree line representing perfect predictions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
