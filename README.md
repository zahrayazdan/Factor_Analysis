
# Factor Analysis Project

## Project Overview

This project demonstrates the application of Factor Analysis, a statistical method used to identify underlying relationships between variables in a dataset. By reducing the dimensionality of the data, Factor Analysis helps in uncovering hidden patterns and simplifying complex datasets.

## Project Structure

The repository contains the following files:
- `Factor_Analysis.ipynb`: Jupyter Notebook with data analysis and Factor Analysis implementation.
- `README.md`: Detailed explanation of the project and findings.

## Key Objectives

1. **Evaluate Data Suitability**: Assess the dataset using Bartlett’s Test of Sphericity and the Kaiser-Meyer-Olkin (KMO) Test.
2. **Perform Factor Analysis**: Extract key factors using the `FactorAnalyzer` library in Python.
3. **Interpret Results**: Analyze the factor loadings to understand the relationships between variables.

## Tools & Technologies

- **Python**: Data analysis and statistical modeling.
- **Pandas & NumPy**: Data manipulation and computations.
- **Matplotlib**: Visualization of factor loadings.
- **FactorAnalyzer**: Python library for performing factor analysis.

## Methodology

1. **Data Preparation**:
   - Load and clean the dataset.
   - Check for missing values and handle outliers.
   
2. **Suitability Testing**:
   - Conduct Bartlett’s Test of Sphericity to ensure the variables are correlated.
   - Perform the KMO Test to assess sampling adequacy.

3. **Factor Extraction**:
   - Use the `FactorAnalyzer` to determine the optimal number of factors.
   - Analyze factor loadings and interpret the results.

## Results & Insights

- The analysis identified significant factors that account for most of the variance in the dataset.
- Factors were interpreted based on loadings, providing insights into key underlying themes in the data.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/portfolio_projects.git
   ```
2. Navigate to the project directory:
   ```bash
   cd portfolio_projects
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Factor_Analysis.ipynb
   ```

## Conclusion

Factor Analysis is an effective technique for dimensionality reduction and helps in simplifying complex data by uncovering hidden patterns. This project showcases how to apply Factor Analysis using Python and interpret the results effectively.

