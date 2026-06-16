\# Video Game Sales Predictive Analytics \& Market Segmentation



\*\*Student:\*\* Sajan Tamang | \*\*ID:\*\* 250387 | \*\*Module:\*\* STW7082CEM



\## Project Overview

This project uses PySpark to forecast global video game sales and segment markets (NA, EU, JP, Other) using K‑Means clustering. An interactive Tableau dashboard visualises the results.



\## Dataset

Source: \[Video Game Sales and Ratings](https://www.kaggle.com/datasets/thedevastator/video-game-sales-and-ratings) on Kaggle.

(Please download the dataset from the link above; a small sample is included in `data/sample\_data.csv`.)



\## Repository Structure

\- `notebook/` – Full PySpark notebook (Phases 1‑6)

\- `images/` – All generated charts and plots

\- `tableau/` – Tableau Packaged Workbook (.twbx)

\- `report.docx` – Final project report



\## How to Run

1\. Clone this repo.

2\. Download the full dataset from Kaggle and place it in the root folder as `Video\_Games\_Sales\_as\_at\_22\_Dec\_2016.csv`.

3\. Open `notebook/VideoGameSales\_Analysis.ipynb` in Google Colab or Databricks.

4\. Run all cells sequentially.



\## Key Results

\- Best regression model: Gradient‑Boosted Trees (RMSE = X.XXXM, R² = 0.XXX)

\- Five regional market segments identified via K‑Means.

\- Interactive Tableau dashboard available.

