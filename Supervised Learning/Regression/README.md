# Regression Models

This repository contains implementations of various regression models including **Simple Linear Regression**, **Multiple Linear Regression**, and **Polynomial Regression**. The models are evaluated using metrics such as **Mean Squared Error (MSE)** and **R² (Coefficient of Determination)**.

## Table of Contents
- [Introduction](#introduction)
- [Models Implemented](#models-implemented)
  - [Simple Linear Regression](#simple-linear-regression)
  - [Multiple Linear Regression](#multiple-linear-regression)
  - [Polynomial Regression](#polynomial-regression)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [How to Run](#how-to-run)
- [Dependencies](#dependencies)

## Introduction

Regression analysis is a statistical method used to model the relationship between a dependent variable and one or more independent variables. This project demonstrates the use of three types of regression models.

### Mathematical Formulations:
 
   ![image](https://github.com/user-attachments/assets/151b133b-af11-406f-bc0b-e6f49ed74421)
   ![image](https://github.com/user-attachments/assets/77aabe05-a595-4a92-b303-df3183f07e09)
   

## Models Implemented

### Simple Linear Regression

In **Simple Linear Regression**, we model the relationship between one independent variable x and one dependent variable y.

The model fits a line through the data points that minimizes the sum of squared differences between the actual and predicted values of the dependent variable.

### Multiple Linear Regression

In **Multiple Linear Regression**, we extend the simple linear regression model to handle multiple features x1, x2, x3,...., xn. The model can predict the dependent variable using multiple independent variables simultaneously.

### Polynomial Regression

**Polynomial Regression** allows us to fit a non-linear model to the data by using polynomial features.


### Evaluation Metrics

The models are evaluated using two key metrics:

![image](https://github.com/user-attachments/assets/3b6e4078-5271-44b9-acb0-a8226ba211b5)


### Results

- **Simple Linear Regression**:
  - R²: 0.9889
  - MSE: 261.48

- **Multiple Linear Regression**:
  - R²: 0.9931
  - MSE: 125.32

- **Polynomial Regression**:
  - R²: 0.9944
  - MSE: 25.29


### How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook Regression.ipynb
   ```

### Dependencies

The following libraries are required to run the project:

- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`

You can install them using the following command:

```bash
pip install numpy pandas matplotlib scikit-learn
```
