# Google Play Store App Review EDA

## Project Overview
This project performs an Exploratory Data Analysis (EDA) on merged Google Play Store app and user review datasets (122,662 records and 17 columns) to uncover patterns across app categories, ratings, reviews, installs, app sizes, pricing models, update trends, and user sentiment.

## Objective
To identify key factors that influence app popularity, user ratings, and customer satisfaction so developers and businesses can make informed product and growth decisions.

## Tools & Technologies
- **Programming & Data Analysis:** Python, NumPy, Pandas, Datetime
- **Data Visualization:** Matplotlib, Seaborn, Plotly Express
- **Environment:** Google Colab

## Workflow & Methodology
1. **Data Loading & Merging:** Loaded `Play Store Data.csv` and `User Reviews.csv` and merged them on `App` (inner join).
2. **Data Wrangling & Cleaning:** Handled missing values, removed duplicate records, reset indices, cleaned and converted `Installs`, `Reviews`, `Price`, `Size` (MB/KB conversion), and `Last Updated` (datetime & update year), and formatted sentiment columns.
3. **Exploratory Data Analysis & Visualization:** Created visualizations following structured univariate, bivariate, and multivariate analysis with chart selection rationale, insights, and business impact for each chart.

## Key Insights
- **Ratings & Sentiment:** Most apps hold high ratings (generally concentrated around 4.0–4.6 with a left-skewed distribution), and user sentiment/polarity helps highlight satisfaction drivers and pain points.
- **Categories & Content Rating:** High-demand categories and broad content ratings (such as `Everyone`) reach wider audiences, whereas niche or restricted categories cater to more specific segments.
- **Pricing & App Size:** Free apps dominate overall volume and accessibility, while smaller-to-moderate file sizes reduce download friction compared to heavy apps.
- **Regular Updates:** Consistent app updates over time reflect active maintenance, which supports quality, user trust, and retention.

## Conclusion
App accessibility, regular maintenance, strong user sentiment, and alignment with user demand play vital roles in sustainable app growth and retention.

## Google Colab Notebook
[Open in Google Colab](https://colab.research.google.com/drive/14UHRXRNhXuPiRKwbyXjAtKWUov2dIOXK?usp=drive_link)
