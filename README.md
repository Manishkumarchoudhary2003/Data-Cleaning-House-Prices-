# House Prices Data Cleaning Project

This project focuses on cleaning the "House Prices" dataset using various techniques in Python, particularly in Jupyter notebooks.
The dataset contains information about various attributes of houses and their corresponding prices.

## Objective

The main objective of this project is to preprocess the dataset to handle missing values and outliers effectively.
By doing so, we aim to prepare the data for further analysis or machine learning modeling.

## Techniques Used

1. **Data Exploration**: Initially, we explored the dataset to understand its structure, including the types of features and their distributions.

2. **Handling Missing Values**:
   - Imputation by Mean: For numerical features with missing values, we replaced them with the mean value of the respective feature.
   - Imputation by Median: Similar to mean imputation, but we used the median value instead.
   - Imputation by Mode: For categorical features, we filled missing values with the mode (most frequent value) of the respective feature.

3. **Handling Outliers**:
   - We identified outliers using visualizations and statistical methods such as box plots and z-scores.
   - Outliers were either removed from the dataset or transformed using techniques like winsorization to bring them within an acceptable range.

4. **Data Cleansing**:
   - We addressed other data quality issues such as duplicate records, inconsistent formatting, and irrelevant columns.
   - Rows or columns containing redundant or irrelevant information were removed from the dataset.

## Tools Used

- Python: for data cleaning and analysis.
- Jupyter Notebooks: for interactive data exploration and documentation.
- Pandas: for data manipulation and preprocessing.
- Matplotlib and Seaborn: for data visualization.
- Scikit-learn: for machine learning-related preprocessing tasks (if applicable).

## How to Use

1. Clone the repository to your local machine.
2. Open the Jupyter notebooks in your preferred environment (e.g., JupyterLab, Jupyter Notebook).
3. Execute the cells in each notebook sequentially to perform data cleaning steps.
4. Review the output and any notes or comments provided to understand the changes made to the dataset.
