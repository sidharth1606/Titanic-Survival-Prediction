# Titanic Survival Prediction

This project provides a comprehensive machine learning solution for predicting Titanic passenger survival using Python and Jupyter Notebook.

## Overview

The analysis covers the complete machine learning pipeline:
1. Data loading and exploration
2. Data cleaning and preprocessing
3. Feature engineering
4. Exploratory data analysis (EDA) with visualizations
5. Machine learning model building and evaluation
6. Prediction on test data and submission file generation

## Files

- `titanic_analysis.ipynb`: Main Jupyter notebook containing the complete analysis
- `titanic_analysis.py`: Original Python script (converted to notebook)
- `train.csv`: Training dataset
- `test.csv`: Test dataset for predictions
- `gender_submission.csv`: Sample submission format
- `requirements.txt`: Python dependencies
- `titanic_submission.csv`: Generated predictions (after running the notebook)
- `survival_by_gender.png`: Visualization of survival rates by gender
- `survival_by_class.png`: Visualization of survival rates by passenger class
- `age_distribution.png`: Age distribution histogram by survival status

## Dependencies

Install the required packages using:
```
pip install -r requirements.txt
```

Required packages:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage

1. Ensure all data files (`train.csv`, `test.csv`, `gender_submission.csv`) are in the same directory
2. Open `titanic_analysis.ipynb` in Jupyter Notebook or JupyterLab
3. Run the cells sequentially to execute the analysis
4. The notebook will generate visualizations and a submission file

## Models Used

- Random Forest Classifier
- Logistic Regression

The best performing model is selected based on validation accuracy and used for final predictions.

## Results

After running the notebook, you'll get:
- Survival rate statistics
- Visualizations saved as PNG files
- A submission file `titanic_submission.csv` ready for Kaggle submission

## License

This project is for educational purposes.
