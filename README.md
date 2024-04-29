# Predicting-the-probability-of-default-in-credit-scoring
# Final EDA-J Component

This Python code performs Exploratory Data Analysis (EDA) and builds a predictive model for credit scoring using various machine learning algorithms. The code is designed to work with a dataset containing information about individuals and their credit history.

## Prerequisites

Before running the code, ensure that you have the following libraries installed:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotnine
- Scikit-learn

You can install these libraries using pip:
## Dataset

The code expects two CSV files:

1. `cs-training.csv`: This file contains the training data for the model.
2. `cs-test.csv`: This file contains the test data for making predictions.

Make sure to update the file paths in the code to match the location of your CSV files.

## Code Structure

The code is divided into the following sections:

1. **Importing Libraries**: The necessary libraries are imported at the beginning of the code.
2. **Data Preprocessing**: The training data is loaded, and various preprocessing steps are performed, such as handling missing values, dropping irrelevant rows, and converting data types.
3. **Exploratory Data Analysis (EDA)**: The code performs EDA by visualizing the relationships between different features and the target variable using scatter plots, bar plots, and correlation heatmaps.
4. **Feature Selection**: The code uses Correlation-based Feature Selection (CFS) and t-tests to identify the most relevant features for predicting the target variable.
5. **Model Selection**: Multiple classification algorithms are evaluated using K-fold cross-validation, and their performance is compared based on accuracy scores.
6. **Model Training and Testing**: The Random Forest Classifier algorithm is selected based on its performance, and the model is trained on the training data. The trained model is then used to make predictions on the test data.
7. **Probability Calculation**: The code calculates the probability of default for the test data and saves it to a new CSV file named `results.csv`.

## Usage

1. Ensure that you have the required CSV files (`cs-training.csv` and `cs-test.csv`) in the correct location.
2. Run the Python script.
3. The script will perform EDA, model selection, training, and testing.
4. The predictions and probability of default for the test data will be saved in the `results.csv` file.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

