# sentiment-market-analysis

Trader Performance & Sentiment Analysis

Overview

This project analyzes trader profitability and behavior across different market sentiment regimes using:

Historical trading data

Fear & Greed Index data

The full analysis, methodology, insights, and results are included in the Google Colab notebook.

Dataset Information

Two datasets were used:

historical_data.csv — Contains trader-level daily PnL and trading metrics

fear_greed_index.csv — Contains daily sentiment classification

Due to large file sizes, the CSV datasets are not uploaded to this repository.
However, all outputs, visualizations, and analysis results are fully available in the notebook.

To rerun the project, place both CSV files in the same directory as the notebook.

Project Structure
├── analysis.ipynb          # Main Google Colab / Jupyter Notebook
├── README.md               # Project documentation

Setup Instructions

Clone the repository:

git clone <https://github.com/juiilly/sentiment-market-analysis.git>
cd <sentiment-market-analysis>

Install required packages:

pip install pandas numpy matplotlib seaborn scikit-learn

How to Run
Option 1: Jupyter Notebook
jupyter notebook

Open analysis.ipynb and run all cells.

Option 2: Google Colab

Upload the notebook to Google Colab

Upload both CSV files to the Colab session

Run all cells

Output

The notebook includes:

Sentiment-based performance analysis
Behavioral analysis
Trader segmentation
Visualizations and summary insights
Strategy recommendations

All results are directly visible in the notebook.

Add the required datasets:

Place historical_data.csv

Place fear_greed_index.csv
in the project folder.
