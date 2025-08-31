# 📊 AgriData Explorer: Understanding Indian agriculture with EDA

India's agricultural sector is vital for the economy, but the management of agricultural data remains a challenge due to its complexity, fragmented nature, and lack of easy access. Various stakeholders such as farmers, policymakers, and researchers face difficulties in accessing, analyzing, and making informed decisions based on agricultural data.

The goal of this project is to create a data visualization platform that integrates agricultural data from different states and districts in India. The platform will provide insights into crop production, yields, and areas under cultivation, making it easier for users to identify trends, gaps, and regional disparities. This solution aims to help farmers optimize crop choices, assist policymakers in targeting areas for intervention, and support researchers in analyzing agricultural trends.

This repository contains three files for analyzing and visualizing agricultural production data:

## Files

- **`agridata.csv`**
  A Cleaned Dataset.


- **`agrieda.ipynb`**  
  A Jupyter Notebook that performs Exploratory Data Analysis (EDA) on agricultural datasets.  
  It includes:  
  - Data cleaning and preprocessing steps  
  - Statistical summaries  
  - Visualizations (bar charts, line plots, etc.)  
  - Insights into crop production (e.g., rice, wheat, millets, sorghum, oilseeds)  

- **`agripowerbi.pbix`**  
  A Power BI dashboard file that provides interactive visualizations for agricultural production.  
  It allows users to explore trends by:  
  - Crop type  
  - Region/State/District  
  - Year/Season (Kharif/Rabi)  
  - Comparative analysis of production and area  

## Requirements

### For Jupyter Notebook (`agrieda.ipynb`)
- Python libraries 
	pandas 
	numpy 
	sqlalchemy 
	pymysql 
	plotly

### For Power BI Report (`agripowerbi.pbix`)
- Microsoft Power BI Desktop (latest version recommended)

## Usage

1. **Run Jupyter Notebook**  
   - Open `agrieda.ipynb` in Jupyter Notebook or JupyterLab.  
   - Execute the cells step by step to reproduce the analysis.  
   - Modify the dataset path if needed.  

2. **View Power BI Dashboard**  
   - Open `agripowerbi.pbix` in Power BI Desktop.  
   - Explore interactive charts and slicers for insights.  

## Insights & Goals
The analysis aims to:  
- Identify top producing states and districts for key crops  
- Analyze trends over time  
- Compare production between Kharif and Rabi seasons  
- Build predictive models for crop production 

