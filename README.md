# Retail Sales Analysis: Data Cleaning & Consumer Insights

## Project Overview
This project involves a comprehensive end-to-end analysis of a retail dataset containing over 12,500 transactions. The primary focus was transforming a "messy" raw dataset into a clean, actionable source of truth to uncover consumer spending habits and business performance.

## Technical Challenges & Solutions

**Advanced Data Cleaning & Logical Imputation**<br>
The raw data contained significant gaps. Instead of removing rows, I utilized Logical Imputation to maintain data integrity:
  - Item Reconstruction: Recovered 98.5% missing product names by mapping unique combinations of Price, Category, and Month.
  - Statistical Imputation: Handled missing 'Quantity' and 'Total Spent' using Median values to mitigate the influence of outliers.
  - Mathematical Back-calculation: Restored missing unit prices by dividing 'Total Spent' by 'Quantity'.

## Key Business Insights
  - The "January Surge": Sales consistently peak in January, followed by stable performance throughout the year.
  - Omnichannel Balance: Revenue is split 50/50 between Online and In-store channels, with consistent category performance across both.
  - Inelastic Demand: Quantity purchased remains steady regardless of price fluctuations, suggesting the inventory consists largely of consumer essentials.
  - Payment Uniformity: Consumer spending distribution remains identical across Cash, Credit Cards, and Digital Wallets.

## Tools & Technologies
  - Language: Python 3.x
  - Libraries: Pandas (Data Manipulation), Matplotlib & Seaborn (Visualization)
  - Environment: Jupyter Notebook / Kaggle

## How to Use
1. View Online: The easiest way to see this project is to click on the retail_sales_analysis.ipynb file right here on GitHub. GitHub will automatically display the code and all the visualizations.

2. Run Locally: Ensure you have Python and Jupyter Notebook installed on your computer.
    - You will need the following libraries: pandas, matplotlib, and seaborn.
    - Download the .ipynb file and open it in your local environment.
