# OIBSIP Data Analytics Internship

This repository contains my projects completed during the **Oasis Infobyte Data Analytics Internship**.

## Internship Track

**Data Analytics**

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Projects

## Task 1 — Exploratory Data Analysis on Retail Sales

**Folder:** `DataAnalytics-L1-EDARetailSales`

### Objective

Perform exploratory data analysis on retail sales data to understand sales
trends, customer demographics, product performance, and relationships between
numerical variables.

### Work Completed

- Loaded and inspected the retail sales dataset
- Performed descriptive statistics
- Calculated mean, median, mode, and standard deviation
- Analyzed monthly sales trends
- Analyzed quarterly sales trends
- Studied customer age groups
- Analyzed customer distribution by gender
- Identified top-performing product categories
- Analyzed revenue by product category
- Created correlation visualizations
- Identified important business insights
- Provided actionable business recommendations

### Tools

Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook

---

## Task 2 — Customer Segmentation

**Folder:** `CustomerSegmentation`

### Objective

Segment customers into groups based on their purchasing behavior using
RFM-style features and K-Means clustering.

### Work Completed

- Loaded and inspected customer transaction data
- Checked missing values and duplicate records
- Created customer-level features
- Calculated Recency
- Calculated Frequency
- Calculated Monetary value
- Calculated Average Purchase Amount
- Standardized numerical features
- Used the Elbow Method to determine the number of clusters
- Applied K-Means clustering
- Analyzed customer cluster profiles
- Visualized customer segments
- Identified marketing strategies for different customer groups

### Tools

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

---

## Task 3 — Cleaning Data

**Folder:** `DataCleaning`

### Objective

Clean and prepare the retail sales dataset for further analysis by identifying
data quality issues and applying appropriate data-cleaning techniques.

### Work Completed

- Inspected dataset structure
- Checked missing values
- Checked duplicate records
- Standardized column names
- Standardized categorical values
- Converted the Date column to datetime format
- Checked numerical data for potential outliers
- Used the IQR method for outlier detection
- Compared dataset information before and after cleaning
- Exported the cleaned dataset

### Result

The dataset contained:

- 1,000 rows
- 9 columns
- 0 missing values
- 0 duplicate rows
- 0 detected IQR outliers in the selected numerical variables

The cleaned dataset was saved as:

`cleaned_retail_sales_dataset.csv`

### Tools

Python, Pandas, NumPy, Jupyter Notebook

---

#  Key Learning Outcomes

Through these projects, I gained practical experience in:

- Data cleaning
- Exploratory data analysis
- Data visualization
- Customer segmentation
- Statistical analysis
- K-Means clustering
- Business insight generation
- Python-based data analytics
- Jupyter Notebook workflows

---

#  Repository Structure

```text
OIBSIP-Data-Analytics-Internship
│
├── CustomerSegmentation
│   ├── customer_segmentation.ipynb
│   └── retail_sales_dataset.csv
│
├── DataAnalytics-L1-EDARetailSales
│   ├── retail_sales_analysis.ipynb
│   └── retail_sales_dataset.csv
│
└── DataCleaning
    ├── data_cleaning.ipynb
    ├── retail_sales_dataset.csv
    └── cleaned_retail_sales_dataset.csv
