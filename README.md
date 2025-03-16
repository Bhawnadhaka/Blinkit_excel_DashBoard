# 🛒 Blinkit Grocery Dataset Dashboard

## 🎉 Project Overview
Explore comprehensive grocery sales insights with this **interactive and dynamic Excel dashboard**, built using Blinkit’s real-world dataset. This project visualizes key sales metrics, customer behavior patterns, and outlet performance — all packed into a **clean, user-friendly interface**.

---

## 🔍 Key Dashboard Features

✨ **Sales Overview**
- 💸 Total Sales, Average Sales, and Total Item Count
- 📊 Revenue breakdown by Tier, Outlet Type, and Item Category

📌 **Product Insights**
- 🥇 Top-selling categories and underperforming products
- 🔬 Analysis of Fat Content influence on sales

📈 **Outlet Performance**
- 📍 Location-based performance (Tier 1, 2, 3)
- 🏪 Supermarket vs Grocery store comparison

👥 **Customer Behavior**
- ⭐ Average Ratings per outlet
- 🔥 Demand trends across years

---

## 📸 Dashboard Preview
Check out the **final dashboard** — a fusion of aesthetics and analytics:


![Blinkit Dashboard Updated](https://github.com/Bhawnadhaka/Blinkit_excel_DashBoard/blob/main/Screenshot%202025-03-16%20010436.png)

---

## 🗂 File Structure

### BlinkIT-Grocery-Data.xlsx

#### 📋 Sheets Breakdown:

1️⃣ **Sheet1:** Aggregated metrics, pivot tables, and summarized data by fat content, tiers, and outlet types.

2️⃣ **Dashboard:** Reserved for future interactive visualizations.

3️⃣ **BlinkIT-Grocery-Data:** Raw transactional data (800+ rows, 12 columns).

---

## 🧠 Data Breakdown

### **Sheet1 - Aggregated Metrics**

#### **Key Metrics:**
- **Total Sales:** ₹1,201,681.49
- **Average Sales per Item:** ₹140.99
- **Total Items Sold:** 8,523
- **Average Customer Rating:** 3.97/5

#### **Breakdown by Fat Content:**
- **Low Fat:** ₹776,319.69 (64.6% of total sales)
- **Regular:** ₹425,361.80 (35.4% of total sales)

#### **Breakdown by Tier:**
- **Tier 1:** ₹336,397.81
- **Tier 2:** ₹393,150.65
- **Tier 3:** ₹472,133.03

#### **Breakdown by Outlet Type:**
- **Supermarket Type1:** ₹787,549.89 (dominant contributor)
- **Grocery Store:** ₹151,939.15

---

### **BlinkIT-Grocery-Data (Raw Data)**

- **Item Fat Content:** Low Fat, Regular
- **Serial No:** Auto-generated identifier
- **Item Identifier:** Unique product codes (e.g., FDX32, NCB42)
- **Item Type:** 14 categories (e.g., Fruits and Vegetables, Frozen Foods, Household)
- **Outlet Establishment Year:** Ranges from 2011 to 2022
- **Outlet Identifier:** Unique store codes (e.g., OUT049, OUT018)
- **Outlet Location Type:** Tier 1, Tier 2, Tier 3
- **Outlet Size:** High, Medium, Small
- **Outlet Type:** Supermarket Type1/2/3, Grocery Store
- **Item Visibility:** Numeric metric (e.g., 0.1000135)
- **Item Weight:** Weight in kg (some missing values)
- **Sales:** Transaction amount in ₹
- **Rating:** Customer rating (scale 1–5; most entries rated 5)

---

## 🔥 Key Insights

### 🏷️ Top Categories by Sales
- **Fruits and Vegetables:** ₹178,124.08
- **Snack Foods:** ₹175,433.92
- **Household:** ₹135,976.53

### 🏪 Outlet Performance
- **Highest Sales Year:** 2018 (₹204,522.26)
- **Lowest Sales Year:** 2011 (₹78,131.57)

### 🎯 Customer Preferences
- **Low-fat products dominate sales** (64.6%)
- **Tier 3 outlets generate the most revenue** (₹472,133.03)

---

## 🔧 Usage Notes

- **Pivot Table Formulas:** Ensure cell `$C$4` remains intact to prevent GETPIVOTDATA errors.
- **Missing Data:** Some `Item Weight` values are blank — handle accordingly.
- **Dashboard Sheet:** Ready for future enhancements (charts, graphs, and automation).

---

## 🔨 Dependencies

- **Software:** Microsoft Excel or compatible alternatives (Google Sheets, LibreOffice)
- **Advanced Analysis:** Export data to tools like Python (Pandas) for deeper insights.

---

## 🚀 Final Takeaway

This dashboard transforms raw Blinkit grocery data into a **visually captivating**, **data-driven narrative**. It helps **retailers, analysts, and decision-makers** identify **high-performing products**, **track outlet efficiency**, and **decode customer behavior** — all within a click.



