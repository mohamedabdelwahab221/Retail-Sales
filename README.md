# Retail Sales & Markdown Strategy Analysis

## Objective:
The goal of this analysis was to understand the relationship between markdowns, holidays, store types, and other influencing factors on sales performance. By identifying key variables affecting sales, we aimed to provide actionable insights to optimize sales strategies.
## Key Findings:

### 1. Low Impact of External Factors:
- **CPI**, **Unemployment**, **Fuel Prices**, and **Temperature** showed low correlation with sales, indicating these external factors do not significantly affect sales performance in this dataset, and dosen't show any patterns.

  
![image](https://github.com/user-attachments/assets/003153ee-cac6-460a-a24c-8ebd7d15e77a)

### 2. Markdowns & Holidays:
- **Markdowns** have a moderate to high correlation with sales, particularly during holidays.
    - **For Store A**:
        - Correlation ranges from 0.565 to 0.889 during holidays.
    - **For Store B**:
        - Similar results, with correlations ranging from 0.556 to 0.700 during holidays.
    - **For Store C**:
        - Markdowns have little to no effect on sales, with very low or negative correlations (-0.076), suggesting markdown promotions are not effective for this store type.

### 3. Store Type Trends:
- **Store A** and **Store B** share similar sales patterns and trends, with markdowns having a notable impact.
  
  ![image](https://github.com/user-attachments/assets/1e8b0c6d-005f-4011-b4cc-58d054822731)

- **Store C** shows a unique sales pattern, where sales are higher at the beginning of the month and decline towards the end, without any significant correlation to markdowns.

  ![image](https://github.com/user-attachments/assets/8b4f5e7a-6eb6-4eb1-b3cf-283171b848d4)


### 4. Size of Markdown:
- **Markdowns below 25,000** show the best correlation with sales for Stores A and B, especially during holidays.
- Larger markdowns (above 25,000) appear to have diminishing returns, with smaller sample sizes showing inflated correlations. It is recommended to limit markdowns to **25,000 or below** during non-holiday periods to optimize sales without overspending.
- During **holidays**, markdowns can exceed the 25,000 threshold as they are shown to have a strong positive impact on sales with a correlation of 0.67.

### 5. Factors Affecting Sales:
- The two main factors that have the most significant impact on sales are:
    1. **Store Size**: Larger stores tend to show higher sales, with store size having a strong correlation with sales performance (as observed with a 0.8 correlation in some store types).
    2. **Markdowns**: Both the size and timing of markdowns play a critical role in boosting sales.
    3. **Holidays**: Sales are significantly higher during holidays, especially when combined with markdowns.

## Recommendations:
1. **For Non-Holiday Periods**: Stick to markdowns ≤ **25,000**, as this size has shown to work best with the available data and optimizes resource allocation.
2. **For Holiday Periods**: Given the 0.67 correlation, markdowns can exceed **25,000** during holidays to maximize sales potential.
3. **Focus on Store Size**: Ensure that markdown strategies are tailored according to store size, as it is one of the major factors influencing sales performance.
4. **Reassess Markdown Strategies for Store C**: Store C’s markdowns do not correlate with sales and should consider alternative promotional strategies or focus on other factors influencing sales.

## Conclusion:
This analysis highlights that markdown strategies should be tailored to both store type and holiday periods. Smaller markdowns work best during non-holidays, while larger markdowns can be more effective during holidays. Additionally, store size is a crucial factor influencing sales, and strategies should reflect this reality for maximum sales optimization.
