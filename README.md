# Retail Sales Data Analysis

## Introduction

I analyzed sales data from 45 retail stores to find out what affects their sales. The data covers weekly sales, store details, promotions, holidays, and external factors like fuel prices, unemployment rates, and temperature.

**Data Source**: [Retail Dataset on Kaggle](https://www.kaggle.com/datasets/manjeetsingh/retaildataset)

**The dataset includes three main parts**:

- **Stores**: Information about each store's type and size.
- **Features**: Details on promotions and external factors.
- **Sales**: Weekly sales records for each store and department, indicating holidays.

## Objectives

- Understand how markdown promotions impact sales.
- Evaluate the influence of holidays like the Super Bowl, Labor Day, Thanksgiving, and Christmas.
- Determine how store size, markdowns, and other factors relate to sales performance.

## Key Findings

### 1. External Factors Have Low Impact

- **CPI**, **Unemployment**, **Fuel Prices**, and **Temperature** have little to no correlation about 0 with sales and dosen't show any parttern between them and sales.
- These factors don't significantly affect sales in our dataset.



![CPI ,Unemployment, Fuel Prices, Temperature plot](https://github.com/user-attachments/assets/62cb35f7-17db-4a66-9635-acef130357fc)


### 2. Promotions and Holidays Boost Sales

- **Markdowns** (promotional discounts) have a moderate to high positive effect on sales, especially during holidays.

  - **Store A**:
    - During holidays, the correlation between markdowns and sales ranges from 0.565 to 0.889.
  - **Store B**:
    - Similar correlations ranging from 0.556 to 0.700.
  - **Store C**:
    - Markdowns have little or no effect, with correlations around -0.076.
    - Promotions aren't effective for this store type.

### 3. Different Sales Patterns by Store Type

- **Stores A and B**:
  - Share similar sales trends.
  - Markdowns significantly impact their sales.

  ![Stores A and B Sales Trends](https://github.com/user-attachments/assets/1e8b0c6d-005f-4011-b4cc-58d054822731)

- **Store C**:
  - Sales are higher at the beginning of the month and decline towards the end.
  - Markdowns don't significantly affect its sales.

  ![Store C Sales Trend](https://github.com/user-attachments/assets/8b4f5e7a-6eb6-4eb1-b3cf-283171b848d4)

### 4. Optimal Markdown Amounts

- **Markdowns below \$20,000** are most effective for Stores A and B, especially during holidays.
- Larger markdowns (above \$20,000) have less impact during non-holiday periods.
  - It's best to keep markdowns at \$20,000 or less during non-holidays.

  ![Markdown Effectiveness](https://github.com/user-attachments/assets/a8583d08-eed5-4b9a-a8eb-77558a4d6a8f)

- **During Holidays**:
  - Higher markdowns (above \$20,000) are effective.
  - Correlations with sales are 0.67 for Store A and 0.7 for Store B.

  ![Holiday Markdown Impact](https://github.com/user-attachments/assets/23a648db-955b-470a-81af-3f7c9a7ad5a1)

### 5. Main Factors Influencing Sales

1. **Store Size**:
   - Larger stores generally have higher sales.
   - Strong correlation (up to 0.8) between store size and sales.
  
![size vs slaes](https://github.com/user-attachments/assets/afc9487f-6d33-45f7-96ed-ee35c4757d9f)


2. **Markdowns**:
   - Timing and amount are crucial, especially for Stores A and B.

3. **Holidays**:
   - Sales increase significantly during holidays when combined with promotions.

## Recommendations

1. **Non-Holiday Periods**:
   - Limit markdowns to \$20,000 or less for optimal results.

2. **Holiday Periods**:
   - It's beneficial to increase markdowns above \$20,000 to maximize sales.

3. **Adjust Strategies Based on Store Size**:
   - Tailor markdown strategies according to the size of the store.

4. **Reevaluate Promotions for Store C**:
   - Since markdowns aren't effective, consider other promotional strategies or focus on different factors.

## Conclusion

To optimize sales:

- **Customize markdown strategies** based on store type and time of year.
  - Use smaller markdowns during non-holidays.
  - Allow for larger markdowns during holidays for Stores A and B.
- **Consider store size** when planning promotions.
- **Explore alternative strategies for Store C**, as traditional markdowns don't boost its sales.

By following these insights, we can improve sales performance across different stores and times.
