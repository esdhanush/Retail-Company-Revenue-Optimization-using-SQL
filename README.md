# Online Sports Retail Company Revenue Optimization

![Logo](https://netivist.org/uploads/forum/discussions/pictures/55929be755f4f71bac7e9ee8/nike-vs-adidas-xl.jpg)

## Project Overview

This project focuses on analyzing product data for an online sports retail company to optimize revenue. The analysis leverages various data points, including pricing, revenue, ratings, reviews, product descriptions, and website traffic, to produce actionable recommendations for the marketing and sales teams.

## Objectives

- **Improve Revenue**: Identify strategies to enhance revenue based on product performance and pricing strategies.
- **Optimize Marketing**: Provide recommendations to boost marketing effectiveness based on data-driven insights.
- **Enhance Sales**: Develop actionable insights to improve sales performance across different product categories.

## Data Overview

The analysis utilizes the following tables from the `sports` database:

1. `info` - Contains product information such as descriptions and product IDs.
2. `finance` - Includes pricing, revenue, and discount data.
3. `brands` - Lists brand information and product IDs.
4. `reviews` - Holds product ratings and reviews.
5. `traffic` - Provides website traffic data, including last visit timestamps.

## SQL Functions Used

- **Aggregate Functions**: `SUM`, `AVG`, `COUNT`
- **Date Functions**: `DATE_PART`
- **Join Functions**: `JOIN`
- **Union Functions**: `UNION`
- **CTE (Common Table Expression)**: `WITH`
- **Subqueries**: Nested `SELECT` statements
- **Window Functions**: `RANK()`, `PERCENTILE_DISC()`

## Analysis & Insights

1. **Counting Missing Values**: Identified columns with significant missing data and their impact.
2. **Nike vs Adidas Pricing**: Compared pricing strategies between Nike and Adidas.
3. **Labeling Price Ranges**: Categorized products by price range and analyzed revenue.
4. **Average Discount by Brand**: Evaluated discount strategies across brands.
5. **Correlation Between Revenue and Reviews**: Assessed the impact of reviews on revenue.
6. **Ratings and Reviews by Product Description Length**: Examined if description length influences ratings and reviews.
7. **Reviews by Month and Brand**: Analyzed review trends throughout the year.
8. **Top Revenue Generated Products**: Identified top revenue products and their performance.
9. **Footwear Product Performance**: Analyzed footwear performance compared to other products.
10. **Clothing Product Performance**: Compared clothing products' performance with footwear.

## Recommendations

1. **Increase Focus on High-Revenue Products**: Develop more "Expensive" and "Elite" products, particularly from Adidas.
2. **Optimize Discounts**: Adjust discount strategies to balance sales and revenue.
3. **Boost Customer Reviews**: Implement strategies to increase review volumes.
4. **Review and Adjust Pricing Strategy**: Continuously optimize pricing based on product performance.
5. **Address Missing Data**: Resolve issues related to missing values in traffic data.
6. **Balance Review Collection**: Increase review collection outside the first quarter.
7. **Enhance Product Descriptions**: Improve product descriptions for better customer engagement.
8. **Monitor and Adjust Strategies**: Regularly evaluate and adjust strategies based on data.

## Getting Started

To run this analysis, ensure you have access to the `sports` database with the required tables. You will need SQL tools or a database client to execute the provided queries and analyze the results.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Your Data Sources]
- [Any libraries, tools, or people who helped]

For further details, please refer to the [project documentation](docs).

