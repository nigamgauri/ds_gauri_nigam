# Market Sentiment vs Trader Behavior – Data Science Assignment

Candidate: Gauri Nigam  
Email: nigamgauri24@gmail.com

This project analyzes how trader behavior varies with market sentiment using two datasets:
1. Fear & Greed Index (sentiment data)
2. Historical trading records (execution data)

By merging the datasets on the date field, we examine how different market sentiments (such as Fear, Greed, etc.) impact average trader profit/loss, trade size, and number of trades.

## Folder Structure

ds_gauri_nigam/
├── notebook_1.ipynb                 - Main analysis notebook (Google Colab)
├── ds_report.pdf                   - 1-page summary of key insights
├── csv_files/
│   └── merged_trader_sentiment.csv.gz   - Compressed merged dataset
├── outputs/
│   ├── pnl_comparison.png          - PnL per sentiment chart
│   └── trade_size_comparison.png   - Trade size per sentiment chart

## Key Analysis Steps

- Loaded and cleaned both datasets
- Merged datasets on the 'date' column
- Grouped merged data by market sentiment classification
- Calculated average profit/loss, trade size, and trade count
- Visualized trends with bar plots
- Saved final outputs for submission

## Notes

- The merged CSV file has been compressed to stay within GitHub's upload limit
- Graphs are included under the outputs/ directory
