# 🚇 Delhi Metro Network - Exploratory Data Analysis (EDA)

This project performs an Exploratory Data Analysis (EDA) of the **Delhi Metro Network** using Python and visualizes key insights with `matplotlib`. The dataset includes details of metro stations and lines, and this notebook helps us understand the layout, distribution, and structure of the metro system.

---

## 📁 Dataset

**File:** `Delhi-Metro-Network.csv`  
**Features may include:**
- Station Name  
- Line Name  
- Latitude & Longitude  
- Interchange Info  

*(Exact columns may vary depending on source)*

---

## 📊 What’s Inside?

- ✅ Data Loading and Cleaning  
- 📌 Missing Value Check  
- 📉 Value Counts of Metro Lines  
- 📍 Station Count per Line (Bar Graph)  
- 🌍 Scatter Plot of Stations (Lat/Lon)
- 🔁 Interchange Station Detection  
- 📈 Custom Graphs using `matplotlib`

---

## 🛠️ Tools & Libraries Used

- Python 🐍
- pandas 🧾
- matplotlib 📊
- Jupyter Notebook 📓

---

## 📷 Sample Visualizations

### 🔸 Stations Per Line
```python
df['Line'].value_counts().plot(kind='bar')
