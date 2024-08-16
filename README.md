# Salaries by College Major - Data Analysis

## Overview

This project analyzes a dataset containing salary information by college major. The dataset includes starting median salaries, mid-career median salaries, and salary percentiles for various undergraduate majors. The project aims to explore the data, clean it, and extract meaningful insights regarding salary trends across different majors.

## Dataset

The dataset used in this project is titled `salaries_by_college_major.csv`. It contains the following columns:

- **Rank**: The ranking of the major based on starting median salary.
- **Undergraduate Major**: The name of the undergraduate major.
- **Group**: The category or field to which the major belongs.
- **Starting Median Salary**: The median salary for graduates right after completing their degree.
- **Mid-Career Median Salary**: The median salary for graduates with around 10 years of experience.
- **Mid-Career 10th Percentile Salary**: The 10th percentile salary for mid-career professionals.
- **Mid-Career 25th Percentile Salary**: The 25th percentile salary for mid-career professionals.
- **Mid-Career 75th Percentile Salary**: The 75th percentile salary for mid-career professionals.
- **Mid-Career 90th Percentile Salary**: The 90th percentile salary for mid-career professionals.

## Project Structure

### 1. Data Cleaning

- **Handling Missing Data**: Rows with missing values are dropped using `dropna()` to ensure the analysis is accurate.
- **Data Inspection**: The shape, columns, and a few rows of the dataset are inspected to understand its structure.

### 2. Data Analysis

- **Maximum and Minimum Salary Analysis**: 
  - Identify the major with the highest starting median salary.
  - Identify the major with the highest and lowest mid-career median salaries.
  - Determine the major with the lowest starting median salary.
- **Salary Spread Calculation**: 
  - Calculate the spread between the 90th and 10th percentile mid-career salaries.
  - Insert the calculated spread into the dataset for further analysis.
- **Sorting and Grouping**: 
  - Sort majors by the 90th percentile mid-career salary, salary spread, and mid-career median salary.
  - Group the dataset by major categories and calculate the mean salaries for each group.

### 3. Visualization and Interpretation

- **Salary Distribution**: Visualize the distribution of starting and mid-career salaries.
- **Spread Analysis**: Interpret the spread between high and low percentiles to understand salary volatility.

### 4. Summary of Findings

- **Top Majors by Salary**: Summary of majors with the highest starting and mid-career salaries.
- **Salary Stability**: Analysis of which majors have the most stable (small spread) and volatile (large spread) salaries.
- **Group Averages**: Comparison of average salaries across different fields of study.

## Results

- The major with the highest starting median salary was found to be **[Insert Major]**.
- **[Insert Major]** was identified as the major with the highest mid-career median salary.
- **[Insert Major]** had the lowest starting median salary.
- The major with the greatest salary spread between the 90th and 10th percentiles was **[Insert Major]**, indicating high salary variability.
- Group analysis revealed that **[Insert Group]** had the highest average starting and mid-career salaries.

## Installation and Usage

To run the analysis:

1. Ensure you have Python installed.
2. Install the required libraries using:
   ```bash
   pip install pandas
   ```
3. Clone this repository and navigate to the project directory.
4. Run the analysis script:
   ```bash
   python analysis.py
   ```

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any improvements or additional analyses.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to the creators of the `salaries_by_college_major.csv` dataset, which made this analysis possible.
