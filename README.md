Below is your **professional, polished, recruiter-friendly `README.md`** for your **Movie Sales Analysis Dashboard (Power BI)** project ✅

---

# 🎬 Movie Sales Analysis Dashboard

**Power BI | IMDb Movie Analytics | Data-Driven Insights**

![Power BI Badge](https://img.shields.io/badge/Tool-PowerBI-F2C811?style=for-the-badge\&logo=powerbi\&logoColor=black)
![Domain](https://img.shields.io/badge/Domain-Data%20Analytics-blue?style=for-the-badge)
![Business Intelligence](https://img.shields.io/badge/Focus-Business%20Intelligence-green?style=for-the-badge)

---

## 📌 Project Overview

This project presents a **Power BI dashboard** built to analyze **movie performance** using IMDb-based data.
It offers insights into global box-office revenue, movie ratings, genre trends, and industry patterns over time.

The goal is to help stakeholders—producers, investors, and analysts—**understand market trends and make data-driven decisions** in film production and distribution.

---

## 🎯 Business Problem

Movie studios struggle to forecast success due to uncertain audience preferences & unpredictable industry trends.

### **Objective:**

Use data analytics to identify **what drives movie success** based on
✅ Revenue
✅ Genre
✅ Ratings
✅ Release patterns
✅ Cast & crew impact

---

## 🧠 Key Features & Insights

### 📊 Dashboard Insights

| Feature                       | Description                                        |
| ----------------------------- | -------------------------------------------------- |
| 💰 Total Revenue              | Global box-office performance KPI                  |
| 🎟️ Top-Grossing Movies       | Highest revenue films                              |
| 🎭 Genre Analysis             | Most successful genres by revenue & average rating |
| ⭐ Ratings Distribution        | Visualize IMDb rating patterns                     |
| 👨‍🎤 Cast/Director Influence | Top actors/directors by movie earnings             |
| 📅 Release Trend Analysis     | Year-wise movie releases & revenue growth          |
| 🏳️ Country Analysis          | Country-wise film market performance               |

### 🎛️ Filters Applied

Genre | Year | Country | Actor | Director | Rating range
*(interactive & user-friendly slicers)*

---

## 📂 Dashboard Pages

| Page                      | Details                              |
| ------------------------- | ------------------------------------ |
| 📌 Overview Dashboard     | KPIs, Revenue, Top movies            |
| 🎭 Genre Analysis         | Genre performance insights           |
| 💹 Revenue vs Ratings     | Correlation visuals & scatter charts |
| 📈 Trends & Time Analysis | Year-wise releases & revenue growth  |

---

## 📊 Data Source & Preparation

### 📁 Dataset

* IMDb / Movies dataset *(placeholder dataset info)*
* Format: Excel/CSV

📎 **Dataset placeholder path**

```
/data/movies_dataset.xlsx
```

### 🧼 Data Cleaning (Power Query)

* Removed nulls & duplicates
* Standardized date & numeric formats
* Cleaned genre & country fields
* Extracted year from release date

---

## 🧮 DAX Measures Used

Example key DAX metrics:

**Total Revenue**

```DAX
Total Revenue = SUM(Movies[Revenue])
```

**Average Rating**

```DAX
Avg Rating = AVERAGE(Movies[Rating])
```

**Revenue Rank**

```DAX
Revenue Rank = RANKX(ALL(Movies), [Total Revenue], , DESC, Dense)
```

**Movies Released Per Year**

```DAX
Movies Count = COUNT(Movies[MovieID])
```

---

## 📁 Project Structure

```bash
Movie-Sales-Dashboard/
│── data/
│   └── movies_dataset.xlsx
│── pbix/
│   └── movie_sales_dashboard.pbix
│── screenshots/
│   └── dashboard_overview.png
│── README.md
```

---

## 🛠️ Tools & Technologies

| Tool        | Purpose             |
| ----------- | ------------------- |
| Power BI    | Dashboard & DAX     |
| Power Query | Data cleaning & ETL |
| Excel / CSV | Data Source         |

---

## 🚀 Installation & Usage

### 📥 Requirements

* Power BI Desktop installed
* Dataset file *(provided in repo)*

### ▶️ Run the Project

1. Clone/download the repo
2. Open `.pbix` file in Power BI
3. Refresh data connection if required
4. Explore dashboards & insights

---

## 📸 Screenshots

> *(Insert your dashboard visuals here)*

📍 Overview Dashboard
`/screenshots/overview.png`

📍 Genre Insights
`/screenshots/genre.png`

📍 Revenue vs Rating
`/screenshots/revenue_rating.png`

---

## 🎤 Demo Video *(Optional)*

🎥 *Add video link here*
`[YouTube Demo Placeholder]`

---

## 🚧 Future Improvements

| Feature                      | Goal                                     |
| ---------------------------- | ---------------------------------------- |
| 📌 Machine Learning Forecast | Predict revenue trends & hit probability |
| 📌 Advanced NLP              | Analyze reviews & sentiment              |
| 📌 Drill-through Pages       | Actor / Director deep-dive               |
| 📌 Auto-Refresh Data         | Connect to live IMDb API                 |
| 📌 Story-telling Mode        | Guided insights experience               |

---

## 🏆 Key Highlights

| Skill         | Demonstration                |
| ------------- | ---------------------------- |
| Power BI      | Reports, dashboards, slicers |
| DAX           | Measures, time intelligence  |
| Data Modeling | Star schema, relationships   |
| ETL           | Power Query transformations  |
| Analytics     | KPI-driven business insights |

---

## 👨‍💻 Author

**Pruthviraj Patil**
📍 Pune, Maharashtra
📧 `pruthvipatil26@gmail.com`
🔗 LinkedIn: `linkedin.com/in/yourprofile`

---

## ⭐ Support

If this project helped you, please **⭐ Star the repository!**

---


