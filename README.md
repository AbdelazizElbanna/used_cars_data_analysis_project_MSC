# Used Cars Data Analysis - EDA Project (MSC)


## Project Overview

This repository contains the Exploratory Data Analysis (EDA) project on used cars data, conducted as part of a training program at the Microsoft Student Club in Kafr El-Sheikh. The project was a collaborative effort between [Abdelaziz El-banna] and [Fatema Shehata]. 

The goal of this project is to analyze a dataset of used cars to uncover insights into market trends, pricing factors, and vehicle characteristics. We cleaned the raw data, performed EDA using Python, visualized key patterns, and created an interactive dashboard to summarize findings. This analysis helps understand factors influencing used car prices, such as age, mileage, fuel type, transmission, and brand.

Key benefits of the project:
- Identifies market trends in the used car industry.
- Provides actionable insights for buyers, sellers, and dealerships.
- Demonstrates data cleaning, analysis, and visualization skills using Python and Jupyter Notebooks.

The dataset focuses on attributes like car name, year, selling price, km driven, fuel type, seller type, transmission, and owner history.

## Contributors
- [Abdelaziz El-banna] (GitHub: [https://github.com/AbdelazizElbanna])
- [Fatema ] (GitHub: [github-username])

## Repository Structure

Here's a breakdown of the files in this repository and their purposes:

- **car_data.csv**: The original raw dataset (CSV file) containing used car listings. It includes columns like `name`, `year`, `selling_price`, `km_driven`, `fuel`, `seller_type`, `transmission`, and `owner`. Note: This data was uncleaned and contained missing values, typos, and inconsistencies (e.g., spelling errors like "Petrrol" instead of "Petrol").

- **car_data_EDA_final.ipynb**: The final Jupyter Notebook for the Exploratory Data Analysis. This notebook includes:
  - Data loading and overview.
  - Data cleaning (handling missing values, correcting typos in fuel types like "Petrrol" to "Petrol", removing outliers).
  - Calculation of new features (e.g., car age, km per year).
  - Statistical summaries and visualizations (using Pandas, NumPy, Matplotlib, and Seaborn).
  - Key insights extraction, such as price distributions, fuel type dominance, and relationships between variables.

- **Cars-dashboard**: A file export of the interactive dashboard created for visualizing the analysis results. The dashboard includes:
  - Overview metrics (e.g., total km driven, average car age, average selling price).
  - Charts on fuel type distribution, transmission types, average prices by brand, owner type, and more.
  - Filters for owner type, transmission, fuel, and brand.

## Key Insights from the Analysis

From the EDA and dashboard, we derived the following insights (summarized from the notebook's conclusions):

1. **Price Distribution**: The used car market is concentrated in the mid-price range (average selling price ~477.59K). High-priced cars represent luxury brands, while extremes were removed for realistic analysis. **Insight**: Affordability drives consumer behavior.

2. **Vehicle Usage**: Average km driven is ~520K, with ~46K km per year. Outliers (extremely high mileage) were removed. **Insight**: Cars show moderate, realistic long-term usage.

3. **Car Age**: Average age is ~11 years (mostly 8-13 years old). Very old cars were filtered out. **Insight**: Dataset represents well-used but active market vehicles.

4. **Fuel Type**: Petrol dominates (>50%), followed by Diesel. CNG, LPG, and Electric are minimal. **Insight**: Petrol is the preferred fuel in the used market.

5. **Transmission**: Manual transmission is overwhelming (90.67%), with Automatic as a small fraction (9.33%). **Insight**: Manual is the common choice in this segment.

6. **Seller Type**: Mostly individual sellers, with fewer dealers. **Insight**: Peer-to-peer transactions dominate.

7. **Owner Distribution**: First owners are most common, followed by second/third. **Insight**: Single-owner cars build trust and value.

8. **Brand Analysis**: 19 brands, with Maruti leading in count. Premium brands (e.g., Land Rover, Mercedes) have higher average prices. **Insight**: Economy brands like Maruti dominate volume.

9. **Relationships**: Price decreases with age and km driven. Automatic, first-owner, low-mileage cars fetch higher prices. Fuel type influences pricing variations.

10. **Overall Trends**:
    - As car age increases, price decreases.
    - Higher mileage reduces value.
    - Brand strongly affects price.
    - Manual transmission is most prevalent.
    - Most cars are Petrol and first-owner.
    - High prices are natural for luxury segments.
    