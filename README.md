# Diwali Sales Data Analysis

## Overview
This project analyzes sales data during the Diwali season using Python libraries like Pandas, NumPy, Matplotlib, and Seaborn. Key insights include sales trends, gender-wise spending, and age group preferences.

## Dataset
The dataset contains 11,251 entries and 15 columns, including customer demographics, product details, and purchase amounts.

## Steps and Analysis
1. **Data Cleaning**:
   - Dropped unused columns: `Status` and `unnamed1`.
   - Handled missing values in the `Amount` column by removing null rows.
   - Converted the `Amount` column to integer type.

2. **Exploratory Data Analysis (EDA)**:
   - Gender-wise sales and spending.
   - Age group preferences and spending.
   - State-wise sales and top contributors.
   - Marital status impact on sales by gender.
   - Occupation-based sales analysis.

3. **Visualizations**:
   - Bar plots and count plots for categorical distributions and aggregated data insights.

## Key Findings
- **Gender Analysis**:
  - Female customers spent significantly more than male customers.
- **Age Group Analysis**:
  - The 26–35 age group had the highest purchases and spending.
- **State Analysis**:
  - Uttar Pradesh, Maharashtra, and Karnataka showed maximum sales and spending.
- **Marital Status**:
  - Married individuals contributed significantly to sales, with notable differences by gender.
- **Occupation**:
  - Certain occupations showed higher spending trends.

## Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

## Visualizations
- Gender-wise sales comparison using count and bar plots.
- Age group-wise spending trends.
- Top states by orders and amount spent.
- Impact of marital status and gender on sales.
- Occupation-wise sales trends.

## Usage
1. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
2. Load the dataset:
   ```python
   df = pd.read_csv('path_to_file.csv', encoding='unicode_escape')
   ```
3. Execute the analysis steps to reproduce results.

## Insights
The analysis highlights key customer segments and states contributing to sales during Diwali, providing actionable insights for targeted marketing strategies.

