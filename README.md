# 📊 Hotel Booking Analysis Project

## 🧾 Overview
This project performs an in-depth exploratory data analysis (EDA) on a hotel booking dataset. The goal is to uncover patterns in customer behavior, cancellations, revenue, room preferences, and other insights to help hotel businesses make data-driven decisions.

---

## 📁 Dataset Description
The dataset consists of **119,390 records** with **32 columns**, covering bookings made for two hotel types:

- 🏨 **City Hotel**
- 🏖️ **Resort Hotel**

### Key Features:
- Booking behavior (`is_canceled`, `lead_time`, `arrival_date`)
- Guest demographics (`adults`, `children`, `babies`, `country`)
- Room and stay details (`reserved_room_type`, `assigned_room_type`, `adr`, `special_requests`)
- Financial and channel information (`adr`, `deposit_type`, `distribution_channel`)

---

## 🔧 Data Preprocessing
- ✅ Removed **duplicate rows**
- 🔧 Handled **missing values**:
  - Filled `agent` with 0
  - Filled `country` with `'Other'`
  - Dropped `company` due to 94% nulls
- 🧮 Created new features:
  - `total_stays_in_nights`
  - `total_guests`
  - `revenue = adr * total_stays_in_nights`

---

## 📊 Exploratory Data Analysis (EDA)

### 1. Hotel Type Booking Distribution
- 📊 **City Hotel**: 61.13% bookings
- 🏝️ **Resort Hotel**: 38.87% bookings

### 2. Booking Cancellation Rate
- ❌ 27.49% of bookings were cancelled
- ✅ 72.51% were successful stays

### 3. Distribution Channels
- 🥇 Highest: **TA/TO (Travel Agent / Tour Operator)**

### 4. Month-wise Booking Trends
- 📅 **August** had the highest number of bookings

### 5. Repeat Guests
- 🔁 Only **3.19%** of bookings were from repeated guests

### 6. Preferred Room Types
- 🛏️ Top 3: **Room Type A**, **D**, and **E**

### 7. Market Segments
- 🎯 Most bookings came from **Online TA (Travel Agencies)**

### 8. Top Guest Countries
- 🌍 Most guests came from:
  - 🇵🇹 **Portugal**
  - 🇬🇧 **United Kingdom**
  - 🇫🇷 **France**

### 9. ADR (Average Daily Rate)
- 💰 **Resort Hotels** had a slightly higher ADR compared to City Hotels

### 10. Revenue by Hotel Type
- 💵 Total revenue calculated using ADR × Total Nights
- 📈 Compared hotel-wise

### 11. Meal Plan Preferences
- 🍽️ **BB (Bed & Breakfast)** was the most preferred in both hotel types

### 12. Correlation Heatmap
- 🔍 Key findings:
  - `previous_cancellations` ↔ `previous_bookings_not_canceled`: **0.39**
  - `total_guests` ↔ `adr`: **0.39**

---

## 🎯 Business Insights & Recommendations

### ✅ Seasonal Optimization
- Focus promotions around **August**, the busiest month

### ✅ Room Strategy
- Highlight and upsell **Room Types A, D, and E**

### ✅ Customer Clarity
- Help customers compare **City vs Resort** hotel benefits

### ✅ Regional Marketing
- Offer discounts and services for **Portugal, UK, France** guests

### ✅ Meal Plan Strategy
- Offer **BB as the default** and upsell **HB/FB**

### ✅ Increase Repeat Bookings
- Launch **loyalty programs** to convert one-time guests into loyal customers

### ✅ Service Readiness
- Use special request and guest count features for better **resource planning**

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Jupyter Notebook
- Data Cleaning & Visualization
- Business Analysis

---

## 🙌 Conclusion
This project provides valuable insights into hotel customer behavior, preferences, and operational factors. It helps stakeholders make informed decisions to improve service quality, increase revenue, and optimize bookings.

---

## 👤 Author

**Piyush Soni**  
📧 Email: sakshiguptaclg@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/sakshi-gupta-3555a42ba/ )  
🔗 [GitHub](https://github.com/SakshiGupta8170)
