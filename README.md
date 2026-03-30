# 🌾 Sugarcane Production Analysis

This project analyzes global sugarcane production data to understand crop yield patterns, acreage distribution, and country-wise productivity trends.

---

## 📌 Objective

To explore sugarcane production across countries and continents, identify the major producers, and understand how acreage and yield influence total production.

---

## ❓ Business / Analysis Questions

- Which countries produce the most sugarcane?
- Which continents contribute the highest share of global production?
- Does larger acreage always mean higher production?
- Which countries have the highest yield per hectare?
- How do production, acreage, and yield relate to each other?

---

## 📊 Dataset

- Dataset: `List of Countries by Sugarcane Production.csv`
- Granularity: country-level
- Main columns:
  - Country
  - Continent
  - Production (Tons)
  - Production per Person (Kg)
  - Acreage (Hectare)
  - Yield (Kg / Hectare)

---

## 🧠 Work Done

### 1. Data Cleaning
- Renamed columns for easier analysis
- Removed unused index column
- Converted numeric columns from string format to numeric values
- Handled missing values

### 2. Exploratory Data Analysis
- Country-wise production analysis
- Continent-wise production comparison
- Acreage analysis
- Yield analysis
- Production share analysis
- Relationship analysis using scatter plots

### 3. Visual Analysis
- Bar plots for top producing countries
- Pie charts for production share
- Distribution plots
- Box plots for spread and outliers
- Scatter plots for acreage vs production and yield vs production

---

## 📈 Key Insights

- Brazil and India are the top sugarcane producers in the dataset.
- South America contributes the highest total sugarcane production, followed by Asia.
- Larger acreage generally supports higher production, but yield efficiency also matters.
- Yield per hectare varies strongly across countries, showing that productivity is not only about land size.
- A few countries contribute a very large share of total production compared with the rest.

### Top 5 countries by production

| Rank | Country | Production (Tons) |
|---|---|---:|
| 1 | Brazil | 768,678,382 |
| 2 | India | 348,448,000 |
| 3 | China | 123,059,739 |
| 4 | Thailand | 87,468,496 |
| 5 | Pakistan | 65,450,704 |

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📁 Project Structure

```text
sugarcane-production-analysis/
│
├── README.md
├── requirements.txt
├── .gitignore
├── data/
│   └── List_of_Countries_by_Sugarcane_Production.csv
├── notebooks/
│   └── 01_sugarcane_production_analysis.ipynb
└── images/
```

---

## 🚀 Future Improvements

- Build an interactive dashboard
- Add trend analysis if time-series data becomes available
- Compare sugarcane production with climate or economic indicators
- Build a predictive model for production or yield

---

## 👨‍💻 Author

This project is part of my Data Science / AI-ML portfolio and focuses on extracting meaningful insights from agricultural production data.
