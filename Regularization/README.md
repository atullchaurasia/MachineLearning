# Regularization Techniques: L1, L2, and Elastic Net

This repository provides an in-depth exploration of regularization techniques, including **L1 Regularization (Lasso)**, **L2 Regularization (Ridge)**, and **Elastic Net Regularization**. These techniques are essential for preventing overfitting in machine learning models, specifically in linear and logistic regression models.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Regularization Techniques](#regularization-techniques)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

In this project, we implement various regularization techniques to address overfitting by adding a penalty term to the model's cost function. Regularization is particularly useful when dealing with high-dimensional data and preventing the model from learning noise from the training dataset.

The notebook demonstrates:

1. Implementing L1 (Lasso) and L2 (Ridge) regularization techniques.
2. Using Elastic Net Regularization, which combines L1 and L2 penalties.
3. Evaluating model performance with different regularization parameters.

## Features

- **L1 Regularization (Lasso):** Adds a penalty proportional to the absolute value of coefficients.
- **L2 Regularization (Ridge):** Adds a penalty proportional to the square of coefficients.
- **Elastic Net Regularization:** A hybrid approach combining L1 and L2 penalties.
- **Evaluation Metrics:** Model performance is evaluated using metrics like Mean Squared Error (MSE) and R-squared (R²) score.

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/regularization-techniques.git
   cd regularization-techniques
   ```

2. **Install the Required Packages:**

   Use the following command to install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

   Alternatively, you may manually install essential libraries such as:

   ```bash
   pip install numpy pandas scikit-learn matplotlib
   ```

## Usage

1. **Open the Notebook:**

   Launch the Jupyter Notebook to explore the code and documentation:

   ```bash
   jupyter notebook Regularization(L1,_L2,_Elastic).ipynb
   ```

2. **Run the Code:**

   Execute each cell in sequence to understand the implementation and visualize the effects of regularization.

3. **Modify Parameters:**

   Experiment with different regularization parameters (alpha values) for L1, L2, and Elastic Net to observe changes in model performance.


## Regularization Techniques

### 1. L1 Regularization (Lasso)

L1 regularization, or Lasso (Least Absolute Shrinkage and Selection Operator), adds a penalty equivalent to the absolute value of the magnitude of coefficients. This method can result in sparse models, setting some coefficients to zero, effectively performing feature selection.

### 2. L2 Regularization (Ridge)

L2 regularization, or Ridge regression, adds a penalty equivalent to the square of the coefficient magnitudes. This method discourages large coefficients and is useful in high-dimensional datasets to prevent overfitting.

### 3. Elastic Net Regularization

Elastic Net combines both L1 and L2 penalties, controlled by the parameter alpha and the mixing ratio rho. This technique is beneficial when dealing with correlated features.

## Results

- **Model Performance:** Each regularization technique impacts model coefficients differently, reducing the risk of overfitting.
- **Trade-off Exploration:** By adjusting regularization parameters, the trade-off between bias and variance can be observed.

Graphs and visualizations in the notebook provide insight into the effects of regularization.


## License

Distributed under the MIT License. See `LICENSE` for more information.

