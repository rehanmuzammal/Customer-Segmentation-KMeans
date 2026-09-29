# 🧩 Customer Segmentation — RFM Analysis & K-Means Clustering

## Objective
Apply clustering algorithms to segment an e-commerce company's customer base into distinct groups based on purchasing behaviour (RFM: Recency, Frequency, Monetary), enabling targeted marketing strategies.

## Dataset
- **Source:** [UCI Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)

## Tech Stack
- Python
- pandas, numpy
- scikit-learn (KMeans, StandardScaler)
- matplotlib, seaborn
- Jupyter Notebook

## Key Steps
1. Data cleaning (remove nulls, negative quantities/prices)
2. RFM feature engineering (Recency, Frequency, Monetary)
3. Feature scaling with StandardScaler
4. Elbow Method to determine optimal number of clusters (K)
5. K-Means clustering
6. Cluster visualization (scatter plots)
7. Cluster profiling (mean feature values per segment)
8. Marketing recommendations per segment

## Key Insights
- Customers segmented into groups such as **VIP/loyal**, **at-risk/churned**, **new/casual**, and **regular** customers.
- Each segment has a tailored marketing action (loyalty rewards, win-back campaigns, onboarding offers, etc.)

## How to Run
1. Download `Online Retail.xlsx` from the dataset link above.
2. Install dependencies: `pip install pandas numpy scikit-learn matplotlib seaborn openpyxl`
3. Open `Task2_Customer_Segmentation.ipynb` in Jupyter Notebook and run all cells.

## Author
[Rehan Muzammal]
