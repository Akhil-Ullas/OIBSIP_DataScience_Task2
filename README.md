# 📊 Unemployment Analysis in India (Before & After COVID-19)

## 📌 Overview
This project analyzes **unemployment trends in India** using CMIE unemployment data.  
The focus is on understanding how **COVID-19 lockdowns (March 2020 onwards)** affected unemployment rates at the **national** and **state** levels.  

Interactive visualizations are created using **Plotly** in Google Colab, making it easier to explore spatial and temporal patterns.

---

## 🎯 Objectives
- Analyze unemployment trends across India using CMIE data.  
- Study unemployment patterns **before and after COVID-19 lockdown (March 2020)**.  
- Identify the **top 10 states** with the highest average unemployment.  
- Visualize unemployment changes at **national and state levels** using Plotly.  
- Compare **state-wise unemployment before vs after lockdown** (Jan–Mar vs Apr–Jun 2020).  

---

## 🗂 Dataset
- **Source:** CMIE (Unemployment in India dataset)  
- **Files Used:**
  - `Unemployment in India.csv`  
  - `Unemployment_Rate_upto_11_2020.csv`  
- Columns include:
  - `date` → Observation date  
  - `state` → Indian state/region  
  - `unemployment_rate_pct` → Unemployment rate (%)  
  - `area` → Urban/Rural division  

---

## 📊 Visualizations
- **National unemployment trend** (with pre vs post COVID shading).  
- **Top 10 states by average unemployment** (monthly trends).  
- **State-wise comparison: Before vs After Lockdown (Jan–Mar vs Apr–Jun 2020)**.  
- **Interactive maps** of unemployment by state.  

---

## ✅ Conclusion
- The unemployment rate in India **spiked sharply after March 2020** due to the COVID-19 lockdown.  
- Some states consistently showed **higher unemployment** compared to the national average.  
- The **top 10 states** by unemployment experienced more volatility during the pandemic.  
- Almost all states saw a **rise in unemployment after lockdown** compared to the pre-lockdown months.  
- Plotly visualizations help in exploring the **spatial and temporal impact** of COVID-19 on unemployment.  

---

## ⚙️ How to Run
1. Open the notebook in **Google Colab**:  
   - Upload the dataset (`.csv` files).  
   - Run all cells sequentially.  

2. Install dependencies if needed:
   ```bash
   pip install plotly pandas
