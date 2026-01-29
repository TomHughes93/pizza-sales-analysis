# Consumer Choice and Behaviour in Pizza Sales (2015)

## Project Overview
This project analyses transactional pizza sales data from 2015 to explore consumer purchasing behaviour. Using R and the tidyverse, the analysis examines how product category, pizza size, pricing, and time influence revenue and sales volume.

The project focuses on descriptive and exploratory analysis rather than prediction, demonstrating data cleaning, aggregation, visualisation, and insight generation in R.

## Business Question
How do pizza category, size, and pricing influence sales volume and revenue, and what patterns emerge in consumer purchasing behaviour over time?

## Dataset
- Source: Pizza Sales Dataset (Kaggle)
- Time period: January–December 2015
- Observations: 48,620 order lines

Key variables include:
- Order date and time
- Pizza category and size
- Quantity sold
- Unit price and total revenue

## Tools & Technologies
- **R**
- **R Markdown**
- **tidyverse (dplyr, ggplot2, tidyr)**

## Key Analysis Steps
- Data validation and cleaning
- Revenue and volume aggregation by category and size
- Visual analysis of sales and revenue patterns
- Monthly trend analysis
- Comparison of volume-driven vs price-driven categories

## Key Insights
- Classic pizzas generate the highest sales volume, indicating broad customer appeal.
- Supreme and Chicken pizzas achieve higher average revenue per unit, suggesting premium pricing strategies.
- Large pizzas contribute most to revenue, while medium pizzas dominate unit sales.
- Monthly demand remains relatively stable throughout the year, with predictable fluctuations rather than strong seasonality.
- A clear trade-off exists between high-volume products and high-value products.

## Files in This Repository
- `pizza_analysis.Rmd` — Full R Markdown analysis
- `pizza_analysis.html` — Rendered report
- `pizza_sales.csv` — Raw dataset
- `README.md` — Project documentation

## How to Reproduce
1. Clone or download this repository
2. Open `pizza_analysis.Rmd` in RStudio
3. Ensure required packages are installed (`tidyverse`)
4. Knit the document to HTML

## Notes
This project is intended as a portfolio-style data analysis demonstrating applied R skills and exploratory data analysis techniques. It does not attempt causal inference or predictive modelling.
