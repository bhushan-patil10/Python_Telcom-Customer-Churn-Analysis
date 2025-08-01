# 📞 Telcom Customer Churn Analysis 📉

## 📖 Story and Background

This project analyzes customer behavior and churn patterns from a telecom company using a real-world dataset of **7,043 customers** and **21 attributes**. The goal is to help the business identify churn drivers, customer segmentation, and opportunities to **improve retention and customer value**.

📌 Using Python’s data analytics and visualization libraries, we extract actionable insights to enable smarter business decisions, personalized offers, and strategic interventions.

---

## 🛠️ Tools Used

- ✅ Python 3.x  
- ✅ Jupyter Notebook  
- 📦 pandas  
- 📦 numpy  
- 📊 matplotlib  
- 🔘 matplotlib-venn  

---

## ❓ Key Questions

- 👤 What is the gender, age, and service segmentation of our customer base?  
- 💳 What are the predominant contract types and payment methods?  
- 🔗 What variables are strongly correlated, and how do they relate to churn?  
- 💰 Which customers are most valuable based on charges?  
- 🚪 What is our churn rate, and which segments are most at risk?  
- 🎯 How can monthly charge categories be used to offer personalized plans?

---

## 🧠 Approach / Methodology

1. **📥 Data Loading and Cleaning:**  
   - Loaded CSV into a pandas DataFrame.  
   - Cleaned null/invalid values in `TotalCharges`.  
   - Renamed columns for better readability.

2. **🔎 Exploratory Data Analysis (EDA):**  
   - Analyzed demographic & service features.  
   - Visualized customer segments: gender, seniority, partnership status, dependents, contract types, etc.

3. **📈 Correlation & Insight Extraction:**  
   - Built correlation matrix for numeric features.  
   - Focused on churn relationships with payment, internet, and contract types.

4. **🧩 Segmentation and Visualization:**  
   - Categorized users by spending patterns.  
   - Visualized top customers, churn trends, and service overlaps.  
   - Used Venn diagrams, pie charts, bar charts, and heatmaps.

5. **📢 Business Recommendations:**  
   - Provided actionable suggestions for offers, retention, and targeting based on detailed analysis.

---

## 📸 Visuals Created

- 🥧 Pie Charts: Gender, Senior Citizen, Partner, Dependent, Contracts, Internet Services, Payment Methods, Churn Rate  
- 📊 Bar Charts: Streaming TV usage, Monthly Charge Segments, Churn per Charge Category  
- 🔥 Heatmaps: Feature correlations  
- 🔘 Venn Diagram: Overlap of Streaming TV & Streaming Movies users  
- 📉 Stacked Bar: Churn by Internet Service and Charge Category  

---

## ✅ Conclusion

### 👥 **Customer Profile**
- Gender: Almost equal split  
- Senior Citizens: **16%**  
- Partners: **51.7%** have partners  
- Dependents: **30%**

### 📞 **Service & Contract**
- Multiple Lines:  
  - Single line: **45.9%**  
  - Multiple lines: **29.9%**  
  - No phone service: **24.2%**  
- Internet Services:  
  - DSL: **34.3%**  
  - Fiber Optic: **44.2%**  
  - None: **21.5%**  
- Contract Types:  
  - Month-to-month: **55%** (🔺higher churn)  
  - One/Two year: Remaining users  
- Payment Methods:  
  - Electronic check: **33.6%** (most common)

### 🚪 **Churn Insights**
- Total Churn Rate: **26.5%**  
- Highest churn among **Fiber Optic** users (~42%)  
- **Month-to-month** customers show most churn  

### 💵 **Spending Segments**
- Average Monthly Charge: **$64.76**  
- Monthly Charge Segments:
  - Low (<$35): **24.6%**  
  - Medium ($35–70): **23.6%**  
  - High ($70–100): **38.1%**  
  - Extreme (>$100): **13.7%**

📌 *Extreme users subscribe to 6.35/8 services, while Low users average just 1.17 services*

### 📊 **Correlation Coefficients**
- Tenure ↔ TotalCharges: **+0.83** ✅  
- MonthlyCharges ↔ TotalCharges: **+0.65**  
- SeniorCitizen ↔ MonthlyCharges: **+0.22** (seniors spend slightly more)

### 🏆 **Top Customers**
- Highest Monthly Charge: **7569-NMZYQ**  
- Highest Total Charges: **2889-FPWRM**

---

## 💡 Recommendations & Actionable Insights

| Segment | Action |
|--------|--------|
| 🟢 **Low Spend** | Offer bundle upgrades at small discounts & free trials |
| 🟡 **Medium Spend** | Promote limited-time service combos to increase adoption |
| 🔴 **High Spend** | Incentivize full-service plans & loyalty bonuses |
| 🔵 **Extreme Spend** | Offer discounted yearly contracts to lock long-term value |

🔁 **Churn Mitigation Focus:**
- 🎯 Target **month-to-month** and **fiber optic** customers  
- 🧩 Personalize offers based on service history and spending  

---

📌 *Keep updating the analysis with fresh data to validate and refine strategies.*

📎 For full analysis, charts, and EDA — refer to the 📓 Jupyter Notebook in this repo.
