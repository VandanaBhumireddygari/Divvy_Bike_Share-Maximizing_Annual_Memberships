

---


# 🚴‍♀️ **Divvy Bike Share – Rider Behavior & Membership Growth Dashboard**

### *Understanding how casual riders behave & identifying opportunities to convert them into annual members*

🔗 **Live Dashboard:**
[https://public.tableau.com/app/profile/vandana.bhumireddygari/viz/Divvy_project_17646233529780/BikeTypeLevelAnalysis](https://public.tableau.com/app/profile/vandana.bhumireddygari/viz/Divvy_project_17646233529780/BikeTypeLevelAnalysis)

🔗 **Project Repository:**
[https://github.com/VandanaBhumireddygari/Divvy_Bike_Share-Maximizing_Annual_Memberships](https://github.com/VandanaBhumireddygari/Divvy_Bike_Share-Maximizing_Annual_Memberships)

---

## 📌 **Overview**

Divvy’s business model depends on two customer segments:

* **Casual Riders** (pay-per-ride, seasonal, inconsistent)
* **Annual Members** (predictable, high-lifetime-value)

This dashboard analyzes ~4.5M trips to answer one high-impact question:

> **“Which casual riders are most likely to convert into long-term annual members?”**

To answer this, the dashboard explores **bike type preference, time-of-day usage, seasonal patterns, ride behavior, and membership trends**.

---

# 🖼️ **Dashboard Insights (with visuals + explanation)**

---

## 🟠 **1. Bike Type Share**

![Bike Type Share]

### **What this tells us**

* **Classic Bikes:** 84.88% of all rides
* **Electric Bikes:** 15.12%

**Interpretation:**
Even though electric bikes have lower volume, they attract riders who take longer trips and often use bikes for commuting → **ideal candidates for membership upsell**.

---

## 🟦 **2. Avg Trip Distance by Bike Type & Membership**

![Distance Comparison](ADD_IMAGE_LINK_HERE)

### **Key Values**

| Rider Type | Classic Bike | Electric Bike |
| ---------- | ------------ | ------------- |
| **Casual** | 2.12 miles   | 2.49 miles    |
| **Member** | 2.23 miles   | 2.55 miles    |

### **What this means**

* Casual riders take longer trips even on classic bikes.
* Electric bike riders (both casual + member) travel farther → **higher willingness to pay**.

➡️ **High-value casual riders = long-distance leisure riders.**

---

## 🟧 **3. Weekly Behavior – Which days do riders prefer?**

![Day of Week](ADD_IMAGE_LINK_HERE)

### **Key Values**

* Casual riders spike on **Saturday (744K rides)** & **Sunday (627K rides)**
* Member rides remain steady across the week (~480–560K per weekday)

### **Business Interpretation**

* Weekends = *leisure riding*, heavily casual → **best conversion window**
* Members = *routine commuters*, consistent usage → **stable revenue**

---

## 🟩 **4. Temporal Analysis (Month × Membership Type)**

![Monthly Trends](ADD_IMAGE_LINK_HERE)

### **Highlights**

* **Peak Usage:** July & August (300k–350k rides/month)
* Members maintain consistent usage across all months
* Casual riders disappear in winter and return sharply in spring

### **Why this matters**

* Spring (Mar–May) = **best time for membership promotions**
* Summer = **highest demand**, great for upselling multi-month plans
* Winter = **predictable low**, helps plan bike rebalancing & maintenance

---

# 🔍 **Summary of Insights (with business meaning)**

### **1️⃣ Casual riders take longer trips**

* Avg trip duration difference: **Casual = 35–40 mins**, **Members = 20–25 mins**
  ➡️ They’re already high-value → convert them.

---

### **2️⃣ Weekend traffic is dominated by casual riders**

* 43% of casual rides happen Sat/Sun
  ➡️ Push weekend-only membership discounts.

---

### **3️⃣ Seasonal behavior shows when to advertise**

* Spring = growth period
* Summer = highest traffic
  ➡️ Offer early-bird membership offers in spring.

---

### **4️⃣ Electric bike users are perfect membership candidates**

* Higher distances
* Faster commuting patterns
  ➡️ Target students & young professionals.

---

### **5️⃣ Month-wise and hour-wise patterns show clear spikes**

* Peak hours: **4 PM – 6 PM**
  ➡️ In-app “join membership to skip peak price” nudges work best here.

---

# 💼 **Business Value Delivered**



---
By implementing these recommendations, Divvy can:

✅ Increase annual membership conversion rates
✅ Improve profitability per rider
✅ Better balance bike availability during peak hours
✅ Optimize marketing spend by targeting high-potential users
✅ Enhance customer satisfaction with tailored offerings
---

# 🛠️ **Tech Used**

* **Tableau Public** – Dashboard & analytics
* **Python / Spark (optional)** – Data cleaning & transformation
* **GitHub** – Documentation & version control

---

# 📂 **Repository Structure**

```
📁 Divvy_Bike_Share-Maximizing_Annual_Memberships
 ├── tableau/             # .twbx workbook
 ├── report/         # Dashboard images
 ├── data/                # Clean dataset used
 └── README.md            # This file
```

---

A clean, visual, business-focused dashboard that helps Divvy convert casual riders into loyal annual members by understanding their real riding behavior.


