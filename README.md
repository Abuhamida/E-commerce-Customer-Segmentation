# E-commerce Customer Segmentation Analysis

## Project Overview
This project analyzes e-commerce customer data to segment customers based on their behavior and characteristics. The analysis includes exploratory data analysis (EDA) and K-means clustering to identify distinct customer groups.

## Data Sources
The data is sourced from an Excel file named 'E-commerce_data.xlsx' containing multiple sheets:
- customers
- genders
- cities
- transactions
- branches
- merchants

## Analysis Steps

### 1. Data Preparation
- Merged multiple dataframes to create a comprehensive dataset
- Handled missing values
- Created a binary 'coupon_burnt' column

### 2. Exploratory Data Analysis (EDA)
Several visualizations were created to understand the data distribution:

![Gender Distribution](images/gender_distribution.png)
*Gender distribution of customers*

![City Distribution](images/city_distribution.png)
*Distribution of customers across cities*

![Coupon Transaction Status](images/coupon_status.png)
*Distribution of coupon burn status*

![Coupon Burns Over Time](images/burns_over_time.png)
*Trend of coupon burns over time*

![Coupon Usage Frequency](images/usage_frequency.png)
*Frequency of coupon usage by customers*

![Coupon Burn Rate](images/burn_rate.png)
*Distribution of coupon burn rates across customers*

### 3. Customer Segmentation
- Used K-means clustering algorithm
- Determined optimal number of clusters using elbow method and silhouette score
- Visualized clusters

![Elbow Method](images/elbow_method.png)
*Elbow method for determining optimal number of clusters*

![Silhouette Score](images/silhouette_score.png)
*Silhouette score for different numbers of clusters*

![Customer Clusters](images/customer_clusters.png)
*Visualization of customer clusters*

## Results
The analysis identified 2 distinct customer segments based on their behavior and characteristics. Further investigation into these segments can provide insights for targeted marketing strategies and personalized customer experiences.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Future Work
- Deeper analysis of cluster characteristics
- Predictive modeling for customer behavior
- Implementation of recommendations based on segmentation