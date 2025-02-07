# Taxi-Out Data Analysis

This project analyzes the taxi-out time of flights using various machine learning models. The analysis is performed using a Jupyter Notebook (`taxi-out-analysis.ipynb`) and the dataset is stored in `../data/M1_final.csv`, downloaded from https://www.kaggle.com/datasets/deepankurk/flight-take-off-data-jfk-airport

## Project Structure

- `taxi-out-analysis.ipynb`: Jupyter Notebook containing the data analysis and model training.
- `../data/M1_final.csv`: CSV file containing the dataset.
- `../figures/`: Directory where generated figures are saved.

## Dependencies

The following Python libraries are required to run the notebook:

- numpy
- pandas
- matplotlib
- scikit-learn

## Analysis Steps

1. **Data Loading and Preprocessing**
    - Load the dataset.
    - Drop columns that are not useful for the analysis.
    - Check for missing values.

2. **Exploratory Data Analysis (EDA)**
    - Generate descriptive statistics.
    - Plot correlation matrix.
    - Visualise the distribution of data points for various features.

3. **Feature Selection**
    - Select relevant features for modeling.

4. **Model Training and Evaluation**
    - Split the data into training and testing sets.
    - Standardize the features.
    - Train and evaluate Linear Regression, Lasso Regression, and Ridge Regression models.
    - Evaluate models using R2, Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

5. **Specific Analysis**
    - Build and evaluate models for taxi-out time vs departure delay.
    - Build and evaluate models for taxi-out time vs wind speed.

## Results

The results of the analysis, including model performance metrics and visualizations, are saved in the `../figures/` directory.

## Usage

To run the analysis, open the `taxi-out-analysis.ipynb` notebook in Jupyter and execute the cells sequentially.