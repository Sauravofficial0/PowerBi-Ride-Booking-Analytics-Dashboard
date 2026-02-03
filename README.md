# 🚖 Power BI Ride Booking Analytics Dashboard

This repository contains a complete **Power BI analytics project** built to analyze ride-booking operations, revenue, cancellations, and ratings.

The dashboard is designed for **business stakeholders and operations teams** to quickly understand ride trends, customer behavior, vehicle performance, and service quality.

---

## 📌 Project Objective

To build an interactive Power BI dashboard that helps:

- Track ride volume and booking performance over time  
- Identify top-performing vehicle types and customers  
- Analyze revenue and payment methods  
- Understand cancellation and incomplete ride reasons  
- Evaluate driver and customer ratings  

---

## 🗂 Dataset Description

The dataset contains the following columns:

| No. | Column Name |
|----|-----------|
| 1 | Date |
| 2 | Time |
| 3 | Booking_ID |
| 4 | Booking_Status |
| 5 | Customer_ID |
| 6 | Vehicle_Type |
| 7 | Pickup_Location |
| 8 | Drop_Location |
| 9 | V_TAT |
| 10 | C_TAT |
| 11 | cancelled_Rides_by_Customer |
| 12 | cancelled_Rides_by_Driver |
| 13 | Incomplete_Rides |
| 14 | Incomplete_Rides_Reason |
| 15 | Booking_Value |
| 16 | Payment_Method |
| 17 | Ride_Distance |
| 18 | Driver_Ratings |
| 19 | Customer_Rating |

---

## 📊 Business Questions Covered

1. Ride Volume Over Time  
2. Booking Status Breakdown  
3. Top 5 Vehicle Types by Ride Distance  
4. Average Customer Ratings by Vehicle Type  
5. Cancelled Rides Reasons  
6. Revenue by Payment Method  
7. Top 5 Customers by Total Booking Value  
8. Ride Distance Distribution Per Day  
9. Driver Ratings Distribution  
10. Customer vs Driver Ratings  

---

## 🧭 Dashboard Structure (Segregation of Views)

The dashboard is organized into the following analytical views:

### 1️⃣ Overall View
- Ride Volume Over Time  
- Booking Status Breakdown  

### 2️⃣ Vehicle Type View
- Top 5 Vehicle Types by Ride Distance  

### 3️⃣ Revenue View
- Revenue by Payment Method  
- Top 5 Customers by Total Booking Value  
- Ride Distance Distribution Per Day  

### 4️⃣ Cancellation View
- Cancelled Rides Reasons (Customer)  
- Cancelled Rides Reasons (Driver)  

### 5️⃣ Ratings View
- Driver Ratings  
- Customer Ratings  

---

## 📈 Visuals & Insights Implemented

### 1. Ride Volume Over Time
A **time-series chart** showing the number of rides per day / week to track growth and demand trends.

---

### 2. Booking Status Breakdown
A **pie / doughnut chart** displaying the proportion of:
- Successful rides  
- Cancelled by customer  
- Cancelled by driver  
- Incomplete rides  

---

### 3. Top 5 Vehicle Types by Ride Distance
A **bar chart** ranking vehicle types based on total ride distance.

---

### 4. Average Customer Ratings by Vehicle Type
A **column chart** showing the average customer rating for each vehicle type.

---

### 5. Cancelled Rides Reasons
A **bar chart** highlighting common reasons for:
- Customer cancellations  
- Driver cancellations  

---

### 6. Revenue by Payment Method
A **stacked bar chart** displaying total booking value by:
- Cash  
- UPI  
- Credit Card  
- Other payment methods  

---

### 7. Top 5 Customers by Total Booking Value
A **leaderboard visual** listing the top 5 customers based on total spending.

---

### 8. Ride Distance Distribution Per Day
A **histogram or scatter plot** showing how ride distances vary across different dates.

---

### 9. Driver Ratings Distribution
A **box plot** visualizing the spread and consistency of driver ratings across vehicle types.

---

### 10. Customer vs Driver Ratings
A **scatter plot** comparing customer ratings and driver ratings for completed rides to analyze correlation.

---

## 🛠 Tools Used

- Microsoft Power BI
- DAX (for calculated measures and KPIs)
- Power Query (for data cleaning and transformation)

---

## 🧪 Data Preparation Highlights

- Removed invalid and incomplete records
- Handled missing ratings and booking values
- Standardized booking status values
- Created calculated measures for:
  - Total Rides
  - Total Revenue
  - Average Ratings
  - Cancellation counts

---

## 🎯 Key KPIs Included

- Total Rides
- Completed Rides
- Total Revenue
- Average Ride Distance
- Average Driver Rating
- Average Customer Rating
- Cancellation Rate

---

## 📁 Repository Structure


---

## 🚀 How to Use

1. Download the `.pbix` file from the **PowerBI_Report** folder.
2. Open it using **Power BI Desktop**.
3. Refresh the data (if dataset path is updated).
4. Explore each dashboard page:
   - Overall
   - Vehicle Type
   - Revenue
   - Cancellation
   - Ratings

---

## 💡 Business Value

This dashboard helps management to:

- Identify high-performing vehicle categories
- Detect revenue-driving payment methods
- Reduce cancellations by understanding their root causes
- Monitor service quality using rating patterns
- Track customer value and loyalty

---
