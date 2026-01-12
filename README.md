# Banking & Investment Analytics Dashboard

## 📌 Overview
This project demonstrates **risk analytics in banking and financial services** using **Power BI**.  
The goal is to minimize lending risks by analyzing client profiles, deposits, loans, and engagement metrics.

## 📊 Dataset
The dataset includes multiple tables:
- **Banking Relationship** – Retail, Institutional, Private Bank, Commercial
- **Client-Banking** – Client details, deposits, loans, fees, engagement timeframe
- **Gender** – Male/Female classification
- **Investment Advisor** – List of advisors assigned to clients
- **Period** – Engagement timeline

## 🔧 Data Cleaning & Transformation
- Added **Engagement Timeframe** and **Engagement Days**
- Created **Income Band** (Low <100k, Mid <300k)
- Added **Processing Fees** column (0.05 for high fee structure)

## 📐 Calculated Functions (DAX)
- `SUM` – Aggregates deposits, loans, accounts
- `DISTINCTCOUNT` – Counts unique clients
- `SUMX` – Calculates fees based on loan × processing fee
- `SWITCH` – Categorizes values dynamically
- `DATEDIFF` – Calculates engagement days

## 📈 Key KPIs
- **Total Clients**
- **Total Loan**
- **Total Deposit**
- **Total Fees**
- **Engagement Account**
- **Credit Card Balance**

## 📊 Insights
- Loans are **highest in Mid Income Band**, lowest in High Income Band
- **European countries** show highest loan amounts, **Australian countries** lowest
- **Private banks** have the largest client base

## 🛠 Tools Used
- **Power BI** – Dashboard creation
- **Excel/CSV** – Data preprocessing
- **DAX Functions** – Calculations

## ✅ Conclusion
This dashboard helps banks:
- Assess loan repayment likelihood
- Identify profitable client segments
- Strategize client acquisition
- Track deposits, loans, and fees with clear KPIs

---
Created By Chaitanya Kukwas
