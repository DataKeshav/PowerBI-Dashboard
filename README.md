# 🛡️ Prism Insurance Portfolio Dashboard

**🔗 Live Dashboard:**  
[View on Power BI](https://app.powerbi.com/view?r=eyJrIjoiNDQwYzU3MTMtZjFhNC00NzUxLWI4ZWItMTNhYjI5NGViMDEzIiwidCI6IjAwN2Y5YTI5LTM2NjgtNDAzMS1iZTA0LTdmYmM4MTU3ZWMwYyJ9)

---

## 🎯 Problem & Business Value

Prism Insurance had a fragmented view of its customer base and product performance. Teams lacked a single, real-time tool to connect demographic usage, policy performance, and qualitative customer feedback efficiently.

This dashboard provides cohesive visibility across the entire insurance lifecycle, enabling Prism to make smarter decisions on risk mitigation, product development, and customer engagement.

---

## 🔑 Key Findings & Recommendations

### 1. Portfolio Engagement & Risk
- **Finding:** 58.11% of the insurance policies are In-Active, significantly higher than the 41.89% that are Active. This suggests a major opportunity for renewal marketing or policy restructuring.
- **Finding:** Travel and Health are the two highest premium-generating policy types, driving a combined majority of the $5.97 Million Premium Amount.
- **Recommendation:** Focus retention efforts specifically on the Travel and Health policy holders, while investigating why the In-Active rate is so high to prevent potential revenue loss.

### 2. Claims Activity & Sentiment
- **Finding:** Claims that are Rejected (4.4K) are nearly twice the amount of claims that are Pending (2.3K), signaling potential issues either in the underwriting process or customer clarity during the claims submission stage.
- **Recommendation:** Utilize the drill-through function (Policy Type) to isolate the policies with the highest rejection rates and review the specific rejection reasons.
- **Sentiment Analysis:** The Word Map (on the final page) revealed high frequency of words like "slow response" and "confusing policy", pointing to immediate service issues and documentation gaps.

---

## ⚙️ Technical Approach

This project integrated multiple data layers—from structured policy data to unstructured customer text—into a single, analytical model.

### 1. Data Preparation & Engineering
- **User Segmentation:** Established clear categories for the 5000 Male and 5000 Female users.
- **Data Cleaning:** Ensured consistency across policy type names and cleaned claim status fields (Pending, Rejected, Settled).
- **Unstructured Data Handling:** Integrated customer feedback text data (via Power Query) to enable the final sentiment analysis page.

### 2. Data Modeling & DAX
- **Key Metrics:** Developed core measures to track total Premium Amount ($5.97M), Coverage Amount ($600.33M), and Claim Amount ($16.90M).
- **Claims Logic:** Built measures to accurately calculate the count and value of claims by their status (Rejected/Settled/Pending).
- **Drill-Through Action:** Implemented a Drill-Through action from the main page to the detailed analysis page based on the PolicyType field, allowing users to investigate policy specifics efficiently.

### 3. Visualization
- **Custom Visual:** Used a Word Map visual (for customer feedback) to transform qualitative data into actionable, quantitative insights.
- **Composition:** Designed a dark-themed, professional dashboard optimized for corporate viewing, clearly isolating major KPIs (Cards) from segmentation analysis (Charts).
- **Segmentation:** Used interactive visual elements (Doughnut Chart, Bar Charts) to show the split between Active/In-Active Insurance and Premium by Policy Type.

---

## 📧 Contact & Attribution

**Developer:**  
→ Keshav Pal

**Email:**  
→ [keshav066pal@gamil.com](mailto:keshav066pal@gamil.com)

**LinkedIn:**  
→ [www.linkedin.com/in/keshav066pal](https://www.linkedin.com/in/keshav066pal)

**License:**  
This project is for portfolio purposes only. All Rights Reserved.
