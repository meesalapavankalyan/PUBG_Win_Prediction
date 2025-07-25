# PUBG_Win_Prediction
# PUBG Win Prediction Analysis

This repository contains a Jupyter Notebook (Game_pubg_winpred.ipynb) that analyzes PUBG (PlayerUnknown's Battlegrounds) game data to predict player win percentages based on various in-game statistics.

## Overview

The notebook performs the following analysis:

1. *Data Loading & Exploration*: Loads a large dataset of PUBG match statistics (4.4M+ records) and explores the data structure.

2. *Data Cleaning & Preprocessing*:
   - Drops duplicate records
   - Handles missing values
   - Removes irrelevant ID columns
   - Encodes categorical variables (like matchType)
   - Converts all columns to numeric format

3. *Feature Engineering*: Prepares the data for machine learning by selecting relevant features and the target variable (winPlacePerc).

4. *Machine Learning Models*: Implements several regression models to predict win percentage:
   - Linear Regression
   - Decision Tree Regressor
   - K-Nearest Neighbors Regressor
   - Ridge Regression
   - Random Forest Regressor

5. *Model Evaluation*: Uses metrics like Mean Absolute Error (MAE) and R-squared (R2) to evaluate model performance.

## Key Features

- Large-scale analysis of PUBG gameplay data
- Comprehensive data cleaning pipeline
- Multiple machine learning approaches compared
- Feature importance analysis
- Visualization of key relationships

## Requirements

To run this notebook, you'll need:

- Python 3.6+
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Usage

1. Clone the repository
2. Install required packages (pip install -r requirements.txt)
3. Run the Jupyter Notebook
4. The dataset (pubg.csv) should be in the same directory

## Results

The notebook demonstrates how different machine learning models perform at predicting PUBG win percentages based on in-game statistics like:
- Damage dealt
- Distance traveled
- Number of kills
- Healing items used
- Match duration
- And many other gameplay features

## Future Work

Potential improvements:
- Feature selection optimization
- Hyperparameter tuning
- Neural network approaches
- Real-time prediction integration

## License

This project is open source and available under the [MIT License](LICENSE).
