# Support Vector Machine (SVM) Data Visualization and Preparation

This project demonstrates a data preparation and visualization pipeline using NumPy, Pandas, and Matplotlib to create a dataset for support vector machine (SVM) classification. The dataset consists of two classes, and each class is generated based on circular distributions with varying radii.

## Project Overview

This project creates a dataset with two classes for binary classification. The data points for each class are generated based on circular boundaries and are visualized using a scatter plot. The dataset is then organized into a Pandas DataFrame, suitable for training a Support Vector Machine (SVM) or similar classification model.

### Key Features
- Generates circular data for two classes.
- Combines and visualizes the data in a 2D plot.
- Prepares a structured dataset using Pandas for further analysis.

## Installation

To run this notebook, ensure you have the following libraries installed:
- `numpy`
- `pandas`
- `matplotlib`

Install these packages using pip if they are not already installed:
```bash
pip install numpy pandas matplotlib
```

## Usage

1. **Data Generation**:
   - Circular data is generated for two classes using `np.linspace` and `np.sqrt`. 
   - Each class has a different radius, with points evenly distributed along the circular boundary.

2. **Visualization**:
   - The data points for each class are visualized using `matplotlib.pyplot.scatter`.
   - This helps in understanding the separability and distribution of the two classes.

3. **Data Preparation**:
   - The data is organized into a Pandas DataFrame with three columns: `X1`, `X2`, and `Y`, where `X1` and `X2` represent coordinates and `Y` represents class labels (0 or 1).
   - The dataset is concatenated to form a single DataFrame, ready for machine learning applications.

## License

This project is licensed under the MIT License.
