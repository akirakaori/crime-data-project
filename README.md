# Crime Data Analysis and Victim Gender Prediction

This project analyzes the **Crime_Data_from_2020_to_Present.csv** dataset and builds machine learning models to explore patterns in crime incidents and predict victim gender from crime-related features.

The notebook combines exploratory data analysis, feature engineering, model training, and model comparison in a single workflow. It is designed to show both analytical thinking and practical machine learning implementation.

## Project Highlights

- Exploratory data analysis on crime trends, victim demographics, crime types, and location patterns.
- Visualizations for gender distribution, victim age, hourly crime patterns, area-level crime counts, correlation structure, and year-wise trends.
- Feature engineering from date, time, location, and categorical crime attributes.
- Comparison of multiple classification models:
  - Logistic Regression
  - Random Forest
  - XGBoost
  - Neural Network (MLP)
- Model evaluation using accuracy, precision, recall, F1-score, confusion matrices, and ROC curves.
- Feature importance and coefficient analysis for interpretation.

## Repository Contents

- `Ashika_Kambang final.ipynb` - Main analysis notebook.
- `Crime_Data_from_2020_to_Present.csv` - Input dataset expected by the notebook.
- Generated figures such as:
  - `victim_gender_distribution.png`
  - `yearwise_crime_trend_by_gender.png`
  - `correlation_heatmap.png`
  - `model_performance_comparison.png`
  - `model_comparison_all_metrics.png`

## What The Notebook Does

1. Loads and inspects the crime dataset.
2. Performs EDA to understand distributions, missingness, and relationships between variables.
3. Cleans and encodes categorical and numerical features.
4. Splits the data into train and test sets.
5. Trains and evaluates several classification models.
6. Compares the models visually and prints classification reports.
7. Demonstrates a sample prediction workflow for unseen data.

## Requirements

- Python 3.10+ recommended
- Jupyter Notebook or VS Code Notebook support

### Python Packages

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost jupyter
```

## How To Run

1. Open the project folder in VS Code or Jupyter.
2. Make sure the CSV dataset is in the same directory as the notebook.
3. Install the required Python packages.
4. Open `Ashika_Kambang final.ipynb` and run the cells from top to bottom.

## Notes

- The notebook expects the dataset file to be named exactly `Crime_Data_from_2020_to_Present.csv`.
- Several plots are saved to disk when the notebook runs, which makes it easy to reuse them in a report or presentation.
- Some model cells perform heavier computation, especially the tuned Random Forest and XGBoost sections.

## Recruiter-Friendly Summary

This project demonstrates end-to-end data analysis skills: data cleaning, visualization, feature engineering, model building, evaluation, and interpretation. It is a strong example of turning raw public data into a structured machine learning workflow.
