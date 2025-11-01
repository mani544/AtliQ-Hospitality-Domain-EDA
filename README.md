# 🏨 AtliQ Hotels Data Analysis Project

### 📊 Overview

This project performs an end-to-end **data analysis** on hotel booking data from **AtliQ Hotels** to uncover business insights and improve decision-making in hospitality management.
The analysis focuses on understanding booking trends, occupancy rates, revenue performance, and key operational metrics.

---

## 📁 Project Structure

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

## 📦 Datasets Used

The project utilizes **five CSV files** as input:

* `dim_date.csv` — Contains date dimension data
* `dim_hotels.csv` — Hotel information and attributes
* `dim_rooms.csv` — Room category and pricing information
* `fact_aggregated_bookings.csv` — Aggregated booking summaries
* `fact_bookings.csv` — Detailed booking records

---

## ⚙️ Technologies Used

* **Python 3.10+**
* **Libraries:**

  * `pandas` – for data manipulation and cleaning
  * `numpy` – for numerical computation
  * `matplotlib` & `seaborn` – for visualization and trend analysis

---

## 🧭 Analysis Workflow

1. **Data Import & Cleaning**

   * Read CSV files and merge datasets
   * Handle missing values and inconsistent data

2. **Exploratory Data Analysis (EDA)**

   * Visualize booking trends over time
   * Identify top-performing hotels and room categories
   * Calculate key KPIs such as occupancy rate, revenue per available room (RevPAR), etc.

3. **Insight Generation**

   * Compare performance across cities and time periods
   * Detect seasonal patterns and customer preferences

4. **Visualization & Reporting**

   * Generate clear visual insights using bar plots, heatmaps, and line charts

---

## 📈 Key Insights (Example)

* Weekends show a 20–25% increase in occupancy compared to weekdays.
* Premium rooms contribute the highest share of total revenue despite lower booking frequency.
* Certain cities show underutilized room capacity during off-seasons.

---

## 💡 Future Enhancements

* Add **interactive dashboards** using Power BI or Streamlit.
* Automate data pipeline for **real-time analytics**.
* Apply **machine learning models** for demand forecasting.

---

## 🚀 How to Run

1. Clone this repository

   ```bash
   git clone https://github.com/<your-username>/atliq-hotels-analysis.git
   cd atliq-hotels-analysis
   ```
2. Install dependencies

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open and run the Jupyter Notebook

   ```bash
   jupyter notebook hotels_analysis.ipynb
   ```

---

## 🧑‍💻 Author

**Mani Chokkara**
📧 [[manichokkara2438@gmail.com](mailto:manichokkara2438@gmail.com)]
🔗 [LinkedIn Profile:http://www.linkedin.com/in/manichokkara]

---


