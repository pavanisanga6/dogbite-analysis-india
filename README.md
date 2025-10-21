# 🐶 Dog Bite Cases in India (2018–2025)

### 📊 Project Overview
Analyzed dog bite cases across Indian states from **2018–2025** using data from **data.gov.in** and **Rajya Sabha reports (PDFs)**.  
The goal was to identify **national and state-wise trends**, compute **year-over-year (YoY)** changes, and highlight top and bottom performing states in reported cases.

---

### 🧹 Data Cleaning
- Extracted tables from government PDFs using **tabula-py**
- Merged state-wise rows using fuzzy matching and manual corrections
- Transformed wide (pivoted) data into long format using **`pandas.melt()`**
- Standardized column names and handled missing values

---

### 🔍 Analysis
- Computed **total cases** and **YoY% change** (both national & state-level)
- Identified **Top 10** and **Bottom 10** states by total dog bite cases
- Visualized yearly and state-wise trends using **Matplotlib** & **Seaborn**

---

### 📈 Key Insights
- National dog bite cases show a sharp **decline after 2019**, likely influenced by the **COVID-19 lockdown period (2020–2022)**.
- A **recovery trend** is visible post-2023.
- **Bihar, Andhra Pradesh, and Gujarat** consistently report high numbers.
- **2025** data represents **January only** (partial year).

---

### 🗂️ Project Structure
├── 1. Data/
│   ├── Raw Datasets (PDFs, CSVs)
│   └── Cleaned Data
│
├── 2. Notebooks/
│   └── Dogbites_India.ipynb
│
├── 3. Images/
│   ├── yearly_trend.png
│   ├── top10_states.png
│   └── bottom10_states.png
│
├── 4. Outputs/
│   ├── yearly_totals.csv
│   ├── top10_states.csv
│   └── bottom10_states.csv
│
├── requirements.txt
└── README.md



---

### ⚙️ Tools & Libraries
- **Python** (pandas, matplotlib, seaborn, tabula-py)
- **Jupyter Notebook**
- **GitHub** for version control

---

### 📬 Credits
Data Source: [data.gov.in](https://data.gov.in) | Rajya Sabha Parliamentary PDFs  
Developed by: **Pavani Sanga**

---

### 🏁 Next Steps
- Extend analysis to include **population-adjusted bite rates**
- Integrate **geospatial (GIS)** maps for visualizing hotspots
- Build a **dashboard** in Power BI or Tableau
