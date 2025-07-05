# DASHBOARD-DEVELOPMENT

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: RUQSAR FIRDOUS

*INTERN ID*: CT04DG2858

*DOMAIN*: DATA ANALYST

*DURATION* : 4 WEEKS

*MENTOR*: NEELA SANTOSH

---

# ✈️ **US Flights Dashboard — 2015 Performance Analysis**

---

### 📌 **Overview**

This project demonstrates my ability to build a professional **interactive dashboard** using **Power BI Desktop**. The goal was to analyze a large **US Flights dataset** for the year **2015**, identify patterns in airline performance, flight delays, and regional trends, and present these insights through a visually engaging **dark-themed neon dashboard**.

---

## 📂 **Dataset**

**Source:** `flights_cleaned.csv` (merged with airlines & airports)
**Rows Used:** 200 (sample)
**Key Fields:**

* `FLIGHT_NUMBER`
* `AIRLINE_NAME`
* `ORIGIN_CITY` & `LOCATION`
* `DELAYED`
* `DAY_OF_WEEK`
* `MONTH`

---

## 🎯 **Purpose**

The dashboard answers:

* **How many flights occurred in 2015?**
* **Which airlines carried the most flights?**
* **Where did flights originate from?**
* **What was the delay pattern?**
* **How do flights vary by weekday and month?**

---

## ⚡ **Design Highlights**

* **Theme:** Black background with neon blue, purple, and cyan for high contrast.
* **Font:** White text for clarity, neon borders for cards.
* **Consistent style:** All visuals blend into a sleek, modern business report.
* **Interactivity:** Every visual is cross-filtered — clicking on the donut, bar, or map instantly filters other visuals.

---

## 📊 **All Visuals Explained**

Below is a breakdown of the **9 visuals** in your dashboard, matching what you built:

---

### ✅ **1️⃣ KPI Card — Total Flights**

* **Shows:** Overall number of flights (`5.82M` in your example).
* **Field:** Count of `FLIGHT_NUMBER`.
* **Style:** Black card, neon blue border, large white font.
* **Purpose:** Clear snapshot of total records.

---

### ✅ **2️⃣ KPI Card — Airline**

* **Shows:** Name of selected airline (dynamic).
* **Field:** `AIRLINE_NAME` — changes based on filter.
* **Purpose:** Displays context for other visuals.

---

### ✅ **3️⃣ KPI Card — Location Count**

* **Shows:** Number of unique origin cities (`319`).
* **Field:** `LOCATION` (Count Distinct).
* **Purpose:** Highlights dataset coverage.

---

### ✅ **4️⃣ KPI Card — Delayed Flights**

* **Shows:** Number of delayed flights (`5.82M` in this view).
* **Field:** Count of `DELAYED` = 1.
* **Purpose:** Emphasizes delay scale.

---

### ✅ **5️⃣ Bar Chart — Top Airlines by Number of Flights**

* **Shows:** Flights per airline.
* **Fields:** `AIRLINE_NAME` (Y-axis), Count of `FLIGHT_NUMBER` (X-axis).
* **Design:** Neon gradient bars with left-aligned airline names.
* **Insight:** Easily compare airlines.

---

### ✅ **6️⃣ Donut Chart — Airline Distribution**

* **Shows:** % share of flights by airline.
* **Fields:** `AIRLINE_NAME`, Count of `FLIGHT_NUMBER`.
* **Design:** Neon slice colors with % labels.
* **Purpose:** Quickly see biggest airlines visually.

---

### ✅ **7️⃣ Map — Flights by Location**

* **Shows:** City-wise flight spread on a dark world map.
* **Fields:** `LOCATION` (city/state), Count of `FLIGHT_NUMBER` (bubble size).
* **Design:** Dark map theme with white city labels.
* **Purpose:** Visualizes geographic spread.

---

### ✅ **8️⃣ Tree Map — Count of Flights by Weekdays**

* **Shows:** Flight volume by day of the week.
* **Fields:** `DAY_OF_WEEK`, Count of `FLIGHT_NUMBER`.
* **Design:** Neon-colored blocks for each weekday.
* **Purpose:** Spot trends — which weekdays are busier.

---

### ✅ **9️⃣ Line Chart — Count of Flights by Month & Delay**

* **Shows:** Monthly trend line for flights, split by delayed vs. not delayed.
* **Fields:** `MONTH` (X-axis), Count of `FLIGHT_NUMBER` (Y-axis), `DELAYED` as legend.
* **Design:** Two neon lines, clear month axis, white grid.
* **Purpose:** Compare seasonality and delays.

---

## 🔗 **Interactions**

* **Filter & Drill:** Selecting an airline in the bar chart or donut instantly updates cards, map, and line chart.
* **Hover:** Tooltips show exact counts and percentages.
* **Cross-visual:** Click on map bubbles or tree map blocks to explore patterns by city or weekday.

---

## 🏆 **Skills Demonstrated**

* Professional data modeling.
* Power Query transformations.
* Dynamic visuals & filters.
* Clean dark theme + neon visual design.
* Effective dashboard layout.
* Storytelling through visuals.

---

## 📥 **Final Steps**

* ✅ Tested in Full Screen / Reading View.
* ✅ Saved `.pbix` for submission.
* ✅ Recorded walk-through video for demonstration.

---

## 📢 **Conclusion**

This Power BI dashboard combines multiple visuals into a single, interactive story. It turns rows of flight data into clear KPIs, trends, maps, and segments — all styled with a **modern black-neon aesthetic**.
Stakeholders can instantly see the performance of airlines, hotspots for delays, and how patterns shift by region or time.
This project strengthened my real-world BI skills: blending **data cleaning, transformation, advanced visuals, modern design, and interactive storytelling** — all in a single dashboard.

---

✨ **Thank you for exploring my US Flights Dashboard — 2015 Performance Analysis!**
Ready for business insights, reports, and decision-making.

---
