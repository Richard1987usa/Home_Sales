
# Analyzing Home Sales Data using PySpark and SQL

## Introduction

This project aims to extract valuable insights from home sales data by leveraging the power of PySpark and Spark SQL on the Google Colab platform. By utilizing these tools, we can efficiently process and analyze large datasets to answer key questions about home sales trends and patterns.

## Objectives

The main objectives of this project are:

1. Determine the average price of four-bedroom houses sold each year.
2. Calculate the average price of homes with three bedrooms and three bathrooms for each year they were built.
3. Find the average price of homes with three bedrooms, three bathrooms, two floors, and a size greater than or equal to 2,000 square feet for each year.
4. Identify the "view" rating for homes costing $350,000 or more.

## Methodology

To achieve these objectives, we employed the following techniques:

- Created temporary views using Spark to facilitate querying and data manipulation.
- Partitioned the data to optimize query performance and enable efficient data retrieval.
- Cached and uncached temporary tables to improve query execution speed and manage memory usage effectively.

## Key Findings

Through our analysis, we discovered the following insights:

1. The average price of four-bedroom houses varied significantly across different years, with notable trends and fluctuations.
2. Homes with three bedrooms and three bathrooms exhibited distinct price patterns based on the year they were built.
3. The average price of homes with specific characteristics (three bedrooms, three bathrooms, two floors, and a size of at least 2,000 square feet) showed interesting variations over time.
4. Homes costing $350,000 or more had different "view" ratings, indicating the relationship between price and the quality of the view.

## Conclusion

By leveraging PySpark and Spark SQL on Google Colab, we successfully analyzed home sales data and derived meaningful insights. The findings from this project can help stakeholders in the real estate industry make data-driven decisions, understand market trends, and identify factors influencing home prices. The use of temporary views, partitioning, caching, and uncaching techniques demonstrates the effectiveness of these tools in handling large datasets and optimizing query performance.
