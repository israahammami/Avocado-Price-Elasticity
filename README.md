Avocado Price Elasticity Analysis: A Business Analytics Case Study
📌 Project Overview
This project analyzes the Price Elasticity of Demand for conventional avocados in the US market using a dataset of 18,250 observations. As a Business and Economics student, my goal was to determine how sensitive consumers are to price changes and what that means for retail pricing strategies.

🛠️ Tech Stack
Language: R

Libraries: tidyverse (dplyr, ggplot2, readr), broom

Statistical Method: Log-Log Linear Regression

📊 Key Findings
Elasticity Coefficient: -0.617

Statistical Significance: p-value of 6.06e-14 (Highly Significant)

Insight: Demand is Inelastic. A 10% increase in price results in only a 6.2% decrease in quantity sold. This indicates strong consumer loyalty and significant pricing power for retailers.

🚀 How to Run the Analysis
Download the avocado.csv dataset.

Open Avocado_Analysis.R in RStudio.

Ensure the tidyverse package is installed: install.packages("tidyverse").

Run the script to generate the summary statistics and the demand curve visualization.

📈 Visualizations
The plot above demonstrates the negative correlation between log-price and log-quantity, with the red line representing our regression model.
