# 🍔 Food Delivery Data Analysis

# 📌 Project Overview

- This project focuses on analyzing food delivery data to understand customer ordering patterns, food category performance, city-wise order amounts, customer ratings, and delivery performance.
- It demonstrates an end-to-end Data Analytics workflow, including data cleaning, missing value treatment, exploratory data analysis (EDA), data visualization, and business insight generation using Python.
- The dataset contains missing values in selected columns, making data preprocessing an important part of this project.

# 🎯 Project Objectives

- Clean and preprocess the food delivery dataset
- Handle missing values using appropriate statistical methods
- Identify and remove duplicate records where required
- Convert the order date column to datetime format
- Perform Exploratory Data Analysis (EDA)
- Visualize data using Matplotlib and Seaborn
- Analyze order amounts, food categories, quantities, and customer ratings
- Generate useful business insights from the analysis

# 🛠️ Skills & Tools Used (ATS Optimized)

- Python
- NumPy
- Pandas
- Data Cleaning & Preprocessing
- Missing Value Treatment
- Exploratory Data Analysis (EDA)
- Data Visualization
- Matplotlib
- Seaborn
- Business Analytics

# 📂 Dataset Information

**Dataset Name:** Food Delivery Analytics Dataset  
**Rows:** 2,500  
**Columns:** 18  
**Target Variable:** `total_amount`

**Key Features:**

- **Order details:** `order_id`, `order_date`, `order_time`
- **Location and restaurant:** `city`, `restaurant_name`
- **Food details:** `category`, `item_name`, `quantity`
- **Order amount and discount:** `total_amount`, `discount_percent`, `delivery_fee`
- **Order and payment:** `payment_method`, `order_status`, `delivery_status`
- **Delivery performance:** `delivery_time_minutes`
- **Customer feedback:** `customer_rating`, `restaurant_rating`
- **Time feature:** `is_weekend`

# 🔍 Project Workflow

## 1️⃣ Data Loading & Understanding

- Loaded the dataset using Pandas
- Checked the dataset shape, column names, data types, and summary statistics
- Reviewed numerical and categorical features
- Identified columns containing missing values

## 2️⃣ Data Cleaning & Preprocessing

- Checked for missing values and duplicate records
- Removed duplicate records where required
- Converted `order_date` to datetime format
- Prepared the dataset for analysis

## 3️⃣ Missing Value Treatment

**Missing values were found in:**

1. `payment_method`
2. `delivery_time_minutes`
3. `customer_rating`
4. `restaurant_rating`

**Methods Used:**

- Median imputation for `delivery_time_minutes`
- Median imputation for `customer_rating`
- Median imputation for `restaurant_rating`
- Mode imputation for `payment_method`

## 4️⃣ Exploratory Data Analysis (EDA)

**EDA was performed using:**

1. Histograms
2. Bar plots
3. Scatter plots
4. Box plots
5. Correlation heatmaps

**Key Analysis Areas:**

1. Distribution of order amounts
2. Order amount by food category
3. Relationship between quantity and order amount
4. Distribution of customer ratings
5. Correlation among order amount, quantity, discount percentage, and delivery fee
6. Order amount variation across food categories
7. City-wise order amount analysis

## 5️⃣ Data Visualization

- Used Matplotlib and Seaborn to create visualizations
- Used a histogram to understand the distribution of order amounts
- Used a bar plot to compare order amounts across food categories
- Used a scatter plot to explore quantity and order amount
- Used a heatmap to view correlations among selected numerical columns
- Used a box plot to compare order amounts across categories

## 6️⃣ Segment-Wise Analysis

- Analyzed order amounts across food categories
- Compared order amounts across cities
- Examined order quantities and customer ratings
- Reviewed order and delivery status patterns

## 7️⃣ Data Visualization Summary

- The charts provide a visual summary of order amount distribution, category performance, customer ratings, and relationships between numerical variables.
- These visualizations help identify patterns that may be useful for food delivery business decisions.

# 📊 Key Insights

1. Most order amounts fall within the lower-to-middle price ranges in the dataset.
2. Pizza is identified as the leading food category in the notebook's category analysis.
3. Nashik has the highest summed order amount among the cities in the dataset.
4. Customer ratings are concentrated around 4 and 5 in the rating distribution.
5. The quantity-versus-order-amount scatter plot helps explore how ordered quantity relates to order amount.
6. Delivery time and customer ratings can be monitored to better understand delivery and customer experience.

# 📈 Business Recommendations

1. Review food category performance to understand which categories contribute strongly to order amounts.
2. Compare city-wise order amounts when planning local promotions and restaurant partnerships.
3. Monitor customer and restaurant ratings to identify areas for service improvement.
4. Review delivery time alongside customer ratings to investigate possible service issues.
5. Analyze discounts and delivery fees to understand their relationship with order amounts.
6. Continue checking missing values and duplicates to maintain data quality.

# ⚠️ Limitations & Assumptions

**Limitations:**

- Some columns contain missing values, and imputation can affect the results.
- The analysis is based on the available food delivery dataset for 2025.
- This project focuses on data analysis and visualization; it does not include predictive modeling.
- The category bar plot in the notebook uses Seaborn's default aggregation (mean) unless explicitly changed; therefore, its plotted result should not automatically be interpreted as total revenue.

**Assumptions:**

- `total_amount` is treated as the order amount for this analysis.
- The available records are assumed to be suitable for exploratory analysis after preprocessing.
- The insights describe patterns in this dataset and may not represent every food delivery business.

**Visualization:**

Q1. What Is the Distribution of Order Amounts?


