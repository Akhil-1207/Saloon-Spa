# Salon & Spa Business Analytics (Bookings + Customers Datasets)

##  Project Overview
This project analyzes data from a salon & spa business using **two related datasets**:  
- **Bookings** (service transactions)  
- **Customers** (customer details)  

By joining them via `Customer_ID`, we can explore trends, peak times, and customer behavior to support business development.

##  Datasets
### 1. Customers Dataset
- **File:** `customers.csv`  
- **Rows:** 100  
- **Columns:**
  - Customer_ID (Primary Key)  
  - Name  
  - Gender  
  - Age  
  - City  

### 2. Bookings Dataset
- **File:** `bookings.csv`  
- **Rows:** 100  
- **Columns:**
  - Booking_ID (Primary Key)  
  - Customer_ID (Foreign Key → Customers)  
  - Staff_ID  
  - Service (Haircut, Massage, Facial, etc.)  
  - Date  
  - Time  
  - Amount  

###  Relationship
- `Customers.Customer_ID` = `Bookings.Customer_ID`  

---

##  Business Problems Solved
1. **Popular Trends:** Most frequently booked services.  
2. **Peak Times:** Identify busiest booking times.  
3. **Revenue Tracking:** Revenue generated per service.  
4. **Customer Loyalty:** Repeat customer analysis.  
5. **Staff Performance:** Compare staff service contributions.  

---

## 🛠 Tech Stack
- **Databricks** (PySpark & Spark SQL)  
- **Python** (for data processing & visualizations)  
- **SQL** (for aggregations & joins)  
- **GitHub** (for version control & documentation)  

---

##  How to Run
1. Clone the repository:
   ```bash
   https://github.com/Akhil-1207/Saloon-Spa.git
