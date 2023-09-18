# Exploratory Data Analysis (EDA) and Statistical Analysis in PySpark and Python

This README provides an overview of the Python script used for conducting Exploratory Data Analysis (EDA) and various statistical analyses, including factor analysis, correlation analysis, and linear regression. The script utilizes PySpark, Pandas, Matplotlib, FactorAnalyzer, Pingouin, Seaborn, Statsmodels, and Scipy libraries. I'm not using this in an academic level or for commercial purposes. These code are only to demonstrate programming technics and were all written by me (@diguitarrista).

## Requirements
Before running the script, make sure you have the following libraries installed:

- PySpark
- Pandas
- Matplotlib
- FactorAnalyzer
- Pingouin
- Seaborn
- Statsmodels
- Scipy

You can install these libraries using `pip`:

```bash
pip install pyspark pandas matplotlib factor-analyzer pingouin seaborn statsmodels scipy
```

## Usage
1. Import the necessary libraries at the beginning of your script:

```python
from pyspark.sql import SparkSession
from pyspark.sql.functions import *
import pandas as pd
import matplotlib.pyplot as plt
from factor_analyzer import FactorAnalyzer
from factor_analyzer.factor_analyzer import calculate_bartlett_sphericity
from factor_analyzer.factor_analyzer import calculate_kmo
import pingouin as pg
import seaborn as sns
import numpy as np
import statsmodels.api as sm
from statsmodels.iolib.summary2 import summary_col
from scipy.stats import pearsonr
from statsmodels.iolib.summary2 import summary_col
from scipy.stats import boxcox
from statstests.process import stepwise
```

2. Create a SparkSession to work with Spark DataFrames if necessary:

```python
spark = SparkSession.builder \
    .appName("YourAppName") \
    .getOrCreate()
```

3. Load your data into a Spark DataFrame using `spark.read.csv()` or any other suitable method.

4. Perform your EDA, data preprocessing, and statistical analyses using the imported libraries. Make sure to adapt the code to your specific dataset and research questions.

5. You can use Matplotlib, Seaborn, and other visualization libraries to create plots and graphs for data visualization.

6. When you're done with your analysis, you can either display the plots using `plt.show()` or save them to a file using `plt.savefig('plot.png')`.

7. Finally, you can run the script using a Python interpreter or an integrated development environment (IDE) like Jupyter Notebook.

## Note
This script is a template and should be adapted to your specific data and research requirements. Ensure that you customize the data loading, cleaning, and analysis steps as needed for your project.
