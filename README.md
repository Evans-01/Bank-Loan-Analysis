# 📊 Bank Loan Report Dashboard

This repository presents a detailed summary and overview of a bank loan dataset visualized using interactive dashboards. The dashboards provide insights into loan applications, funded and received amounts, interest and DTI rates, and various breakdowns by loan status, term, employee length, and more.

---

## 🧾 Summary Dashboard

![Summary Dashboard](https://github.com/Evans-01/Bank-Loan-Analysis/blob/fdff3e37c132310f1923def2053ed88c2abd239c/Bank%20Loan%20Report%20Summary.png) <!-- Replace with actual image path if needed -->

### 🔹 Key Metrics:
- **Total Loan Applications:** 38.6K  
  - Month-To-Date (MTD): 4.3K  
  - Month-over-Month (MoM) Growth: 6.9%
  
- **Total Funded Amount:** $435.8M  
  - MTD: $54.0M  
  - MoM Growth: 13.0%

- **Total Amount Received:** $473.1M  
  - MTD: $58.1M  
  - MoM Growth: 15.8%

- **Average Interest Rate:** 12.0%  
  - MTD: 12.4%  
  - MoM Change: 3.5%

- **Average DTI Rate:** 13.3%  
  - MTD: 13.7%  
  - MoM Change: 2.7%

### ✅ Good vs Bad Loans:
- **Good Loans Issued:** 86.2%  
  - Applications: 33.2K  
  - Funded Amount: $370.2M  
  - Amount Received: $435.8M

- **Bad Loans Issued:** 13.8%  
  - Applications: 5.3K  
  - Funded Amount: $65.5M  
  - Amount Received: $37.3M

### 📌 Loan Status Breakdown:
| Status      | Applications | Funded Amount | Amount Received | Avg Interest | Avg DTI |
|-------------|--------------|----------------|------------------|---------------|----------|
| Fully Paid  | 32,145       | $351.4M        | $411.6M          | 11.64%        | 13.2%    |
| Charged Off | 5,333        | $65.5M         | $37.3M           | 13.88%        | 14.0%    |
| Current     | 1,098        | $18.9M         | $24.2M           | 15.10%        | 14.7%    |
| **Total**   | **38,576**   | **$435.8M**    | **$473.1M**      | **12.05%**    | **13.3%** |

---

## 📈 Overview Dashboard

![Overview Dashboard](https://github.com/Evans-01/Bank-Loan-Analysis/blob/49bab5d662a5625882a14058ed0011b22aae90ea/Bank%20Loan%20Report%20Overview.png) <!-- Replace with actual image path if needed -->

### 🔹 Trends and Distributions

#### 📅 Loan Applications by Month
- Monthly growth is consistent, rising from 2.3K in January to 4.3K in December.

#### 🗺️ Loan Applications by State
- Visualized by heatmap; higher loan applications in states like California, Texas, New York.

#### ⏳ Loan Term Distribution
- 36 months: 28.2K (73.2%)
- 60 months: 10.3K (26.8%)

#### 🧑‍💼 Applications by Employee Length
- 10+ years: 8.9K
- 2–5 years: ~4K each
- <1 year: 4.6K
- 1 year: 3.2K

#### 🎯 Applications by Purpose
- Top purposes:
  - **Debt Consolidation:** 18.2K
  - **Credit Card:** 5.0K
  - **Other:** 3.8K
  - **Home Improvement:** 2.9K

#### 🏠 Home Ownership Distribution
- **Renters:** 18K
- **Mortgage Holders:** 17K
- Others are minimal

---

## 🧰 Filters and Controls
- Grade (A–G)
- State
- Loan Purpose
- Loan Type (Good / Bad)
- Measure Selection:  
  - Total Amount Received  
  - Total Funded Amount  
  - Total Loan Application  

---
