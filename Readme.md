# ☕ Starbucks Analytics Dashboard

> **"Brewing Insights. Fueling Connections."**
> An end-to-end Business Intelligence project analyzing Starbucks' global store presence and complete beverage nutrition portfolio — built with **Microsoft Power BI** and **Canva UI Design**.

---

## 🚀 Project Overview

This project simulates a real-world data analyst role in the FMCG / Food & Beverage industry. Using two rich datasets covering Starbucks' menu nutrition data and worldwide store directory, I designed a fully interactive Power BI dashboard that helps stakeholders understand beverage performance, nutritional patterns, global expansion, and customer health insights.

The goal: answer the kind of questions a **product team, nutritionist, or business strategist** at Starbucks would actually ask.

---

## 📊 Dataset Summary

| Dataset | File | Records |
|---|---|---|
| **Beverage Nutrition** | `starbucks.csv` | 242 beverages |
| **Global Store Directory** | `directory.csv` | 25,600+ stores |

### 🗂️ Schema

**`starbucks.csv` — Nutrition Data**
| Column | Description |
|---|---|
| `Beverage_category` | High-level category (Coffee, Frappuccino, Smoothies, etc.) |
| `Beverage` | Specific drink name |
| `Beverage_prep` | Size/preparation (Short, Tall, Grande, Venti, etc.) |
| `Calories` | Total calories (kcal) |
| `Total Fat (g)` | Fat content in grams |
| `Sugars (g)` | Sugar content in grams |
| `Protein (g)` | Protein content in grams |
| `Caffeine (mg)` | Caffeine content in milligrams |
| `Sodium (mg)` | Sodium content |
| `Vitamin A/C, Calcium, Iron` | Micronutrient % daily values |

**`directory.csv` — Global Store Data**
| Column | Description |
|---|---|
| `Store Number` | Unique store identifier |
| `Store Name` | Name of the outlet |
| `Ownership Type` | Company Owned / Licensed / Joint Venture / Franchise |
| `Street Address / City / Country` | Location details |
| `Longitude / Latitude` | Geo-coordinates for map visuals |

---

## 📈 Key Metrics at a Glance

| KPI | Value |
|---|---|
| **Total Beverage Types** | 33 |
| **Total Beverage Categories** | 9 |
| **Average Calories** | 194.30 kcal |
| **Average Sugar** | 33.02g |
| **Average Caffeine** | 81 mg |
| **Total Global Stores** | 25,600+ |
| **Countries Present** | 73 |

---

## 🔍 Key Insights Uncovered

- **Smoothies are the most calorie-dense** category at 282 kcal average — higher than Frappuccinos
- **Brewed Coffee has the highest caffeine** at 294mg average — nearly 2.4x the overall average
- **White Chocolate Mocha** is the highest calorie single beverage at **510 kcal**
- **Tazo® Tea** is the lowest calorie option at **0 kcal** — ideal for health-conscious customers
- **Top 5 highest caffeine beverages:** Coffee (293.75mg) → Classic Espresso (122.07mg) → Frappuccino Blended (101.81mg) → Frappuccino Light (99.58mg) → Iced Beverages (98.53mg)
- **USA dominates global presence** with 13,608 stores — more than the next 4 countries combined
- **Classic Espresso Drinks** lead beverage category distribution at **21%**
- **Company Owned stores (11,932)** outnumber Licensed (9,375) and Joint Venture (3,976) outlets

---

## 🌍 Global Store Breakdown

| Country | Stores |
|---|---|
| 🇺🇸 United States | 13,608 |
| 🇨🇳 China | 2,734 |
| 🇨🇦 Canada | 1,468 |
| 🇯🇵 Japan | 1,237 |
| 🇰🇷 South Korea | 993 |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Microsoft Power BI Desktop** | Dashboard design, DAX measures, interactive visuals |
| **Power Query (M Language)** | Data cleaning, transformation, type formatting |
| **DAX** | KPI calculations — averages, rankings, category aggregations |
| **Microsoft Excel / CSV** | Source data files |
| **Canva** | Custom dashboard UI design & Starbucks brand styling |

---

## 📐 Dashboard Features

- **KPI Cards** — Total Beverages, Average Sugar, Average Calories, Average Caffeine
- **Protein Range Slicer** — Dynamic filter (0–20g) to explore high-protein beverages
- **Beverage Prep Filter** — Filter by size: Short, Tall, Grande, Venti, and more
- **Average Calories by Beverage Category** — Area chart showing calorie distribution
- **Starbucks Global Presence** — Bar chart of top beverages by global store presence
- **Beverage Category Distribution** — Donut chart with % share of each category
- **Average Caffeine by Category** — Horizontal bar chart ranking caffeine levels
- **Top 5 Highest Caffeine Beverages** — Visual cards with beverage images & values
- **Canva-designed UI** — Matched Starbucks' exact brand colors and typography for a product-ready look

---

## 📁 Project Structure

```
Starbucks-Analytics-Dashboard/
│
├── starbucks-analysis.pbix        # Power BI report file
├── starbucks.csv                  # Beverage nutrition dataset (242 rows)
├── directory.csv                  # Global store directory (25,600+ rows)
├── Dashboard.png                  # Dashboard preview screenshot
└── README.md                      # Project documentation
```

---

## 🧠 Skills Demonstrated

- **Data Modeling** — Structured and related multiple data sources in Power BI
- **Data Cleaning** — Handled mixed types (e.g., "Varies" in caffeine column), nulls, and formatting via Power Query
- **DAX Proficiency** — Dynamic KPIs, ranked measures, average calculations across categories
- **UI/UX Design** — Designed dashboard layout in Canva matching Starbucks brand identity before building in Power BI
- **Storytelling with Data** — Structured the dashboard to guide from summary KPIs → category analysis → global insights
- **Business Thinking** — Framed insights around real health, product, and expansion questions

---

## 🏃 How to Run

1. Clone or download this repository
2. Open `starbucks-analysis.pbix` in **Power BI Desktop** (free download from Microsoft)
3. If prompted, update the data source path to point to `starbucks.csv` and `directory.csv` on your machine
4. Click **Refresh** — all visuals will load automatically


---

## 👤 Author

**[Aditya Kumar]**
2nd Year Computer Science Student (Entering 3rd Year — August 2025)
Aspiring Data Analyst | Power BI · DAX · Excel · Canva · SQL

📧 [adisatya9508@gmail.com]
🔗 [LinkedIn Profile]
💻 [GitHub Profile]

---

## 📌 Domain

This project is relevant for roles in:
- Data Analytics
- Business Intelligence
- FMCG / Food & Beverage Analytics
- Product Analytics
- Consumer Insights

---

*Built as part of a self-initiated data analytics portfolio — focused on real-world datasets and industry-relevant insights.*