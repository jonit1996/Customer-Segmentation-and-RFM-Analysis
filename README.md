# Customer Segmentation and RFM Analysis

This repository contains a Jupyter notebook that demonstrates how to perform customer segmentation using RFM (Recency, Frequency, Monetary) analysis. The goal of the analysis is to segment customers based on their purchasing behavior, which can help businesses identify and target different customer groups effectively.

## Overview

**Customer Segmentation** is a crucial technique in marketing and sales that involves dividing a customer base into groups that are similar in specific ways relevant to marketing, such as age, gender, interests, spending habits, etc.

**RFM Analysis** is a data-driven customer segmentation technique that uses three key metrics:
- **Recency (R):** How recently a customer made a purchase.
- **Frequency (F):** How often a customer makes a purchase.
- **Monetary Value (M):** How much money a customer spends on purchases.

These metrics help in understanding customer behavior, which can be used to optimize marketing strategies and improve customer retention.

## Contents

The repository includes the following files:
- `Customer Segmentation and RFM Analysis.ipynb`: The main Jupyter notebook containing the code and analysis.

### The notebook covers the following steps:

1. **Data Loading:** 
   - The dataset is loaded, and an initial inspection is performed to understand the structure and content.

2. **Data Preprocessing:**
   - This section involves cleaning the data, such as handling missing values, converting data types, and preparing the data for analysis.

3. **RFM Segmentation:**
   - The RFM metrics are calculated for each customer.
   - Customers are segmented based on their RFM scores, allowing us to identify groups such as 'Best Customers,' 'At Risk,' and 'Churned.'

4. **Visualizations:**
   - Several plots are created to visualize the distribution of RFM scores and the characteristics of different customer segments.
   - Specific visualizations include scatter plots and heatmaps that highlight the relationships between Recency, Frequency, and Monetary value.

5. **Churn Rate Calculation:**
   - The churn rate is calculated based on specific RFM criteria to identify customers who are at risk of leaving.

6. **Insights and Recommendations:**
   - The notebook concludes with insights derived from the analysis and recommendations on how to target different customer segments.

## How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/customer-segmentation-rfm-analysis.git
   cd customer-segmentation-rfm-analysis
2. Install the required packages:

Make sure you have Python installed. You can install the required packages using pip:

   pip install -r requirements.txt 

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Customer\ Segmentation\ and\ RFM\ Analysis.ipynb
## Key Findings
- **Churn Rate:** The analysis reveals a churn rate of 33.30%, indicating that approximately one-third of customers are at risk of leaving.
- **Customer Segments:** The segmentation identifies key customer groups that can be targeted with specific marketing strategies to improve retention and increase
  revenue.
## License
This project is licensed under the Apache License Version 2.0  - see the LICENSE file for details.

