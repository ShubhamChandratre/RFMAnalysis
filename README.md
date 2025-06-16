# RFM Analysis Project

This repository contains an implementation of RFM (Recency, Frequency, Monetary) analysis for customer segmentation. The project leverages Python and Jupyter Notebook to process transactional data and segment customers into meaningful categories.

## Dataset
The dataset used in this analysis is provided in `Dataset.xlsx`. It contains transactional details required to compute RFM metrics, including:
- **Customer ID**: Unique identifier for each customer.
- **Transaction Date**: Date of each transaction.
- **Monetary Value**: Purchase amount per transaction.

## Overview of the Project
RFM analysis is a technique used to evaluate customer behavior by analyzing their purchase history. It helps businesses identify and segment customers into categories such as "Champions," "Loyal Customers," and "At Risk." This segmentation provides actionable insights for targeted marketing strategies.

### Key Objectives:
- Calculate RFM metrics for each customer:
  - **Recency**: Days since the last purchase.
  - **Frequency**: Number of transactions made.
  - **Monetary Value**: Total spending of the customer.
- Assign RFM scores based on these metrics.
- Categorize customers into segments based on their RFM scores.

## Steps Performed
1. **Data Loading and Exploration**:
   - Loaded transactional data from `Dataset.xlsx`.
   - Performed exploratory data analysis (EDA) to understand the dataset structure and identify missing values.

2. **Data Preprocessing**:
   - Handled missing data and standardized date formats.
   - Ensured monetary values were positive and consistent.

3. **Calculation of RFM Metrics**:
   - Computed Recency, Frequency, and Monetary values for each customer.
   - Used pandas to aggregate data at the customer level.

4. **RFM Scoring**:
   - Assigned scores to each metric based on their quartile distribution.
   - Combined scores to generate a composite RFM score for each customer.

5. **Customer Segmentation**:
   - Defined rules to categorize customers into groups such as:
     - **Champions**
     - **Loyal Customers**
     - **Potential Loyalists**
     - **At Risk**
     - **Hibernating**
   - Segments provide actionable insights into customer behavior.

6. **Visualization**:
   - Created visualizations, including bar plots and heatmaps, to represent the distribution of customer segments and RFM relationships.

7. **Exporting Results**:
   - Saved the processed data, including RFM scores and segments, to an updated Excel file for further use.

## Files in the Repository
- **Dataset.xlsx**: Input dataset containing transactional details.
- **PythonNotebook_RFMAnalysis.ipynb**: Jupyter Notebook containing the RFM analysis implementation.

## Results
- **RFM Scores**: Customers are scored based on Recency, Frequency, and Monetary metrics.
- **Customer Segmentation**: Provides clear insights into customer groups, helping businesses target them effectively.

## Requirements
The analysis is performed using Python with the following libraries:
- pandas
- numpy
- matplotlib
- seaborn

To run the analysis, ensure you have these libraries installed in your Python environment.

## How to Use
1. Clone the repository.
2. Open `PythonNotebook_RFMAnalysis.ipynb` in Jupyter Notebook.
3. Run the notebook cells sequentially to:
   - Load and preprocess the data.
   - Compute RFM metrics.
   - Segment customers and visualize the results.
4. Check the updated `Dataset.xlsx` file for results.

## Insights
- The analysis provides actionable insights into customer behavior.
- Businesses can use these insights to:
  - Retain high-value customers.
  - Re-engage at-risk customers.
  - Optimize marketing strategies.

## Contact
For any questions or feedback, feel free to reach out to [Shubham Chandratre](https://github.com/ShubhamChandratre).

---

This project demonstrates how to use RFM analysis to segment customers effectively. Contributions and suggestions are welcome!
