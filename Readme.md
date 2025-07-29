# Retail Data Analysis Projects

This repository contains two end-to-end data analysis projects using real-world retail datasets. The goal is to demonstrate practical data science workflows, from data cleaning and visualization to machine learning, in retail and e-commerce contexts.

---

## Project 1: Amazon Bestsellers Analysis [Click here](02_amazon_bestseller.ipynb)


### Overview
This notebook analyzes Amazon's bestselling books dataset. It covers exploratory data analysis (EDA), feature engineering, data visualization, and predictive modeling for book popularity.
[Click here for SQL-Based Amazon Bestseller Analysis](Amazon_best_selling_SQL.ipynb)
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

## Project 2: Brazilian Retail Data Analysis [Click here](01_Brazial_retail.ipynb)

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

## Project 3: UK Online Retail Analysis [Click here](03_UK_retail_analysis.ipynb)

### Overview
This notebook analyzes transactional data from a UK-based online retailer, demonstrating a complete workflow from data loading and cleaning to advanced customer segmentation and product association analysis.

[Click here for SQL-Based UK Retail Analysis](UK_retail_SQL.ipynb)

### Data Source
- **Dataset:** Online Retail Dataset (UCI Machine Learning Repository / Kaggle)
- **Fields include:** Invoice number, product code and description, quantity, unit price, customer ID, country, date and time of purchase.

### Main Steps

1. **Data Loading and Cleaning**
    - Imported core libraries (pandas, numpy)
    - Loaded the dataset from CSV with the appropriate encoding
    - Removed duplicate rows and filtered out invalid records (non-positive quantity or unit price)
    - Dropped rows with missing CustomerID (required for customer-level analysis)
    - Converted `InvoiceDate` to datetime format for temporal analysis
    - After cleaning, retained 541,909 valid transactions with complete and reliable fields

2. **Exploratory Data Analysis**
    - Calculated descriptive statistics: number of unique products, customers, and top countries
    - Assessed the time coverage of the data
    - Visualized monthly sales trends to identify seasonality and business growth patterns

3. **RFM Analysis and Customer Segmentation**
    - Computed Recency, Frequency, and Monetary (RFM) metrics for each customer
    - Segmented customers into groups based on quartiles for each metric
    - Generated RFM scores for targeted marketing and customer value assessment
    - Applied KMeans clustering to RFM features to reveal key customer segments

4. **Market Basket Analysis**
    - Transformed transaction data into basket format
    - Used the Apriori algorithm and association rules to uncover frequently co-purchased products
    - Identified actionable product bundles and cross-selling opportunities

5. **Results & Insights**
    - Revealed strong seasonal sales effects and key sales periods
    - Distinguished between high-value, loyal customers and less active segments
    - Highlighted product pairs with high lift for promotional campaigns

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

If you have any questions, suggestions, or want to collaborate, please open an issue or contact me at rgao4@tulane.edu

