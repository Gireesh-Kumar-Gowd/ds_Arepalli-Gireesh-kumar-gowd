# Trading Data Analysis

This repository contains a complete notebook for analyzing trader behavior (profitability, risk, and volume) in relation to overall market sentiment (*Fear vs Greed Index*) using historical trading data.

---

## **Project Overview**

- **Goal:**  
  To discover how trader decisions and outcomes are influenced by daily market sentiment, and to identify actionable insights for trading strategy optimization.

- **Datasets:**  
  - **Market Sentiment Index:** Daily values measuring collective market emotions (fear, greed).
  - **Historical Trader Data:** Trade records from 2024–2025, including asset, price, size, side, direction, fees, PnL, and other metadata.

---

## **Repository Structure**

- `Trading_data_analysis.ipynb`  
  Main analysis notebook containing:
  - Data loading and cleansing
  - Feature engineering & encoding
  - Exploratory Data Analysis (EDA)
  - Data visualizations (trend, heatmaps, pairplots)
  - Insights and conclusions

- Data files (required, not supplied here):
  - `feargreedindex.csv` – Market sentiment data
  - `historicaldata.csv` – Trade records

---

## **Requirements**

- Python 3.x
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

Install with:

pip install pandas numpy matplotlib seaborn scikit-learn


---

## **Usage**

1. Place the required data CSV files in your project directory.
2. Open `Trading_data_analysis.ipynb` in Jupyter/Colab.
3. Run each cell sequentially to reproduce analysis and visualizations.
4. Review:
    - Data quality reports
    - Sentiment/trader activity trend plots
    - Correlation and strategy insights

---

## **Key Features & Methods**

- **Data Cleaning:**  
  - Removes unnecessary fields
  - Handles missing values and encodes categorical columns

- **EDA Visualizations:**  
  - Market sentiment trends
  - Correlation heatmap of trading outcomes/features
  - Pairwise summary plots
  - PnL and risk distribution by sentiment

- **Final Insights:**  
  - Explains how sentiment moves affect trading results
  - Identifies which strategies outperform based on emotional market states

---

## **Summary of Insights**

- Market sentiment is a strong driver of trading volume and profitability.
- Buy-side trades and higher risk strategies succeed during rising greed, while risk-aversion dominates in fear phases.
- Data-driven strategies should align with market mood for improved outcomes.

---

## **License**

This repository is for educational purposes. Please cite the original source when using or referencing the analysis.

---

## **Contact**

For feedback and questions, please open an issue or contact the repository owner.

