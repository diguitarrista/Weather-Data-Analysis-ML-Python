# Data Analysis and Modeling with PySpark and Factor Analysis

This project demonstrates data analysis and modeling using PySpark, factor analysis, and various statistical and machine learning libraries. It provides an example of how to load, preprocess, and analyze a dataset, as well as how to perform factor analysis and other statistical tests. The script was written by @diguitarrista for demonstration purposes and is not intended for commercial or academic use.

```markdown
## Data Source

The dataset used in this project was obtained from the Instituto Nacional de Meteorologia (INMET), Brazil's National Institute of Meteorology. You can access historical weather data from the INMET website at the following link:

[INMET Historical Weather Data](https://portal.inmet.gov.br/dadoshistoricos)

## Getting Started

To get started with this project, you'll need to have Python and the required libraries installed. You can install the necessary libraries using the following commands:

```bash
pip install pyspark pandas matplotlib factor-analyzer pingouin seaborn statsmodels scikit-learn
```

## Project Structure

- `data/`: This directory contains the dataset(s) used in the project.
- `notebooks/`: Jupyter notebooks with detailed code examples and explanations.
- `README.md`: This file, providing an overview of the project.

## Usage

1. **Data Loading**: The project utilizes PySpark for loading and handling large datasets efficiently. Use the `SparkSession` object to read data.

2. **Data Preprocessing**: Explore data preprocessing techniques, such as cleaning, handling missing values, and encoding categorical variables using libraries like Pandas and Scikit-Learn.

3. **Factor Analysis**: Discover how to perform factor analysis using the `factor_analyzer` library. Calculate Bartlett's sphericity and the Kaiser-Meyer-Olkin (KMO) measure to assess data suitability.

4. **Statistical Tests**: Utilize `pingouin`, `statsmodels`, and `scipy` for various statistical tests, including Pearson correlations, model comparisons, and more.

5. **Visualization**: Visualize data and analysis results using Matplotlib and Seaborn for creating informative statistical plots.

## Notebooks

The `notebooks/` directory contains Jupyter notebooks with step-by-step code explanations and examples:

- `weather_linear_regression`: Data loading and preprocessing. Linear Regression, BoxCox
- `weather_pca`: Data loading and preprocessing. PCA

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or create a pull request.
