# Executive_Board_Meetings_Tracking 📊
 Helping Executive Board to track their meeting recommendations through years 2021/2022

## Introduction
![alt text](<(3) Media/Gifs/Dynamic_dashboard.gif>)

This project was created as a training exercise to simulate a real-world Excel dashboard request from a business executive team. The goal was to build a dynamic and visually engaging tool for tracking recommendations made during board meetings — helping leadership monitor execution progress, priorities, and departmental responsibilities.

---

## 🎯 Project Scope

The dashboard is designed to address the following:

### 🔧 Data Structure Enhancements
The raw data was enhanced with new columns to better track and analyze recommendations:
- **Status** *Dropdown* (Completed / In Progress / Not Started)
- **Execution Date**
- **Responsible Department**
- **Recommendation Impact**
- **Notes**
- **Priority** *Dropdown* (High / Medium / Low)
- **Completion Rate (%)**
- **Attachments/Links**

### 📊 Dashboard Features
- **Status breakdown** of all recommendations
- **Priority and department distribution**
- **Execution timeline** trends
- **Filtering options** by status, department, and meeting date
- **Printable summary report** with delayed or high-priority items

---

## ⚙️ Tools Used
- Data Validation
- PivotTables & PivotCharts
- Slicers and conditional formatting
- Various functions to help with filling, cleaning, and filtering data
[**Randbetween**, **countif**, **filter**, *etc...*]

---
## Dashboard File
[You can check the dashboard Excel file from here](./(2)%20In%20Progress/)

[You can also check the original excel file (before editing) from here](./(1)%20Source/)

---
## Dashboard build
### Cleaning and Optimizing the table

![alt text](<(3) Media/Gifs/Transition.gif>)

I began by adding the required columns and populated the dataset using the `RANDBETWEEN` function to simulate realistic data.

This approach ensured there was enough variety to properly demonstrate dashboard functionality and interactivity.

---
### Data Validation & Dropdown columns & Conditional Formatting

![alt text](<(3) Media/Gifs/Data_Validation.gif>)

Using **Data Validation**, I created dropdown menus for key fields like **Priority** and **Status**. This improves data entry by:
- Reducing human error
- Enforcing consistency
- Making the dataset easier to analyze later

I also applied **Conditional Formatting** to visually flag key values and statuses at a glance.

---
### Summary Report

![alt text](<(3) Media/Still_Images/summary_report.png>)

One of the requirements was a **printable, dynamic summary page** to give decision-makers a quick overview of key metrics.

I used functions like `FILTER`, `COUNTIF`, `AVERAGE`, and `AVERAGEIF` to automate KPI tracking.  
The result is a page that updates automatically as the main dataset changes no manual recalculations needed.

---
### Dynamic Dashboard & Slicers

![alt text](<(3) Media/Gifs/Dynamic_dashboard.gif>)

Using **PivotTables**, **PivotCharts**, and **Slicers**, I built a fully interactive dashboard. Users can filter by department, status, or date to focus on the information that matters most.

Since it's powered by PivotTables and formulas, the dashboard automatically reflects any updates made to the original database

![alt text](<(3) Media/Gifs/Dynamic_KPI.gif>)
---

## 🧠 Conclusion

This project was an excellent opportunity to simulate a real-world Excel dashboarding task from start to finish — from data structure planning and validation to creating a fully dynamic and interactive reporting tool.

It helped reinforce best practices in Excel, like clean data design, automation with formulas, and visual storytelling through dashboards.

Whether used for executive tracking or personal training, this project showcases how Excel can still be a powerful tool for data analysis and communication.

---