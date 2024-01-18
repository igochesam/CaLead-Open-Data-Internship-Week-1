# E-commerce Sales Data Analysis

## Overview

This repository contains the analysis of a sales transaction dataset from a UK-based e-commerce platform. The dataset covers one year of transactions for a London-based online retail shop specialising in gifts and homewares. The goal of this analysis is to gain insights into sales trends, customer behaviour, and profitability.

## Dataset Description

- **Size:** 500K rows, 8 columns
- **Columns:**
  - `TransactionNo`: Six-digit unique number defining each transaction (C indicates cancellation).
  - `Date`: Date of each transaction.
  - `ProductNo`: Unique character identifying a specific product.
  - `Product`: Name of the product/item.
  - `Price`: Price per unit in pound sterling (£).
  - `Quantity`: Quantity per transaction (negative values for cancellations).
  - `CustomerNo`: Five-digit unique number defining each customer.
  - `Country`: Name of the country where the customer resides.

## Questions Explored

1. **Sales Trend Over Months:**
   - Analysed the sales trend over the months to understand fluctuations and patterns.

2. **Frequently Purchased Products:**
   - Identified the most frequently purchased products.

3. **Quantity of Products in Each Transaction:**
   - Explored how many products customers typically purchase in each transaction.

4. **Most Profitable Customer Segments:**
   - Determined the most profitable segments of customers based on the analysis.

## Findings and Recommendations

- **Sales Trend:**
  - The sales data covers the time between January and January 2021. Sales peaked in December 2019 with almost 8 Million Pounds generated in sales in that month alone. On the contrary, sales was at the lowest in January 2020 with a value of a little over 1 Million Pounds in total. The average monthly sales across the months stood at about 4.8 Million Pounds.
  - ![image](https://github.com/igochesam/CaLead-Open-Data-Internship-Task-1/assets/109409835/acde900e-6f26-44c6-8564-a14119dc13cf)

- **Frequently Purchased Products:**
  - The top 5 most frequently purchased products are Cream Hanging Heart T-Light Holder (2336 purchases), Jumbo Bag Red Retrospot (2115 purchases), Regency Cakestand 3 Tier (2019 purchases), Party Bunting (1708), and Lunch Bag Red Retrospot (1597).
  - As for the least frequently purchased products, a couple of products were purchased just once. In fact, 122 items were purchased just once. You can find the list in the Jupyter Notebook file. 
  - ![image](https://github.com/igochesam/CaLead-Open-Data-Internship-Task-1/assets/109409835/96e3da4e-c2d0-4aa6-8104-af62d6c74e23)
  
- **Quantity of Products in Each Transaction:**
  - The total number of successful transactions is 19790. The highest quantity purchased in one transaction is 80995 and the least quantity is 1. The items purchased the most are items for designs and decorations. Only a few customers purchased items in such large quantities, while majority of the transaction quantities were less than 10. [Share insights into customer behaviour regarding the quantity of products in transactions.]

- **Profitable Customer Segments:**
  - The most profitable segments in this case will be determined by the countries with the highest average revenue. The top 5 countries in this category are Sweden, the Netherlands, Japan, Australia, and the Czech Republic.
  - ![image](https://github.com/igochesam/CaLead-Open-Data-Internship-Task-1/assets/109409835/1367996d-e6ca-4b47-8fdd-1498eae300c3)

## Recommendations for Business Strategy

Based on the analysis, the following recommendations are proposed:

1. **Seasonal Sales Patterns:**
   - The analysis reveals a significant peak in sales during December 2019 and a subsequent decline in January 2020. This pattern may be attributed to holiday season purchases. Consider leveraging this insight for targeted marketing campaigns during festive periods to capitalize on increased consumer spending.

2. **Top Frequently Purchased Products:**
   - The most frequently purchased products, including 'Light Holder,' 'Jumbo Bag,' and 'Cake Stand,' indicate specific items that are popular among customers. Consider bundling or promoting these items to boost overall sales.

3. **Large Quantity Purchases:**
   - The observation of a few transactions with exceptionally high quantities, exceeding 8000 items, suggests a small but significant group of customers making bulk purchases. Identifying and understanding the needs of these bulk purchasers can lead to tailored marketing strategies or loyalty programs to encourage repeat business.

4. **Profitable Countries by Average Revenue:**
   - Countries such as Sweden, the Netherlands, Japan, Australia, and the Czech Republic stand out as the most profitable based on average revenue per transaction. Focus marketing efforts in these regions, explore potential expansion strategies, or consider offering exclusive deals to enhance customer loyalty.

5. **Least Profitable Countries:**
   - Iceland, South Africa, and Austria emerge as the least profitable countries in terms of average revenue. Investigate the reasons behind lower revenue in these regions. It might involve adjusting marketing strategies, exploring local preferences, or optimizing logistics to improve profitability.

6. **Tailored Marketing for High-Value Customers:**
   - Given the presence of customers making large quantity purchases, consider developing personalized marketing strategies for this segment. Special offers, bulk discounts, or loyalty programs can be implemented to incentivize repeat business.

7. **Continuous Monitoring and Adaptation:**
   - Regularly monitor sales trends, frequently purchased products, and customer preferences. Market dynamics can change, so staying agile and adapting strategies based on ongoing analysis is crucial for sustained success.

8. **Global Expansion Opportunities:**
   - Consider exploring opportunities for global expansion, especially in regions with favourable revenue patterns. Expanding operations in profitable markets can contribute significantly to overall business growth.

## Tools Used for Analysis

The analysis was performed using the following tools and libraries:

- [Jupyter Notebooks](https://jupyter.org/): Used for interactive data analysis.
- [Pandas](https://pandas.pydata.org/): Data manipulation and analysis library for Python.
- [Matplotlib](https://matplotlib.org/): Plotting library for visualisation.
- [Seaborn](https://seaborn.pydata.org/): Statistical data visualisation based on Matplotlib.

## Getting Started

To replicate the analysis or explore the dataset, follow these steps:

1. Clone the repository.
2. Run the Jupyter notebooks in the `analysis` directory.

## Contributing

If you have suggestions or find issues, please feel free to open an issue or submit a pull request.

## Acknowledgements

- CaLead Open Data Internship 2023

