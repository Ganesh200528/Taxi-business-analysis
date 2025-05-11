# 🚖 Taxi Trip Analytics Dashboard

This Power BI project analysis taxi trip data by combining customer demographics, trip details, and transaction/payment information. It uses advanced DAX measures, interactive parameters, and dynamic visuals to provide actionable insights into customer behavior, revenue performance, and operational efficiency.

---

## 📊 Project Overview

The dashboard includes:

* Customer demographics (age, gender, income)
* Trip-level insights (city, company, cost, distance, price, date)
* Transaction data with payment methods
* Parameter-based dynamic pricing analysis
* Key KPIs and What-If analysis for strategic decision-making

---

## 📁 Dataset Structure

### 1. **Customers Table**

| Column        | Description                |
| ------------- | -------------------------- |
| `customer_id` | Unique customer identifier |
| `age`         | Age of the customer        |
| `gender`      | Gender of the customer     |
| `income`      | Customer's income          |

### 2. **TaxiTrips Table**

| Column            | Description                      |
| ----------------- | -------------------------------- |
| `transactionid`   | Unique transaction identifier    |
| `city`            | City where the trip took place   |
| `company`         | Taxi company                     |
| `cost of trip`    | Operational cost for the trip    |
| `price`           | Price charged to the customer    |
| `distance travel` | Distance covered during the trip |
| `date of travel`  | Date when the trip occurred      |

### 3. **Transactions Table**

| Column           | Description             |
| ---------------- | ----------------------- |
| `transaction_id`  | Unique transaction ID   |
| `customer_id`     | Linked customer ID      |
| `payment method` | Method used for payment |

---

## 🧮 Key DAX Measures

* **Total Revenue by Customer**
* **Number of Trips**
* **Average Trip Cost**
* **Revenue by Payment Method**
* **Revenue by City, Age Group, and Gender**
* **Revenue per Distance**
* **Adjusted Revenue using Price Parameter**

  ## thank you for Vist my Github Page
