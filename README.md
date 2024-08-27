# Supermarket Customer Analysis
Final Exam Modul 2 - Data Analysis

## Project Overview

This project involves data cleaning and analysis of customer data from a supermarket to provide insights into customer behavior, spending patterns, and interactions with various products and promotions. The goal is to identify strategies that can help increase the profitability of the supermarket by focusing on customer behavior, expenditure, and their response to marketing campaigns.

## Files in This Repository

- **Data Cleaning (Supermarket).ipynb**: This Jupyter Notebook contains the data cleaning process applied to the original dataset. It includes handling missing values, creating new columns such as `Children`, `Total_Spending`, `Total_Purchases`, `Campaign Accepted`, and `Avg_spend`, and preparing the data for analysis.

- **Supermarket_Cleaning.csv**: This CSV file is the cleaned version of the dataset after applying the data cleaning process. It includes the original columns along with the new columns created during the cleaning process.

- **Data Analysis (Supermarket).ipynb**: This Jupyter Notebook contains various analyses performed on the cleaned dataset. The analyses focus on understanding customer behavior, spending patterns, and their interactions with products and promotions to derive actionable insights.

## Key Analyses

1. **Customer Behavior Analysis Based on Children**:
    - Analyzed how the number of children affects customer spending and purchase behavior.
    - **Insights**: Customers without children tend to spend more on average, suggesting a higher disposable income that can be targeted with premium or non-essential products.

2. **Total Spending and Total Purchases Analysis**:
    - Investigated the relationship between total spending and the frequency of purchases.
    - **Insights**: A positive correlation was found, indicating that customers who shop more frequently tend to spend more, highlighting the importance of encouraging repeat purchases.

3. **Campaign Acceptance Analysis**:
    - Analyzed customer response to various marketing campaigns.
    - **Insights**: Although most customers did not accept the campaigns, Campaign 4 was particularly effective in increasing average spending among those who participated. This suggests that successful elements of this campaign could be leveraged in future marketing strategies.

4. **Average Purchase Analysis**:
    - Examined the average number of purchases made by customers, segmented by marital status and number of children.
    - **Insights**: Married customers and those with more children tend to have higher average purchases, indicating that these segments may be more profitable and should be targeted with relevant marketing efforts.

## Conclusion

The analyses provide valuable insights into the behavior and preferences of supermarket customers. By focusing on specific customer segments and tailoring marketing campaigns accordingly, the supermarket can potentially increase its profitability.

## Recommendations

- **Target High-Spending Customers**: Focus on customers without children, who tend to have higher disposable income, by offering premium products and exclusive deals.
- **Optimize Campaign Strategies**: Replicate the successful elements of Campaign 4 in future marketing efforts and refine campaigns that did not perform well to increase overall acceptance rates.
- **Segmented Marketing**: Create personalized marketing strategies based on marital status and number of children, catering to the specific needs and preferences of each segment.

## How to Use

1. **Data Cleaning**: Run the `Data Cleaning (Supermarket).ipynb` notebook to see how the raw data was processed and cleaned.
2. **Analysis**: Explore the `Data Analysis (Supermarket).ipynb` notebook to understand the various analyses performed and the insights derived from the cleaned data.
3. **Data**: Use the `Supermarket_Cleaning.csv` file as a starting point for further analysis or machine learning models.

## Dependencies

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- seaborn
- matplotlib

Ensure you have these packages installed before running the notebooks.

## Author

This project was developed by [Your Name].

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
