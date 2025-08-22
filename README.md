# Optimizing Inventory and Maximizing the Profit of a Café Business

📌 **Capstone Project – End Term Report**  
🎓 **IIT Madras Online BS Degree in Data Science & Applications**  
👤 **Author**: Sourasish Ghosh (Roll: 23f3004075)  

---

## 📖 Project Overview
This project analyzes a real-world café business (*Ektu Baithak Café*) to identify challenges in **inventory management, wastage reduction, and profit optimization**.  
The study uses **sales, SKU, inventory, and daily sales datasets** from 2024–2025 to perform statistical and predictive analyses.

---

## 🔍 Key Analyses Performed
1. **Trend & Demand Analysis**
   - Seasonal sales patterns
   - Cost fluctuations (Employee, Raw Goods, Electricity)
   
2. **Day-Wise Sales & Inventory Usage**
   - Inventory Efficiency Ratio
   - Wastage Flagging using percentile thresholds  

3. **ABC Analysis**
   - Categorization of SKUs into A, B, C groups based on profit contribution  

4. **Break-Even Analysis**
   - Identified the café’s BEP at ~3106 units/month (current sales ~2022 units/month)  

5. **Regression Analysis & What-If Scenarios**
   - R² = 0.967 → strong model fit  
   - Explored scenarios like “+15% Customers”, “-10% Raw Cost”, “+10% Sales” etc.  

---

## 📊 Results & Insights
- 📉 Café is operating below break-even point (~1084 units short per month).  
- 🗓️ Peak sales during October & festive months; lowest in April–August.  
- 🍽️ Category A SKUs (Biriyani, CST Rice) contribute ~63% of total profit → must be prioritized.  
- 🚫 Category C SKUs (Drums of Heaven, Others) drive wastage risk.  
- 💡 What-If analysis shows **raw cost reduction & sales growth have highest impact** on profitability.  

---

## ✅ Recommendations
- Daily inventory audits & FIFO implementation  
- Real-time inventory dashboard with POS integration  
- Combo offers & discounts on low-margin SKUs  
- Hiring temporary staff in festive seasons  
- Introducing **home delivery services** for remote/local customers  

---

## 🛠️ Tools & Technologies
- **Programming**: Python (Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Scikit-learn)  
- **Visualization & Calculation**: Google Sheets, Python plots  
- **Data Handling**: Inventory & Sales datasets (2024–2025)  

---

## 📂 Repository Structure
```plaintext
├── datasets/ # Raw and cleaned data files
├── notebooks/ # Jupyter/Python scripts with analysis
├── results/ # Plots, charts, and analysis outputs
├── report/ # Full End-Term Report (PDF)
└── README.md # Project documentation
