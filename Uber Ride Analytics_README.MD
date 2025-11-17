# 🚗 Uber Ride Analytics Dataset 2024  
A comprehensive ride-sharing analytics dataset containing **148,770 Uber bookings** from the year **2024**, covering booking behavior, cancellations, vehicle performance, revenue metrics, and customer satisfaction.

This dataset is ideal for projects involving:  
- Data Analytics  
- Machine Learning  
- Customer Segmentation  
- Predictive Modeling (ETA, cancellations, ride value, churn)  
- BI Dashboards (Power BI / Tableau)  

---

## 📦 Dataset Overview

The dataset captures end-to-end booking details, customer ratings, trip performance, cancellations, and payment-related metrics.

### 🔢 **Total Records**  
- **148,770 bookings**  
- **65.96% completed rides (93K+)**  
- **25% cancelled (37.4K)**  
- **19.15% customer cancellations (27K)**  
- **7.45% driver cancellations (10.5K)**

---

## 📋 **Data Schema**

| Column Name | Description |
|------------|-------------|
| `Date` | Date of booking |
| `Time` | Time of booking |
| `Booking ID` | Unique ride identifier |
| `Booking Status` | Completed / Cancelled / Incomplete |
| `Customer ID` | Unique customer identifier |
| `Vehicle Type` | Go Mini, Auto, Sedan, UberXL, etc. |
| `Pickup Location` | Start location |
| `Drop Location` | End location |
| `Avg VTAT` | Avg driver arrival time to pickup |
| `Avg CTAT` | Avg customer trip time |
| `Cancelled Rides by Customer` | Flag |
| `Reason for cancelling by Customer` | Customer cancellation reasons |
| `Cancelled Rides by Driver` | Flag |
| `Driver Cancellation Reason` | Driver cancellation reasons |
| `Incomplete Rides` | Flag |
| `Incomplete Rides Reason` | Reason for incomplete trips |
| `Booking Value` | Total fare amount |
| `Ride Distance` | Distance travelled |
| `Driver Ratings` | Rating given by the driver (1–5) |
| `Customer Rating` | Rating given by the customer (1–5) |
| `Payment Method` | UPI, Cash, Card, Wallet, etc. |

---

## 🚗 **Vehicle Fleet Performance (Summary)**

| Vehicle Type | Success Rate | Avg Distance | Total Distance |
|--------------|--------------|--------------|----------------|
| Auto | 91.1% | 25.99 km | 602K km |
| eBike/Bike | 91.1% | 26.11 km | 537K km |
| Go Mini | 91.0% | 25.99 km | 482K km |
| Go Sedan | 91.1% | 25.98 km | 433K km |
| Premier Sedan | 91.2% | 25.95 km | 292K km |
| UberXL | 92.2% | 25.72 km | 72K km |

---

## 💰 **Revenue Breakdown (Payment Methods)**  
- **UPI: ~40% of total revenue**  
- **Cash: ~25%**  
- **Credit Card: ~15%**  
- **Uber Wallet: ~12%**  
- **Debit Card: ~8%**

---

## 🚫 **Cancellation Patterns**

### **Customer Cancellation Reasons**
- Wrong Address — **22.5%**
- Driver Issues — **22.4%**
- Driver Not Moving — **22.2%**
- Change of Plans — **21.9%**
- App Issues — **11.0%**

### **Driver Cancellation Reasons**
- Capacity Issues — **25.0%**
- Customer Related Issues — **25.3%**
- Personal/Car Problems — **24.9%**
- Customer Behavior — **24.8%**

---

## ⭐ **Rating Summary**
- **Customer Ratings:** 4.40 – 4.41  
- **Driver Ratings:** 4.23 – 4.24  
- **Highest customer-rated:** Go Sedan  
- **Most satisfied drivers:** UberXL  

---

## 🧹 Data Quality
- **Minimal missing values**
- **Fully standardized categories**
- **Covers full calendar year (2024)**
- **Rich geographical + temporal variation**

---

## 📁 Use Cases
- Ride completion prediction  
- Surge pricing insights  
- Driver-customer rating analysis  
- Location-based cancellation hotspots  
- Demand forecasting  
- Payment behavior analysis  

---

## 📜 License
This dataset is provided for **educational and research purposes**.

