# NYC Taxi & Limousine Commission Data Analysis

## Overview

This project was completed as part of my scholarship in the Data Science program at the Artificial Intelligence and Technology Academy. It was undertaken within the scope of the "Get Started with Python" chapter of the Google Advanced Data Analytics course. The project involves analyzing the 2017 Yellow Taxi Trip Data provided by the New York City Taxi & Limousine Commission (TLC). The aim is to clean, explore, and analyze the dataset to derive meaningful insights that can support predictive modeling and inform future data-driven solutions.

## Project Objective

The objective of this project is to:
1. Inspect and clean the provided dataset.
2. Identify key variables and assess data quality.
3. Prepare the data for future exploratory analysis (EDA) and predictive modeling.
4. Extract actionable insights for potential improvements and solutions based on the dataset.

## Dataset

The dataset, `2017_Yellow_Taxi_Trip_Data.csv`, contains information about taxi trips in New York City for the year 2017. The variables in the dataset include trip information such as the distance, total amount, payment type, vendor ID, and other key attributes. This dataset is essential for building a predictive model to enhance the understanding of taxi trips in NYC.

## Structure

- `data/`: Folder containing the raw data files.
- `notebooks/`: Folder containing Jupyter notebooks with the code for data inspection, cleaning, and analysis.
- `README.md`: This file.

## Installation

To get started, clone this repository to your local machine:
git clone https://github.com/yourusername/nyc-taxi-data-analysis.git


Make sure to have the following dependencies installed:
pip install pandas numpy matplotlib seaborn scikit-learn

## How to Use

1. **Data Loading**: Load the dataset using the following Python code:
    ```python
    import pandas as pd
    df = pd.read_csv('data/2017_Yellow_Taxi_Trip_Data.csv')
    ```
2. **Data Cleaning**: Clean the data by handling missing values, outliers, and irrelevant columns.
3. **Exploratory Data Analysis (EDA)**: Use visualizations and summary statistics to explore data patterns.
4. **Model Building**: Use the cleaned data to build predictive models.

## Results

The analysis led to identifying key variables such as `trip_distance`, `total_amount`, and `payment_type` that are significant for predictive modeling. In addition, we explored data quality, including missing values and outliers, and performed a detailed analysis of payment types and vendor statistics.

## Next Steps

- Clean the data further by handling missing values and outliers.
- Conduct exploratory data analysis (EDA) to identify relationships between key variables.
- Build a predictive model using machine learning algorithms such as regression or classification.
- Visualize results to gain deeper insights into taxi trip data.

## Contributing

Feel free to fork this repository and submit pull requests for improvements. Contributions to enhance the analysis, suggest new ideas, or fix issues are always welcome.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

