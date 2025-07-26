# Retail Data Analysis Projects

This repository contains two end-to-end data analysis projects using real-world retail datasets. The goal is to demonstrate practical data science workflows, from data cleaning and visualization to machine learning, in retail and e-commerce contexts.

---

## Project 1: Amazon Bestsellers Analysis[Amazon1.ipynb](Amazon1.ipynb)


### Overview
This notebook analyzes Amazon's bestselling books dataset. It covers exploratory data analysis (EDA), feature engineering, data visualization, and predictive modeling for book popularity.

### Data Source
- **Dataset:** Amazon Best Sellers (sourced from Kaggle or public datasets)
- **Fields include:** Book name, author, user ratings, reviews, price, year, and genre.

### Main Steps

1. **Data Cleaning & Preparation**
    - Handling missing values and duplicates
    - Data type conversion (dates, numerics, categories)
    - Feature engineering: extracting useful features from text and dates

2. **Exploratory Data Analysis**
    - Descriptive statistics: average price, rating, review count by year/category
    - Trend analysis: changes in bestsellers over time
    - Correlation analysis between price, ratings, reviews, and bestseller status

3. **Visualization**
    - Top authors and genres visualization
    - Rating and review distributions
    - Price trends and outlier detection

4. **Machine Learning Modeling**
    - Defining the prediction target (e.g., whether a book becomes a bestseller)
    - Feature selection and preprocessing (encoding, scaling)
    - Training and evaluating classification models (e.g., logistic regression, random forest)
    - Model performance assessment (confusion matrix, ROC curve)

5. **Results & Insights**
    - Key factors that influence book sales on Amazon
    - Interpretation of model results and feature importances
    - Discussion of business implications and possible next steps

---

## Project 2: Brazilian Retail Data Analysis [Brazial_retail.ipynb](Brazial_retail.ipynb)

### Overview
This notebook examines transaction-level retail data from Brazil, providing insight into customer behavior, product trends, and business performance.

### Data Source
- **Dataset:** Brazilian retail transaction dataset (typically from Kaggle or open data sources)
- **Fields include:** Order ID, customer ID, product details, sales value, date, and geographic info.

### Main Steps

1. **Data Preprocessing**
    - Loading and inspecting raw data
    - Cleaning inconsistent entries, handling missing values
    - Creating date-related features (month, year, day of week)
    - Aggregating sales by product, customer, and time period

2. **Exploratory Data Analysis**
    - Sales volume and revenue analysis by product, region, and time
    - Customer segmentation: identifying top customers and purchase frequency
    - Analysis of seasonal trends and sales cycles

3. **Visualization**
    - Time series plots of sales/revenue
    - Bar charts of top-selling products and categories
    - Heatmaps and geographic distribution of sales

4. **Predictive Modeling (if included)**
    - Sales forecasting (time series or regression)
    - Customer churn or purchase prediction
    - Evaluation of model performance

5. **Results & Insights**
    - Key drivers of sales performance in the Brazilian retail sector
    - Business opportunities identified from data
    - Recommendations for further analysis or applications

---

## Datasets

**Note:**  
The datasets themselves are not included in this repository due to copyright and size restrictions.  
Please refer to the links or sources provided in each notebook to download the original data.

---

## Highlights

- **End-to-end Data Science Workflow:** From raw data cleaning to actionable insights.
- **Modern Visualization:** Clear, informative plots and dashboards to summarize complex data.
- **Hands-on Machine Learning:** Applied examples of real business problems.
- **Well-Commented Notebooks:** All steps are documented for learning and reproducibility.

---

## Contact

If you have any questions, suggestions, or want to collaborate, please open an issue or contact me at [your-email@example.com].

