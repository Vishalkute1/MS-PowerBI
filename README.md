# MS-PowerBI
Student Survey Power BI Capstone Project

# 📊 Student Survey Power BI Capstone Project

## 🏬 Industry: Retail | 🧑‍🎓 Target Audience: Students | 🌐 Region: United States

This Power BI project analyzes survey data collected from students across various U.S. retail stores. The aim is to understand student spending behavior on different categories like Video Games, Indoor Games, Outdoor Sports, Books, and more — segmented by age, store setting (Urban/Suburban/Rural), and store location (cities).

---

## 📌 Problem Statement

> Use the "Student Survey" dataset to extract meaningful business insights by creating an interactive and informative Power BI report for retail stakeholders.

---

## 🧩 Key Features & Visualizations

### 1. 🔴🟡🔵 Tabular Visualization (Total Amount of Purchase)
- Based on **Store Location** and **Store Setting**
- Conditional formatting:
  - `0 < TAP < 35,000` → 🔴 Red
  - `35,000 <= TAP < 60,000` → 🟡 Yellow
  - `TAP >= 60,000` → 🔵 Blue

### 2. 🧮 Matrix Visualization (Outdoor Sports Spend)
- Cross-tabbed by **Age** and **Store Setting**
- Color formatting applied to total outdoor sport spending values

### 3. 🔻 Funnel Chart (TAP by Store Setting)
- Funnel format with **Percentage of First** displayed as data labels

### 4. 🥧 Pie Chart (Filtered View)
- Total Amount of Purchase by **Store Location**
- Filter applied: Only **Suburban** store settings

### 5. 🧪 Age-Wise Analysis
- **a)** Scatter Plot: Outdoor Sports vs. Video Games by Age
- **b)** Sand Dance Plot: Indoor Sports vs. Video Games by Age

### 6. 🔒 Row-Level Security (RLS)
- Based on a `User Mapping Table`
- Example: `Mani` can view only **Rural** area data

### 7. ☁️ Power BI Service
- Published to Power BI Cloud
- Master Dashboard: Combines **Funnel** & **Scatter** charts
- Scheduled Refresh: Every 4 hours (6 times a day)

### 8. 💬 Q&A Feature
- a) Show **Average Age** of students using natural language
- b) Donut Chart for **TAP by Store Location**

---

## 🛠️ Tools Used

- **Power BI Desktop & Service**
- **Excel / CSV (Data Preprocessing)**
- **DAX, Power Query**
- **Power BI Row-Level Security (RLS)**
- **Q&A (Natural Language Query)**
- **Power BI Online Scheduling & Publishing**

---

## 📂 Project Structure

```plaintext
📁 StudentSurveyCapstone/
├── StudentSurveryPBIDASHBOARD.pbix      # Power BI file
├── StudentSurveryPBIDASHBOARD.pdf       # Exported report slides
├── Student-Survey/                      # Dataset folder
├── UserMapping.xlsx                     # Mapping table for RLS
└── README.md                            # This file

