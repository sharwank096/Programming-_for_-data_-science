
# Project Title: Air Quality Analysis

## Introduction
This project involves analyzing air quality data to explore pollution levels across various cities and states. The goal is to clean, visualize, and perform statistical analyses on the dataset to draw meaningful insights about air pollution patterns.

## Dataset Description
The dataset contains the following key features:
- **pollutant_min**: Minimum pollutant level.
- **pollutant_max**: Maximum pollutant level.
- **pollutant_avg**: Average pollutant level.
- **last_update**: Timestamp of the last update.
- **city**: City where the data was collected.
- **state**: State where the data was collected.

## Installation Instructions
1. **Clone the Repository**: Use `git clone` to clone the repository.
2. **Install Python and Required Libraries**:
   Ensure the following Python libraries are installed:
   - `pandas`
   - `numpy`
   - `seaborn`
   - `matplotlib`
   - `scipy`

   You can install the required libraries using:
   ```bash
   pip install pandas numpy seaborn matplotlib scipy
   ```

## Usage
1. **Load the Dataset**: The data is loaded from a CSV file located in Google Drive.
2. **Data Cleaning**: Missing values are handled, and necessary columns are converted to appropriate data types.
3. **Exploratory Data Analysis**:
   - Generate summary statistics.
   - Visualize data distributions.
   - Perform statistical tests.
4. **Save Results**: Summary statistics and cleaned data are saved as CSV and Excel files.

## Summary of Analyses
- **Data Cleaning**: Rows with missing values in key columns were removed, and the `last_update` column was converted to a datetime format.
- **Summary Statistics**: Descriptive statistics were computed for numerical columns to understand the central tendency and dispersion of pollutant levels.
- **Visualizations**:
  - Distribution histograms of pollutant averages.
  - Scatter plots for pollutant minimum vs. maximum values.
- **Statistical Tests**:
  - T-tests were conducted to compare pollutant levels between different states.
  - Chi-square tests were used to explore the relationship between categorical variables.

## Results
- **Insights**: The analysis revealed patterns and anomalies in pollution levels across various cities and states.
- **Statistical Findings**: The T-test and Chi-square test provided insights into the statistical significance of differences in pollutant levels and relationships between variables.
