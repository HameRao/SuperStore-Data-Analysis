This project focuses on cleaning and analyzing the **Sample Superstore** dataset using Python. The goal was to preprocess raw data, identify and remove outliers, engineer useful features, and visualize trends to make the dataset analysis-ready for business insights or machine learning tasks.

Key Features

* Loaded and explored a real-world retail dataset (`SampleSuperstore.csv`)
* Handled missing values, data types, and duplicates
* Removed outliers in `Sales`, `Profit`, and `Discount` using IQR method
* Engineered a new feature: **Shipping Duration** (calculated from order and ship date)
* Created visualizations (barplots, boxplots) using Seaborn & Matplotlib
* Exported the cleaned dataset as `Cleaned_Superstore.csv`

Tools & Libraries Used:

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

Files Included:

* `superstore_data_cleaning.ipynb` – Main Jupyter Notebook
* `SampleSuperstore.csv` – Original dataset
* `Cleaned_Superstore.csv` – Final cleaned version of the dataset

Use Cases

This cleaned dataset is now suitable for:

* Business analysis and reporting
* Data visualization dashboards
* Machine learning model development
* Sales and shipping time optimization
