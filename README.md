# Supermarket Sales Analysis

A data analysis project exploring supermarket sales data to identify branch performance, customer behavior, product trends, and sales patterns.

## Project Objective

The goal of this project is to analyze supermarket transaction data and identify key factors affecting sales performance across different branches.

## Dataset

The dataset contains 1,000 supermarket transactions from three different branches.

It includes information about:
- product categories and sales
- customer types
- payment methods
- transaction dates and times
- gross income and customer ratings

Dataset source: [Supermarket Sales Dataset — Kaggle](https://www.kaggle.com/datasets/faresashraf1001/supermarket-sales)

## Tools

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Workflow

The analysis follows these main steps:

1. Data loading and initial exploration
2. Data quality checks
3. Feature engineering
4. KPI analysis
5. Product line analysis
6. Payment method analysis
7. Time of day analysis
8. Customer type analysis
9. Conclusions and business insights

## Key Insights

- Giza generated the highest total sales and gross income despite having the lowest number of transactions.
- Giza also had the highest average transaction value and customer rating.
- Food and Beverages was the highest-selling product category overall.
- Afternoon was the strongest sales period across all three branches.
- Member customers generated higher total sales than Normal customers in every branch.
- The payment method generating the highest sales differed by branch: Ewallet in Alex, Credit Card in Cairo, and Cash in Giza.

## Project Structure

- `supermarket_analysis.ipynb` — complete data analysis and visualizations
- `SuperMarket Analysis.csv` — dataset used in the analysis
- `README.md` — project overview and key findings
- `requirements.txt` — Python dependencies required to run the project

## Author

This project was created as part of my data analytics portfolio.

## How to Run

1. Clone or download this repository.
2. Install the required Python libraries:
   `pip install -r requirements.txt`
3. Open `supermarket_analysis.ipynb` in Jupyter Notebook or VS Code.
4. Run all cells from top to bottom.
