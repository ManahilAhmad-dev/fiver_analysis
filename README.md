# Fiverr Dataset — Data Cleaning & Exploratory Data Analysis

This project focuses on cleaning, exploring and visualizing data from the freelancing platform **Fiverr**.  
It covers:

- ✅ Data Pre-processing & Cleaning  
- ✅ Exploratory Data Analysis (EDA) of gig categories, pricing, ratings and reviews  
- ✅ Visual insights & key business observations

---

## Project Workflow

1. **Data Pre-processing**  
   - Imported libraries and loaded raw dataset.  
   - Inspected dataset shape, missing values and column info.  
   - Cleaned column names, stripped extra spaces.  
   - Removed duplicate rows.  
   - Parsed star ratings and review counts from text.  
   - Handled missing values (dropped columns >35% missing, filled mode/median).  
   - Converted price strings to numeric and filtered unrealistic values.  
   - Converted rating/review columns to numeric and removed outliers using IQR.  
   - Saved cleaned dataset for analysis.

2. **Exploratory Data Analysis (EDA)**  
   - Identified key columns dynamically for price, category, rating and review count.  
   - Computed average price by service category.  
   - Visualized top categories by average price (bar chart).  
   - Visualized skill/ sub-category distribution (pie chart).  
   - Computed correlations (price vs rating, price vs review count).  
   - Simulated monthly trend of average gig price.  
   - Identified top-profitable categories using a combined metric of mean price and count.

---

## Results & Insights

- The dataset comprises ~6,183 rows (pre-cleaning) covering various Fiverr service categories.  
- Major categories (Programming & Tech, Graphic Design, Business) dominate both in volume and average price.  
- There is **weak correlation** between gig price and rating — price alone doesn’t guarantee higher rating.  
- Moderate correlation between price and review count — more reviewed gigs tend to charge more.  
- Outlier removal improved clarity of insights and representation of typical market behaviour.

---

## Tech Stack

- Python (pandas, numpy, matplotlib, seaborn, scipy)  
- Jupyter Notebook  
- Git & GitHub for version control  

---

## Dataset

- **Original file:** `fiverr.csv`  
- **Cleaned file:** `fiverr_cleaned.csv`  
- **Notebook:** `Fiver_Analysis.ipynb`  
- **Report:** `Report_of_fiverr_analysis.pdf`

---

## Author

**Manahil Ahmad**  
Data Analysis Internship Project — Fiverr Freelance Data Analysis

---

## License

[MIT](LICENSE)
