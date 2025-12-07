

# 🏨 **AtliQ Hotels Data Analysis Project**

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-orange?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualizations-green?logo=plotly)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Viz-teal)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Dataset](https://img.shields.io/badge/Dataset-CSV-blue)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

### 📊 **Overview**

This project performs an end-to-end **data analysis** on hotel booking data from **AtliQ Hotels** to uncover business insights and improve decision-making in hospitality management.

The analysis focuses on:

* Booking trends
* Occupancy rates
* Revenue performance
* Room utilization
* City-wise comparison

---

## 📁 **Project Structure**

```
├── hotels_analysis.ipynb      # Main Jupyter notebook with data analysis
├── data/
│   ├── dim_date.csv
│   ├── dim_hotels.csv
│   ├── dim_rooms.csv
│   ├── fact_aggregated_bookings.csv
│   └── fact_bookings.csv
└── README.md                  # Project documentation
```

---

## 📦 **Datasets Used**

The project utilizes **five CSV files**:

| File Name                      | Description                       |
| ------------------------------ | --------------------------------- |
| `dim_date.csv`                 | Date dimension data               |
| `dim_hotels.csv`               | Hotel information, city, category |
| `dim_rooms.csv`                | Room types & pricing              |
| `fact_aggregated_bookings.csv` | Aggregated booking summaries      |
| `fact_bookings.csv`            | Detailed booking-level records    |

---

## ⚙️ **Technologies Used**

* **Python 3.10+**
* **Libraries:**

  * `pandas`
  * `numpy`
  * `matplotlib`
  * `seaborn`

---

## 🧭 **Analysis Workflow**

### **1️⃣ Data Import & Cleaning**

* Load CSV datasets
* Merge tables into a unified model
* Handle null values and inconsistencies

### **2️⃣ Exploratory Data Analysis**

* Booking trends across time
* City-level performance
* Room category demand
* Yearly, monthly occupancy evaluation

### **3️⃣ Key KPI Calculation**

* **Occupancy Rate**
* **Revenue per Available Room (RevPAR)**
* **Average Daily Rate (ADR)**
* **Booking cancellation trends**

### **4️⃣ Insight Generation**

* Seasonal patterns
* Underperforming cities/hotels
* Revenue strengths & weaknesses

### **5️⃣ Visualization**

* Bar graphs
* Line charts
* Heatmaps
* Revenue trend plots

---

## 📈 **Key Insights (Example)**

✔ Weekends show **20–25% higher occupancy**
✔ Premium rooms generate **maximum revenue**
✔ Off-season dips identified in multiple cities
✔ Certain hotels require optimization in pricing strategies

---

## 💡 **Future Enhancements**

* Develop a **Power BI / Tableau dashboard**
* Create a **Streamlit-based interactive report**
* Add **machine learning forecasting models**
* Automate pipeline using **Airflow / Prefect**

---

## 🚀 **How to Run**

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/atliq-hotels-analysis.git
cd atliq-hotels-analysis
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

### 3. Open the Notebook

```bash
jupyter notebook hotels_analysis.ipynb
```

---

## 🧑‍💻 **Author**

**Mani Chokkara**
📧 Email: **[manichokkara2438@gmail.com](mailto:manichokkara2438@gmail.com)**
🔗 LinkedIn: **[http://www.linkedin.com/in/manichokkara](http://www.linkedin.com/in/manichokkara)**

---


