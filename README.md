# 🚗 Uber Trip Analysis

![Python](https://img.shields.io/badge/python-3.12-blue)
![Pandas](https://img.shields.io/badge/pandas-%3E%3D1.5.0-brightgreen)
![Matplotlib](https://img.shields.io/badge/matplotlib-%3E%3D3.0-orange)

## 📌 Project Overview
Exploratory Data Analysis (EDA) on Uber trip data to uncover trends in trip distances, timing, and categories.  
This project uses **statistics, probability, and feature engineering** to generate actionable insights for operations and business strategy.

---

## 📂 Dataset
**Dataset:** `myuber.csv` – Uber trip records  

**Key Features:**

| Column         | Description |
|----------------|-------------|
| `TRIP_ID`      | Unique trip identifier |
| `START_DATE*`  | Trip start timestamp |
| `END_DATE*`    | Trip end timestamp |
| `CATEGORY*`    | Trip type (UberX, UberPool, etc.) |
| `MILES*`       | Distance of trip in miles |
| `PURPOSE*`     | Trip purpose |
| `CITY*`        | Trip city |

---

## 📊 Analysis Highlights
- **Data Cleaning:** Handled missing values, duplicates, and formatting issues.  
- **EDA:** Histograms, scatter plots, boxplots; outlier detection; peak hours analysis.  
- **Probability:** Likelihood of long-distance trips; peak time identification.  
- **Feature Engineering:** Extracted Hour, Day, Month; aggregated metrics like total miles per category.

---

## 📈 Visualizations

**Total miles traveled by category**  
<img width="589" height="502" alt="image" src="https://github.com/user-attachments/assets/28a24617-ddae-4d48-a459-a20036f4568d" />


**TOTAL MILES PER MONTH**  
<img width="580" height="455" alt="image" src="https://github.com/user-attachments/assets/69ad1c59-53b1-4632-9707-8cf157f3c99c" />


**Top 5 Trip Purposes**  

<img width="571" height="550" alt="image" src="https://github.com/user-attachments/assets/b188ee0d-142b-44d9-9bde-49e075d56f84" />


## 📌 Conclusion & Insights

Trip Distance vs Time of Day → Most trips are short (<10 miles); longer trips occur during off-peak hours.

Category Analysis → UberX dominates the dataset; other categories like UberPool have lower frequency.

Peak Hour Analysis → Early mornings and evenings have the highest number of trips, indicating demand patterns.

## ✅ Business Takeaways

Optimize Driver Allocation → Focus on high-demand hours and areas to improve service efficiency.

Pricing Strategy → Adjust pricing based on trip distance distribution and category usage.

Category-Based Insights → Promote underutilized categories like UberPool to balance demand.
