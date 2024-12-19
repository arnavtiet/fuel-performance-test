

# Fuel Cell Performance Prediction with PyCaret

This project uses the PyCaret library to predict fuel cell performance based on a dataset. The dataset is in CSV format and contains various features that affect fuel cell performance.

## Overview

In this project, different regression models are tested using the PyCaret library. After testing the models, a detailed report is generated, showing the performance and comparison of each model.

## Project Features

- **Dataset:** Fuel cell performance data in CSV format.
- **PyCaret:** Used for automatic preprocessing, model training, and comparison of different regression models.
- **Detailed Report:** After training, a detailed report is displayed showing metrics like RMSE, R-squared, MAE, etc., for each model tested.

## Requirements

Before running the code, ensure you have the following installed:

- Python 3.x
- PyCaret
- Pandas
- Scikit-learn

You can install the required libraries using pip:

```bash
pip install pycaret pandas scikit-learn
```
## How to Run
- Upload the Dataset: Make sure you have the CSV file containing the fuel cell performance data.

- Load the Data: In the code, load your CSV dataset using PyCaret.

- Run the Regression Models: The script will automatically train and test multiple regression models.
- Generate the Report: After running the models, a detailed report will be shown, comparing all the models.

## Project Structure
- Fuel_cell_performance_data-Full.csv
- Fuel-performance-tester.ipynb    
- README.md                 

## Conclusion
This project helps in analyzing and predicting fuel cell performance using various regression models. The comparison report will guide you in choosing the best model for the task.

