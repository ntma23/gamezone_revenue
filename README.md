# Game Zone's Revenue Analysis
## Project Background

Game Zone, established in 2019, is a US company selling technology products worldwide.

The company has rich sales data that has not been fully utilized. This project aims to analyze the data to uncover insights about sales trends and provide recommendations for improving revenue through better marketing efforts.

Insights and recommendations are provided on the following key areas:

- Sales Trend Analysis: Examine historical sales patterns, focusing on total revenue.
- Product Performance: Assess the impact of key products on overall revenue and investigate potential products.
- Marketing Channel Comparison: Analyze revenue, sales, and average order value (AOV) performance across different marketing channels and purchase platforms.
- Regional Comparison: Compare sales metrics across various regions and countries.

An interactive Power BI dashboard can be downloaded [here](https://github.com/ntma23/gamezone_revenue/blob/main/game%20zone.pbix).

## Data Structure

Game Zone’s database structure, as seen below, consists of 2 tables: orders and regions, with a total row count of 21,685 records.
![order_id (1)](https://github.com/user-attachments/assets/bf640081-170b-45b3-b541-c0368d3d044a)


Prior to beginning the analysis, a variety of checks were conducted for quality control and familiarization with the dataset. The Issue log Excel file can be found [here](https://github.com/ntma23/gamezone_revenue/blob/main/Game%20Zone_Issue%20Log.xlsx).

## Executive Summary

After an initial growth surge in early 2020, Game Zone experienced a steep decline in sales metrics in 2021. However, this drop is expected because of seasonality, and key metrics still outperformed the previous year.

The following sections will identify factors contributing to this trend and opportunities for improvement.

Below is the overview page from the Power BI dashboard, and more examples are included throughout the report. The entire interactive dashboard can be accessed [here](https://github.com/ntma23/gamezone_revenue/blob/main/game%20zone.pbix).
![image](https://github.com/user-attachments/assets/57ab1c29-f5e9-44cb-b4a4-fe55d7cc9376)


## Insight Deep Dives

### Sales Trend Analysis

- Sales exhibit a seasonal pattern marked by an overall upward trend that **declines in October**, followed by a **peak in December**. This trend can largely be attributed to the holiday season at the end of the year, which prompts consumers to increase their spending on entertainment products.
- However, this surge in expenditure is often followed by a notable **reduction in January**, as individuals seek to adjust for their overspending during the holidays.
- This seasonal trend is true across products, marketing channels, and regions. It can also explain the significant drop at the beginning of 2021.
- Total revenue reached $4.06 million in 2020, representing an exceptional growth of 163.26% along with a 102.30% rise in sales volume, along with a 30.13% increase in AOV.
![image](https://github.com/user-attachments/assets/9ccea85f-488c-4bf7-814f-e8213529c324)


### Product Level Performance

- A similar spike was observed across all products. However, the **top three key items** displayed the most significant growth in 2020: the Sony PlayStation (+360.38%), the 27K gaming monitor (+119.22%), and the Nintendo Switch (+98.43%), while others maintained stability.
- In 2019, the 27K gaming monitor led the market, accounting for an average of 40% of revenue, followed closely by the Nintendo Switch at around 33%. Since 2020, both the Sony PlayStation and the 27K gaming monitor have alternated in capturing the largest market share, each hovering around 30%.
- With a combined market share exceeding 80% and remarkable growth rates, the Sony PlayStation, the 27K gaming monitor, and the Nintendo Switch are likely the **primary drivers** of the revenue surge in the 2020s.
- **Some products performed poorly**, including the Razer Gaming Headset, Dell Gaming Mouse, Acer Laptop, and JBL Headset. Together, they brought in less than 5% of the total revenue during all periods. The Razer Headset sold the worst, with only 6 units sold for a total of $764. The JBL Headset was one of the top 3 selling products, but because its average price was the lowest at $22.49, it only brought in a maximum of 2.86% of total revenue.
![image](https://github.com/user-attachments/assets/b6b65718-d7f9-49a1-b4e6-075fafa3237e)



### Marketing Channel Comparisons

- The **direct channel**, which is the **main revenue source**, experienced a growth rate of 160.64%, generating $3.44 million, while other channels remained low, notably social media, accounting for less than 1% on average of revenue.
- The **affiliate channel** consistently maintained **the highest AOV** of $322.48 on average and had significant growth at the beginning of 2020 with a peak of $519.73. However, less than 5% of orders came from affiliates, whereas approximately 80% of orders were through the direct channel. Thus, lower contribution to the overall revenue than the direct channel.
![image](https://github.com/user-attachments/assets/b6583135-4248-488a-96b7-ae8d48865ab3)



### Region Market Shares

- Revenue spikes were observed across all four regions, with the most significant increases in **North America (NA)** and **Europe, the Middle East, and Africa (EMEA)**. North America held more than half of the market share, while EMEA accounted for over 30%.
- All four regions experienced a general upward trend, converging toward higher AOVs by the end of the period. LATAM exhibited the most volatility with sharp spikes at the end of 2019, while EMEA showed a steady rise. At the beginning of 2020, all regions experienced a spike, except for LATAM, which saw a sharp drop.
![image](https://github.com/user-attachments/assets/2efa63e8-8534-4b82-ae15-843b16ced735)



## Recommendations

- Although the sharp decline in sales in early 2021 is attributed to seasonal patterns, it is possible to implement promotions or loyalty programs to retain customers or boost sales during slower seasons to alleviate seasonal variances.
- With a combined market share exceeding 80% and impressive growth rates, the Sony PlayStation, the 27K gaming monitor, and the Nintendo Switch are likely the primary drivers of revenue. Therefore, we should reallocate the marketing budget from underperforming products like Razer Headset to focus on these three key products to maintain and bolster the revenue growth rate.
- JBL Headset was one of the most popular products with high volume in sales but low in value. We can offer it in a combo with key revenue driver products to increase the amount spent per transaction.
- The direct sales channel is the main source of revenue, contributing over 80%. Thus, we should invest more in marketing campaigns for this channel while adjusting the budget for less effective channels, i.e., social media.
- Although the affiliate channel has low sales volume (less than 5%), it has a high average order value of $322.48, indicating potential. We should consider implementing promotions and enhancing marketing campaigns in this channel to increase the sales volume and, consequently, overall revenue.
- The North America (NA) and Europe, Middle East, and Africa (EMEA) regions together account for over 80% of revenue. Therefore, we should focus our marketing efforts and advertisements on these regions, particularly for higher-value products such as the Sony PlayStation, to promote an increase in average order value.

## Caveats and Appendix

- In the analysis, it was noted that Marketing Channel categorized as "unknown" and missing Region observations were hidden from the visualizations to avoid skewness and see the overall trends clearly. There were some missing transactions and duplicate observations in the order data that required verification with stakeholders. However, given the project's scope and the insignificant magnitude of these issues, less than 1%, the decision was made to remove them to prevent potential errors in metric calculations. More information about missing values in the Issue log can be found [here](https://github.com/ntma23/gamezone_revenue/blob/main/Game%20Zone_Issue%20Log.xlsx).

- Furthermore, the analysis could be enhanced by incorporating data from the marketing team regarding campaigns. There is also an opportunity to further investigate customer profiles by utilizing demographic information.
