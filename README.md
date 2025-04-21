# 🚴‍♀️ Ford GoBike Data Visualization Project

## 📌 Project Overview

This project explores the **Ford GoBike System Dataset** through both **exploratory** and **explanatory** data visualizations. Created as part of a data visualization course, the project is split into two parts:

- **Part I: Exploratory Visualization**  
  Using Python libraries to analyze trends, patterns, and distributions across variables in the dataset.
  
- **Part II: Explanatory Visualization**  
  Communicating key findings through clean, effective visuals focused on storytelling and insights.

---

## 📁 Dataset Description

The dataset contains trip-level information including:

- `duration_sec`: Length of trip in seconds  
- `start_time`, `end_time`: Timestamps of trip start and end  
- `start_station_*`, `end_station_*`: Location info (IDs, names, coordinates)  
- `bike_id`: Unique identifier for each bike  
- `user_type`: Either `Subscriber` or `Customer`  
- `member_birth_year`, `member_gender`: Demographics  
- `bike_share_for_all_trip`: Whether the trip was shared

---

## 🧹 Data Wrangling Steps

- Removed rows with missing values in key columns:
  - `member_birth_year`, `member_gender`
  - `start_station_name`, `end_station_name`
  - `start_station_id`, `end_station_id`
- Converted:
  - Birth year to `int`
  - Time columns to `datetime`

---

## 🔍 Summary of Findings

This analysis compared usage patterns between **Subscribers** and **Customers**. Notable observations:

-  **Subscribers dominate the user base** (~90%)
-  Most trips are **under 20 minutes**
-  **Weekdays see higher usage**, especially during **6–8 AM** and **3–5 PM**
-  **Customers are more active on weekends**
-  Majority of users are in their **30s**
-  **Males are the majority**, with females making up about one-third
-  **Shared trips are rare**, and not used by Customers
-  **Trip distance and duration are positively correlated**
-  Both user types rarely exceed **8 km**
-  **Subscribers take shorter, more consistent trips**; Customers have **wider variation**
-  **Long trips are more common during commute hours**
-  **Thursday has the most trips** in the 5–10 minute range

---

## 📌 Key Insights for Presentation

- 📊 **Age & User Type**: Majority of users are in their 30s → Visualize age distribution by user type  
- 🚻 **Gender Breakdown**: Males dominate → Compare usage by gender  
- ⏰ **Peak Hours**: High usage during 6–8 AM and 3–5 PM → Show dominant user type per hour

---

## 🐍 Tools Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `datetime`

---

## 🧠 Author

**SAUD ALSHUSHAN**  
Created as part of a data visualization course project using the Ford GoBike dataset

---
