## Random Forest Regressor Model Evaluation

This repository contains code for training a Random Forest Regressor model on the diabetes dataset and evaluating its performance along with other regression models.

### Setup Instructions
1. Clone the repository:

   ```
   git clone <repository-url>
   ```

2. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

### Usage Instructions

1. Run the `random_forest_regressor.py` script to train the Random Forest Regressor model and evaluate its performance against other regression models.

   ```
   python random_forest_regressor.py
   ```

### Contents

- **random_forest_regressor.py**: Python script containing the code for training the Random Forest Regressor model and evaluating its performance.
- **README.md**: This file, providing an overview of the repository and instructions for usage.

### File Descriptions

- **random_forest_regressor.py**: This script loads the diabetes dataset, performs data preprocessing, trains a Random Forest Regressor model using hyperparameter tuning, evaluates its performance, compares it with other regression models, and visualizes feature importances.

### Dependencies

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`
