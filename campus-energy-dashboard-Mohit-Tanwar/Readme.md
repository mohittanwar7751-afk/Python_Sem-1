# 🚀 Campus Energy Dashboard – Capstone Project

## 👤 Student Information
- **Name:** Mohit Tanwar  
- **Roll No.:** 2501730174  
- **Course:** B.Tech CSE (AI & ML)

---

## 📌 Project Overview
This project analyzes electricity consumption across multiple campus buildings using Python, Pandas, Matplotlib, and object-oriented programming.  
It generates cleaned datasets, statistical summaries, visual dashboards, and a final PDF report.

---

## 🗂️ Folder Structure

campus-energy-dashboard-Mohit-Tanwar/
├─ data/            # Raw CSV files for buildings
├─ output/          # Generated plots, cleaned data, summary
├─ docs/            # Final combined PDF report
├─ main.py          # Main project script
└─ README.md        # Project documentation

---

## 📊 Dataset Description
Each `.csv` file in `/data` contains hourly electricity usage for one campus building.

Example format:

timestamp,kwh
2024-01-01 00:00,21
2024-01-01 01:00,25
2024-01-01 02:00,22
…

Included Buildings:
- Admin Block  
- Library  
- Hostel  

---

## ✔️ Features Implemented

### 1️⃣ Data Ingestion & Cleaning
- Reads multiple `.csv` files
- Converts timestamp column to datetime
- Handles missing values
- Saves cleaned file as:

- output/cleaned_energy_data.csv

  ### 2️⃣ Aggregation Logic
- Daily usage using `resample('D')`
- Weekly usage using `resample('W')`
- Building summary (mean, min, max, total)

- output/building_summary.csv
- ### 3️⃣ Object-Oriented Modeling
Classes used:
```python
class MeterReading
class Building
class BuildingManager
```

These encapsulate readings, compute statistics, and generate reports.

4️⃣ Visualization Dashboard

Generated a multi-chart dashboard (dashboard.png) including:
	•	Line chart (daily trend)
	•	Bar chart (weekly averages)
	•	Scatter plot (peak usage)

Saved at:
output/dashboard.png


5️⃣ Summary Report

A summary file is produced automatically:
output/summary.txt
It includes:
	•	Total campus consumption
	•	Highest consuming building
	•	Peak hour and value
	•	Daily and weekly average usage
	•	Insights and recommendations
📈 Key Findings
	•	Total campus consumption: ~620 kWh
	•	Highest consuming building: Hostel
	•	Peak load time: 08:00 AM
	•	Lowest consumption building: Library
	•	Average daily consumption: ~206 kWh

⸻

🧾 Requirements

Install dependencies:
pip install pandas matplotlib

▶️ How to Run
	1.	Place CSV files inside data/
	2.	Run the script:
  python main.py

  3.	Generated files will appear in output/

⸻

📚 Documentation

The full project report (screenshots + theory + conclusion) is located in:
docs/Final_Campus_Energy_Report_Mohit_Tanwar_Combined.pdf

It includes:
	•	Cover page
	•	Introduction
	•	Methodology
	•	Screenshots
	•	Findings
	•	Conclusion

  🔮 Future Enhancements
	•	Real-time readings via IoT sensors
	•	Cloud-based database for energy storage
	•	Streamlit / Dash web dashboard
	•	Automated monthly summary via email

⸻

📌 Academic Declaration

This is an individual academic project submitted by Mohit Tanwar.
All coding and documentation are original and created for educational purposes.

⸻

🙏 Acknowledgements
	•	Pandas documentation
	•	Matplotlib documentation
	•	Assignment guidelines provided by faculty
