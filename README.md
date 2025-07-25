🏠 Nashville Housing Data Analysis
This repository contains a comprehensive analysis and preprocessing pipeline for the Nashville housing dataset (2013–2016). The project aims to clean, transform, and balance the dataset for further modeling and analysis. Additionally, an exploratory data analysis (EDA) report is included for insights into the dataset's structure and features.

📁 Project Files
nashville_eda.ipynb: Python notebook for cleaning, preprocessing, and visualizing the Nashville housing dataset.
nashville_housing_report.html: Interactive HTML report generated using YData Profiling, providing an overview of the dataset's structure, missing values, correlations, and distributions.

🛠️ Features
Data Cleaning
Standardized column names.
Removed columns with >95% missing values.
Dropped constant columns and ID-like "Unnamed" columns.
Removed highly correlated columns to reduce redundancy.
Dropped rows missing critical fields (e.g., sale_price, year_built).
Imbalance Fixes
Grouped rare categories (e.g., property_city, tax_district, exterior_wall) into "Other".
Converted categorical fields (sold_as_vacant, multiple_parcels_involved_in_sale) into standardized formats.
Binned values for half_bath and transformed skewed features like acreage.
Transformations
Applied logarithmic and Box-Cox transformations to handle skewness in numerical features.
Reset index and removed duplicates for a clean final dataset.
Output
Cleaned dataset saved as nashville_model_ready_balanced.csv.
Exploratory Data Analysis (EDA)
Visualized transformations on skewed features.
Generated an interactive profiling report using YData Profiling.

🔧 Requirements
Python 3.7+
Required Libraries:
pandas
numpy
seaborn
matplotlib
sklearn
ydata-profiling
📊 Usage
Data Cleaning and Preprocessing
Open the nashville_eda.ipynb notebook in Jupyter or any Python IDE and execute the cells to clean and preprocess the dataset. The cleaned dataset will be saved as nashville_model_ready_balanced.csv.

EDA Report
Open the nashville_housing_report.html file in a browser to explore the dataset interactively.

📈 Visualizations
The notebook includes visualizations comparing original and transformed features, helping to assess the impact of cleaning and transformation steps.

🤝 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

📧 Contact
For questions or feedback, please reach out to:

Name: Bennie Sofiyea
Email: bsofiyea@icloud.com

✅ Project Status: Complete
