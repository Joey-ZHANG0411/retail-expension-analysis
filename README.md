# Retail Expansion Site Selection Analysis

"A quantitative site selection framework integrating multiple regression, K‑means clustering, and Monte Carlo simulation — with a comparison of standalone NPV vs. incremental firm value approaches"

### Project Overview

This project builds an end-to-end, data-driven decision system for retail expansion:
1.Forecasts regional demand using synthetic sales and demographic data

2.Segments candidate locations into market potential tiers via clustering

3.Constructs a Discounted Cash Flow (DCF) model and runs 5000 Monte Carlo simulations to quantify risk

4.Employs a multi‑attribute scoring model to deliver structured site recommendations

5.Adds an enterprise value comparison experiment that reveals the systematic overestimation of standalone NPV when cannibalization of existing stores is ignored

###Tools

Python (pandas, numpy, scikit-learn, matplotlib, numpy-financial) · Jupyter Notebook

### Run the codes

1. Clone the repository or download `Retail_X.ipynb`
   
2. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn numpy-financial`
   
3. Open the file with Jupyter Notebook and Run All

### Key Results

1.Regression R² ≈ 0.72; population and income are the main positive drivers of sales

2.184 candidate areas were clustered into High / Medium / Low potential groups; K=3 was chosen based on business interpretability

3.The High‑potential store shows an expected NPV of ~$224k with a positive 5% VaR, indicating a high safety margin

4."Firm‑value experiment": While the sum of independent NPVs of the two positive‑NPV stores is ~$370k, the true enterprise value increment drops to only ~$134k after a 20% cannibalization assumption — nearly 64% of the expected wealth is eroded by internal competition

### File Structure

1.`Retail_X.ipynb` : Full analysis code and visualizations

2.`Experiment_report - Retail_Expansion.pdf` : Formal report (methods, results, discussion)

3.`README.md` : This file

