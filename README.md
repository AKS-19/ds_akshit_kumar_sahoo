Trader Behavior vs Bitcoin Market Sentiment

Project Overview:

This project studies how trader behavior changes based on overall Bitcoin market sentiment (Fear and Greed). By combining market sentiment data with historical trading data, the project analyzes how profit, risk, and trade size vary in different market conditions.

The goal is to understand whether market sentiment can help explain trading performance and risk-taking behavior.

Notebooks:

notebook_1.ipynb: Main analysis notebook.

Contains all data loading, cleaning, analysis, and visualizations.

Historical Trader Data from Hyperliquid:(Provided the google drive link fro this csv due to 25mb limitation of GitHub)

Link: https://drive.google.com/file/d/1Zjo-RW6MG-widSoco3_eIPcUbCVbKpcI/view?usp=drive_link

Google Colab Link:

notebook_1.ipynb: https://colab.research.google.com/drive/1DtDP3mAxwitays6fIttVgKNqwtBFVjat?usp=sharing

Key Questions Answered:

1.How does profitability change during Fear and Greed?

2.Do traders take larger positions during Greed?

3.How does risk (volatility and large losses) change with sentiment?

4.Are there hidden performance trends using rolling averages?

How to Run:

1.Open notebook_1.ipynb in Google Colab.

2.Upload fear_greed_index.csv and historical_data.csv to Colab.

3.Run all cells from top to bottom.

4.Download generated plots from the outputs/ folder.

Notes:

1.All analysis is done in a single notebook: notebook_1.ipynb.

2.Leverage is approximated using trade size (Size USD) due to lack of explicit leverage data.

3.All notebooks are shared with public viewer access as required.
