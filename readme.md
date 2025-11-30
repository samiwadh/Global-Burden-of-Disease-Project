# Global and Italy SDI Analysis (1950–2021)

This project explores the **Socio-Demographic Index (SDI)** from 1950 to 2021 using a Kaggle SDI dataset. It includes both global-level analysis and a detailed Italy-focused study. The goal is to understand long-term changes in development, inequality patterns, global rankings, and Italy’s position compared to other countries.

The project involves data cleaning, time-series transformations, rolling averages, peer comparison, and more than 12 visualizations that tell a complete development story.

---

## Dataset

**Source:** [Institute for Health Metrics and Evaluation data (GBD 2021 SDI)](https://ghdx.healthdata.org/record/global-burden-disease-study-2021-gbd-2021-socio-demographic-index-sdi-1950–2021)  
**Contents:**
- SDI values for all countries
- Yearly data from 1950–2021
- Clean, numeric, ready-to-analyze data

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Plotly (for geo visualization)  
- Statsmodels (optional ARIMA modeling)  

---

##  Data Preparation Steps
1. Cleaned and normalized column names  
2. Converted `year` into integer format  
3. Selected key variables: `location`, `year`, `SDI`  
4. Removed missing values  
5. Sorted data for time-series analysis  
6. Created additional features:
   - Year-to-year SDI difference  
   - 5-year rolling mean  
   - 10-year rolling mean  
   - Global rankings  
   - Peer group averages  

---

## Visualizations Included

### 🌍 Global Analysis
- **Global SDI Trend (1950–2021):** Shows how average SDI improved worldwide over seven decades.  
- **Distribution of SDI Across Countries (2021):** Understand global inequality and variation in development.  
- **Top 10 Countries by Total SDI Change:** Identifies countries contributing most to global SDI growth.  
- **SDI Heatmap for Selected Countries:** Highlights long-term development trajectories for major nations.  
- **SDI Quintile Area Plot Over Time:** Shows global inequality trends and country movements across quintiles.  
- **Year-to-Year SDI Difference:** Measures how SDI changes annually across all countries.  

### 🇮🇹 Italy-Focused Analysis
- **Italy SDI Trend (Observed + Rolling 5 & 10 years):** Shows smoothed long-term patterns and short-term fluctuations.  
- **Italy SDI Distribution (Histogram + KDE):** Reveals how Italy’s SDI values are spread over 70+ years.  
- **Italy SDI Boxplot:** Highlights median, variability, and outliers.  
- **Italy Global Ranking Over Time:** Shows how Italy’s position changed compared to all other countries.  
- **Italy vs Selected Asian Countries:** Compares Italy’s development with China, India, Pakistan, Bangladesh, Thailand, Malaysia, Singapore, and Iran.  
- **Italy vs Peer-Group Average:** Shows whether Italy performs above or below the average of selected peers.  

---

## Key Insights
- Global SDI has steadily improved from 1950–2021, showing long-term progress.  
- Inequality between SDI quintiles is decreasing as more countries move into higher development groups.  
- Italy shows a consistent upward SDI trend, especially after the 1980s.  
- Italy remains in the top global ranks, although its relative ranking fluctuates slightly over decades.  
- Compared to Asian peers, Italy stays ahead for most years but faces strong growth from countries like China and Malaysia.  
- Rolling averages indicate Italy’s development pattern is stable and smooth, with no major long-term declines.  

---

## Skills Demonstrated
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Time-series analysis  
- Rolling averages and trend estimation  
- Country ranking algorithms  
- Multi-country comparison visualization    
- Clear interpretation of development metrics  

---

## 📌 Purpose of the Project
To analyze long-term socio-demographic trends globally and for Italy, highlight inequality changes, understand development patterns, and provide data-driven insights for policy, research, and comparative
