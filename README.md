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
  - As for the least frequently purchased products, a couple of products were purchased just once. In fact, 122 items were purchased just once, and these products fall in the category of items used in arts and crafts. You can find the list in the Jupyter Notebook file. 
  - ![image](https://github.com/igochesam/CaLead-Open-Data-Internship-Task-1/assets/109409835/96e3da4e-c2d0-4aa6-8104-af62d6c74e23)
  
- **Quantity of Products in Each Transaction:**
  - [Share insights into customer behaviour regarding the quantity of products in transactions.]

- **Profitable Customer Segments:**
  - [Identify and describe the most profitable customer segments.]

## Recommendations for Business Strategy

Based on the analysis, the following recommendations are proposed:

1. [Strategy recommendation 1.]
2. [Strategy recommendation 2.]
3. [Strategy recommendation 3.]

## Tools Used for Analysis

The analysis was performed using the following tools and libraries:

- [Jupyter Notebooks](https://jupyter.org/): Used for interactive data analysis.
- [Pandas](https://pandas.pydata.org/): Data manipulation and analysis library for Python.
- [Matplotlib](https://matplotlib.org/): Plotting library for visualisation.
- [Seaborn](https://seaborn.pydata.org/): Statistical data visualisation based on Matplotlib.

## Getting Started

To replicate the analysis or explore the dataset, follow these steps:

1. Clone the repository.
2. [Instructions for setting up the environment, if any.]
3. Run the Jupyter notebooks in the `analysis` directory.

## Dependencies

List any dependencies or libraries required to run the analysis.

## Contributing

If you have suggestions or find issues, please feel free to open an issue or submit a pull request.

## Licence

This project is licensed under the [License Name] - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgements

- CaLead Open Data Internship 2023

