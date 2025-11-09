# 🏦 Bank Loan Analysis Dashboard

## 📘 Overview

The **Bank Loan Analysis Dashboard** provides a comprehensive overview of a bank’s lending activities and performance.  
It helps stakeholders monitor key loan metrics, assess portfolio health, and identify trends for data-driven decision-making.  
This project is divided into three key dashboards — **Summary**, **Overview**, and **Details** — each serving a specific analytical purpose.

---

## 📊 Dashboards

### 🧭 DASHBOARD 1: SUMMARY

**Objective:**  
Monitor and assess the bank's lending performance through KPIs that highlight loan applications, funding, repayments, and borrower financial health.

**Key KPIs:**
1. **Total Loan Applications** – Track the total and Month-to-Date (MTD) loan applications, with Month-over-Month (MoM) changes.  
2. **Total Funded Amount** – Total loans disbursed, along with MTD and MoM tracking.  
3. **Total Amount Received** – Total repayments received, MTD totals, and MoM variation.  
4. **Average Interest Rate** – Mean interest rate across all loans with MTD and MoM trends.  
5. **Average Debt-to-Income Ratio (DTI)** – Measure of borrowers’ financial health with monthly comparisons.

---

### 💰 Good Loan vs Bad Loan KPIs

**Purpose:**  
Evaluate loan quality and categorize loans as *Good* or *Bad* based on repayment status.

#### ✅ Good Loans:
Loans classified as *Fully Paid* or *Current*.

- **Good Loan Application Percentage**  
- **Good Loan Applications Count**  
- **Good Loan Funded Amount**  
- **Good Loan Total Received Amount**

#### ❌ Bad Loans:
Loans classified as *Charged Off*.

- **Bad Loan Application Percentage**  
- **Bad Loan Applications Count**  
- **Bad Loan Funded Amount**  
- **Bad Loan Total Received Amount**

---

### 🗂 Loan Status Grid View

A grid-based summary grouped by loan status to visualize key metrics such as:
- Total Loan Applications  
- Total Funded Amount  
- Total Amount Received  
- MTD Funded Amount  
- MTD Amount Received  
- Average Interest Rate  
- Average DTI  

This helps in quick comparisons between different loan categories.

---

### 📈 DASHBOARD 2: OVERVIEW

**Objective:**  
Provide visual insights into loan-related metrics and trends using interactive charts.

#### 🔹 Monthly Trends by Issue Date (Line Chart)
- **Metrics:** Total Loan Applications, Funded Amount, and Amount Received  
- **Purpose:** Identify seasonality and long-term lending trends  

#### 🗺 Regional Analysis by State (Filled Map)
- **Metrics:** Total Loan Applications, Funded Amount, Amount Received  
- **Purpose:** Highlight high-performing regions and geographic lending distribution  

#### 🕒 Loan Term Analysis (Donut Chart)
- **Metrics:** Total Applications, Funded Amount, Amount Received  
- **Purpose:** Understand loan distribution across 36-month and 60-month terms  

#### 👔 Employee Length Analysis (Bar Chart)
- **Metrics:** Total Applications, Funded Amount, Amount Received  
- **Purpose:** Assess borrower employment history’s impact on lending  

#### 🎯 Loan Purpose Breakdown (Bar Chart)
- **Metrics:** Total Applications, Funded Amount, Amount Received  
- **Purpose:** Analyze why borrowers are taking loans (e.g., debt consolidation, credit card refinance)  

#### 🏠 Home Ownership Analysis (Tree Map)
- **Metrics:** Total Applications, Funded Amount, Amount Received  
- **Purpose:** Study loan behavior by home ownership status (Own, Rent, Mortgage)  

---

### 📋 DASHBOARD 3: DETAILS

**Objective:**  
Provide a consolidated view of detailed loan-level information, enabling users to explore individual borrower profiles, loan performance, and portfolio details.

**Features:**
- Holistic snapshot of all key metrics  
- Interactive filtering and sorting  
- Easy access to borrower and loan performance data  

---

## 🛠 Technologies Used

- **Power BI** – For interactive dashboard creation  
- **Excel / CSV** – Data source and preprocessing  
- **SQL (optional)** – For data extraction and transformation  
- **Python (optional)** – For data cleaning or KPI calculation  

---

## 🧩 Features

- KPI-based loan performance tracking  
- Comparison between Good and Bad loans  
- Regional and temporal analysis  
- Visual exploration through charts and maps  
- Comprehensive data-driven dashboarding  

---

## ⚙️ Installation & Setup

1. **Download or clone** the repository:
   ```bash
   git clone https://github.com/👉CHANGE-THIS/your-repo-name.git

---

## 📸 Screenshots

Here are some visuals of the dashboard:  
(📌 Make sure you have an `images` folder in your project if you use local images.  
If using GitHub-hosted images like below, you’re all set.)

### 📊 Summary Dashboard
<img width="1211" height="697" alt="Summary Dashboard" src="https://github.com/user-attachments/assets/abb84dd9-be64-4c3a-a356-d3c06abe3302" />

### 🌍 Overview Dashboard
<img width="1193" height="710" alt="Overview Dashboard" src="https://github.com/user-attachments/assets/26ef38a9-ac2f-4ec4-8cea-f52931f37cf9" />

### 📋 Details Dashboard
<img width="1197" height="713" alt="Details Dashboard" src="https://github.com/user-attachments/assets/6fc48c30-5679-4ab0-a0d8-88de2bb3d64a" />
   
