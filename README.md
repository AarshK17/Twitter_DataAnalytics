# 📊 Twitter Analytics Dashboard - Power BI Project

This project is a Power BI-based analysis of Twitter engagement data. It focuses on understanding user interactions such as clicks, media engagement, and app opens using advanced filtering, drill-downs, and dynamic visuals.

---

## 🧠 Project Overview

The dashboard provides detailed insights into:
- Types of clicks (URL, profile, hashtag) for high-impression tweets
- Relationship between media engagements and media views
- Engagement comparison between tweets with and without app opens

---

## 🎯 Learning Objectives

- Master Power BI data transformation using Power Query
- Implement DAX for conditional formatting and time-based visibility
- Create dynamic dashboards that respond to time and content filters
- Build drill-down charts and multi-level filtering

---

## ⚙️ Features and Tasks

### ✅ Task 1: Pie Chart with Drill-down
- Visualizes the **proportion of total clicks** for tweets with **>500 impressions**
- Drill-down to view **click type breakdown** (URL, profile, hashtag) per tweet

### ✅ Task 2: Conditional Scatter Chart
- Shows the **relationship between media engagements and views**
- Filters applied:
  - Tweets with **>10 replies**
  - **Odd-numbered tweet dates**
  - **Word count > 50**
  - Displayed **only from 6 PM to 11 PM IST**
  - Tweets with **engagement rate > 5%** are highlighted

### ✅ Task 3: Engagement Rate Comparison
- Compares tweets **with vs without app opens**
- Filters applied:
  - Posted **between 9 AM and 5 PM on weekdays**
  - Only shown from **12 PM–6 PM** and **7 AM–11 AM IST**
  - **Even impressions**, **odd tweet dates**, and **character count > 30**
  - **Words containing 'D' removed** from tweet text

---

## 🛠 Tools & Technologies

- **Power BI**
- **Power Query** for data cleaning
- **DAX** for custom measures and conditional visuals
- Time-based logic (IST conversion)

---

## 🔍 Skills Demonstrated

- Data Modeling and Transformation
- Conditional Chart Rendering using DAX
- Custom Columns for Odd/Even Logic
- String Filtering in Power Query
- Time Intelligence in Power BI

---

## 🧩 Challenges & Solutions

| Challenge | Solution |
|----------|----------|
| Odd/Even filtering on dates and impressions | Used `MOD()` and `DAY()` DAX functions |
| Time-based chart visibility | DAX + `TIME()` logic with UTC to IST conversion |
| Removing words with 'D' | Power Query custom M functions |
| Calculating engagement rate safely | Custom DAX with error handling for 0 impressions |

---

## 📈 Outcomes and Impact

- Revealed top-performing tweet strategies
- Identified tweet formats that drive engagement
- Emphasized the role of timing and content length in performance
- Enhanced dashboard interactivity with dynamic visual visibility

---

## 📄 Report

A complete Word report is available for download covering:
- Introduction
- Tasks and Implementation
- Skills Used
- Challenges and Outcomes  
👉 [Download Word Report](./Twitter_Analytics_PowerBI_Report.docx)

---

## 📸 Screenshots

> <img width="500" height="282.98" alt="trainingProject" src="https://github.com/user-attachments/assets/acfb1f43-c977-43d6-ad97-ff3dc5774df2" />
> <img width="500" height="282.98" alt="task1" src="https://github.com/user-attachments/assets/6e4b5a7f-e5bb-4db1-97b3-cf41695c891c" />
> <img width="500" height="282.98" alt="task2" src="https://github.com/user-attachments/assets/033a9c8e-3327-4603-b781-76b859ff8df9" />
> <img width="500" height="282.98" alt="task3" src="https://github.com/user-attachments/assets/4be52fe9-4f8f-487a-89d9-be84bb30a9b4" />






---

## 📬 Feedback and Future Work

Your feedback is welcome! Future improvements could include:
- Real-time Twitter API integration
- Sentiment analysis
- Keyword frequency trends

---

## 👩‍💻 Author

**Aarsh Khadgi**  
Power BI Enthusiast | Data Visualization & Social Media Analytics

---

## 📄 License

This project is licensed under the [NullClass Edtech Private Limited](LICENSE).


