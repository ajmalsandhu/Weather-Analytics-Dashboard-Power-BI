# 🌤 Weather Analytics Dashboard (Power BI)

A fully interactive Weather Analytics Dashboard built in Power BI using live API data.

This dashboard provides real-time weather insights, 7-day forecast analysis, and air quality monitoring for multiple cities.

---

## 📊 Features

- Current Weather Overview
- 7-Day Forecast Trend Visualization
- Sunrise & Sunset Tracking
- Air Quality Index (AQI) Monitoring
- Rain Probability Analysis
- Multi-City Selection (Lahore, Islamabad, Karachi, Murree etc.)
- Automated Data Refresh Handling
- Error-Resilient API Data Processing

---

## 🛠 Tools & Technologies

- Power BI Desktop
- Power Query (ETL Processing)
- REST Weather API
- DAX (Data Analysis Expressions)
- Data Cleaning & Error Handling Techniques

---

## ⚙ Data Processing Approach

Since live APIs can return incomplete or malformed data, the following production-level techniques were implemented:

- Error replacement instead of row deletion
- Removal of cyclic query dependencies
- Controlled data type handling
- Safe refresh architecture
- Multi-query dependency management

This ensures the dashboard refreshes reliably even if the API returns partial data.

---

## 📈 Key Insights Provided

- Daily temperature trend comparison
- Humidity, Wind Speed, Pressure, Visibility metrics
- UV Index tracking
- Air Quality breakdown (PM10, PM2.5, O3, CO, NO2)
- Rain probability visualization

---

## 📷 Dashboard Preview

![Dashboard Preview](screenshots/dashboard.png)

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Update API key (if required)
4. Click Refresh

---

## 📌 Project Highlights

- Designed with clean UI/UX principles
- Handles API refresh errors gracefully
- Structured data model architecture
- Optimized for scalability

---

## Notes
- The data utilized is for demonstration purposes.
- This project showcases Power BI expertise through the development of a live Weather API dashboard featuring real-time insights, forecast analysis, and robust data handling.
