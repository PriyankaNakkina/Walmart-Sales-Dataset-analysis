# Walmart-Sales-Dataset-analysis

Exploring Customer Behavior and Sales Trends

This project delves into the Walmart Sales Dataset, analyzing customer behavior, sales trends, and product categories to gain insights into the retail giant's operations. Using Python, Pandas, NumPy, Matplotlib, and Seaborn, I extracted valuable information from the dataset, visualized key findings, and identified patterns that can inform business decisions.

Key Features:

    Data Preprocessing: Cleaned and preprocessed the dataset to ensure accuracy and consistency.
    Exploratory Data Analysis: Used statistical methods and data visualization techniques to uncover trends, patterns, and correlations.
    Customer Segmentation: Identified distinct customer segments based on demographics, behavior, and purchase history.
    Sales Trend Analysis: Analyzed sales data to identify seasonal fluctuations, product category performance, and regional differences.
    Product Category Analysis: Examined product categories to determine top-selling products, customer preferences, and opportunities for growth.

Technologies Used:

    Python
    Pandas
    NumPy
    Matplotlib
    Seaborn
    Jupyter Notebook

Data Preprocessing

The project began with data preprocessing, where we:

    Imported the dataset: We imported the Walmart sales dataset into a Pandas DataFrame using the pd.read_csv() function.
    Handled missing values: We checked for missing values in the dataset using the df.isnull().sum() function and found that there were no missing values.
    Converted data types: We converted the Age column from a categorical variable to a numerical variable using a dictionary mapping.
    Encoded categorical variables: We used One-Hot Encoding (OHE) to encode the categorical variables City_Category, Occupation, and Product_Category into numerical variables.

Exploratory Data Analysis

Next, we performed exploratory data analysis to understand the distribution of the data and identify patterns and trends. We:

    Visualized the data: We used Matplotlib and Seaborn to create visualizations of the data, including histograms, bar plots, and scatter plots.
    Calculated summary statistics: We calculated summary statistics such as mean, median, and standard deviation for the numerical variables.
    Identified correlations: We used the corr() function to identify correlations between the numerical variables.

Customer Segmentation

We performed customer segmentation to identify distinct customer segments based on demographics, behavior, and purchase history. We:

    Created a customer segmentation DataFrame: We created a new DataFrame that included the customer ID, age, occupation, and purchase amount.
    Used K-Means clustering: We used K-Means clustering to segment the customers into distinct clusters based on their demographics and behavior.

Sales Trend Analysis

We analyzed the sales data to identify seasonal fluctuations, product category performance, and regional differences. We:

    Visualized sales trends: We used Matplotlib and Seaborn to create visualizations of the sales data, including line plots and bar plots.
    Identified seasonal fluctuations: We used the seasonal_decompose() function to identify seasonal fluctuations in the sales data.
    Analyzed product category performance: We used the groupby() function to analyze the performance of different product categories.

Product Category Analysis

We examined the product categories to determine top-selling products, customer preferences, and opportunities for growth. We:

    Visualized product category performance: We used Matplotlib and Seaborn to create visualizations of the product category performance, including bar plots and scatter plots.
    Identified top-selling products: We used the sort_values() function to identify the top-selling products in each product category.
    Analyzed customer preferences: We used the groupby() function to analyze customer preferences for different product categories.

Conclusion

The Walmart Sales Dataset Analysis project provided valuable insights into customer behavior, sales trends, and product categories. The project demonstrated the importance of data preprocessing, exploratory data analysis, and data visualization in understanding complex datasets. The findings of the project can be used to inform business decisions and drive growth in the retail sector.
