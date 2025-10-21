# Dog Bite Cases in India (2018–2025)

### 🧾 Project Overview
Analyzed dog bite cases across Indian states from 2018–2025 using data from government PDFs and data.gov.in datasets.  
Cleaned, merged, and unpivoted the data in Python to identify national and state-wise trends.

### 🧹 Data Cleaning
- Extracted tables from government PDFs using **tabula-py**
- Merged rows by summing values & corrected state names (fuzzy matching)
- Converted wide (pivoted) data into long format using `melt()`

### 📊 Analysis
- Total & Year-over-Year (YoY) cases at national and state level  
- Top and bottom 10 states by total reported cases  
- Trend visualization using **Matplotlib** and **Seaborn**

> Note: 2025 data represents only **January**, not the full year.

### 📁 Project Structure
