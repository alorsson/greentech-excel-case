# GreenTech Solutions – Case Study Instructions

## I. Background  
GreenTech Solutions is analyzing its sales data to uncover trends in customer profitability, product performance, and segmented differences. As a data analyst, your task is to use Excel PivotTables to extract insights and help leadership make data-driven decisions.

---

## II. Data Description  

### Customer_Transaction Table
- Each row represents a single purchase
- Includes: Transaction ID, date, customer ID, product ID, quantity, revenue, author, discount, profit, segment, year
- `Customer_ID` and `Prod_ID` are foreign keys linking to the Customer and Product_Cost tables, respectively

### Customer Table
- Customer_ID (PK)
- Organization Name
- Customer Segment (Commercial, Residential, Government)

### Product_Cost Table
- Prod_Code (PK)
- Product name
- Supplier Cost (GreenTech’s cost per item)

---

## III. Analysis Questions  

### 1. Customer Revenue Analysis  
- Create a PivotTable by **customer segment**:
  - Sum of revenue, average revenue
  - Sum of profit, average profit  
- Filter: customers with >15 purchases  
- Question: Which segment generates the highest revenue and profit per customer on average?

---

### 2. Profitability by Product  
- For each product:
  - Sum of profit, average profit
  - Unique customer count
  - Total quantity sold  
- Question: Which product is the least profitable, and what percentage of items sold does it represent?

---

### 3. Revenue Impact of Discount Tiers  
- Pivot by discount tier:
  - Customer count
  - Average revenue
  - Total profit  
- Filter: Commercial and Residential customers  
- Question: Which tier generates the most profit per segment?

---

### 4. Combined Analysis – Customer Segment × Discount Tier  
- Analyze average profit by segment + discount tier  
- Question: Which combination yields the highest gross profit per customer?

---

### 5. Author Behavior Analysis  
- By transaction author:
  - Count, average quantity, and average profit by **customer segment**
  - Count, average quantity, and average profit by **year**

---

### 6. Advanced Insight  
- Build a custom PivotTable revealing a meaningful business pattern  
- Write a 1–2 sentence interpretation of your insight

---

## IV. Deliverable Notes  
- Each analysis should appear on its corresponding tab (Q1–Q6)  
- Answers highlighted clearly in labeled cells  
- Executive summary provided in a separate worksheet
