# ✈️ Airlines Data Analysis Using SQL and Python

## 📌 Project Overview

This project focuses on analyzing airline data to identify ways to **increase occupancy rates** and **boost annual turnover**. It uses **SQL for querying a travel database** and **Python (Pandas, Matplotlib)** for data processing and visualization.

The analysis is designed to help airlines:
- Maximize profitability
- Adjust pricing strategies
- Enhance customer experience
- Make data-driven decisions

---

## 📊 Business Problem

The airline operates a diverse fleet and faces rising challenges such as:
- Stricter environmental regulations
- Increased taxes and fuel costs
- Labor shortages and higher wages

These issues have reduced profitability. To counter this, the airline wants to analyze seat occupancy, revenue, and pricing trends to uncover areas of improvement.

---

## 🎯 Objectives

- ✅ **Increase Seat Occupancy**  
  Improve average seats filled per flight to increase revenue and reduce losses from empty seats.

- ✅ **Revise Pricing Strategy**  
  Develop pricing models that are attractive yet profitable based on aircraft type and class.

- ✅ **Maintain Quality Experience**  
  Improve occupancy without affecting safety or passenger comfort.

---

## 🗃️ Dataset Overview (`travel.sqlite`)

| Table Name         | Description                              | Rows     | Columns |
|--------------------|------------------------------------------|----------|---------|
| `aircrafts_data`   | Info about aircraft types                 | 9        | 3       |
| `airports_data`    | Airport metadata                         | 104      | 5       |
| `boarding_passes`  | Boarding records per flight              | 579,686  | 4       |
| `bookings`         | Booking transactions                     | 262,788  | 3       |
| `flights`          | Flight schedule and aircraft info        | 33,121   | 10      |
| `seats`            | Seat details for each aircraft           | 1,339    | 3       |
| `ticket_flights`   | Mapping between tickets and flights      | 1,045,726| 4       |
| `tickets`          | Ticket-level passenger and fare info     | [Not listed] | [Not listed] |

---

## 🛠️ Tools & Technologies Used

- **SQLite3** for SQL querying
- **Python 3 (Jupyter Notebook)** for data manipulation
- **Pandas** for data analysis
- **Matplotlib/Seaborn** for data visualization

---

## 📈 Key Insights

- Aircrafts like **SU9** generate high revenue despite lower ticket prices, suggesting strong demand.
- **CN1** had the lowest revenue, likely due to limited class options and lower demand.
- A 10% increase in occupancy rate could lead to a significant **increase in total annual turnover**.

---

## 🧮 Main Calculations

- **Occupancy Rate** = (Average Booked Seats per Flight) / (Total Seats in Aircraft)
- **Expected Revenue with 10% Boost** =  
  \[(Total Revenue ÷ Current Occupancy Rate) × Increased Occupancy Rate\]

---

## 📄 Files Included

- `AIRLINES_Data_Analysis_Using_SQL_and_Python.ipynb` — Jupyter Notebook with all analysis, SQL queries, and plots.
- `Report(Airlines).pdf` — Final report summarizing business problem, challenges, visualizations, and insights.

---

## ✅ Conclusion

Analyzing ticket sales, pricing, and occupancy data helps airlines:
- Identify underperforming aircraft
- Set better fares
- Increase profits without compromising service

A **data-driven strategy** can help airlines navigate rising costs and remain competitive.

---

## 📬 Contact

For feedback or questions, feel free to reach out!

