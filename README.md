# margin-erosion-analysis-dashboard
Margin Erosion analysis using Excel with dashboards, KPIs, cost breakdown, pricing insights, and actionable recommendations.
This project analyzes **product, customer, region, and cost performance** to detect **margin erosion** and provide a fully interactive **Excel dashboard** for business decision-making. It highlights low-margin areas, cost drivers, and offers actionable recommendations to improve profitability.

---

## 🎯 Objective

The **Margin Analysis Dashboard** helps businesses:

- Track **yearly margin trends**
- Identify **top low-margin products & customers**
- Analyze **state-wise performance**
- Understand **cost buildup impact**
- Compare **Price vs Cost** to detect outliers
- Generate **executive insights & recommendations**

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Excel** | Data modeling, dashboard creation, KPIs |
| **Power Query** | Cleaning & transforming data |
| **Pivot Tables & Pivot Charts** | Insights & reporting |
| **Excel Functions (SUMIFS, LOOKUP, IF)** | Margin %, HVLM flag, cost calculations |
| **GitHub** | Version control & documentation |

---

## 📌 Key Performance Indicators (KPIs)

| KPI | Description |
|-----|-------------|
| **Average Margin %** | Measures profitability trend |
| **Total Revenue** | Total collected revenue |
| **Total Marginal Amount** | Profit after total cost deduction |
| **Marginal Loss** | Loss from negative-margin items |
| **HVLM Count** | High Volume Low Margin products |

---

## 🔄 Project Workflow

### 1️⃣ Data Preparation
- Cleaned product, customer, revenue, cost, and returns datasets.
- Created calculated fields: **Margin %**, **Total Cost**, **Net Revenue**, **HVLM flag**.
- Structured and normalized tables for pivot-ready analysis.

### 2️⃣ Margin Trend Analysis
- Designed a **Margin Trend Line Chart**.
- Added **CEO-level KPI cards**.
- Highlighted declining vs improving yearly margins.

### 3️⃣ Product & Customer Performance
- Identified **Top 5 Lowest Margin Products**.
- Visualized **customer-wise margin comparison**.
- Analyzed **state-wise YoY performance**.

### 4️⃣ Cost Buildup Waterfall Chart
- Calculated:
  - Base Cost  
  - Packaging Cost  
  - Freight Cost  
  - Other Cost  
- Visualized **total cost impact** on profitability.

### 5️⃣ Price vs Cost Scatter Plot
- Compared selling price vs cost for all products.
- Added a **reference line** to detect pricing issues.

---

# 🖼️ Dashboard Visualizations

Below are the key visual components included in the dashboard:

### 📌 KPI Cards  
- Average Margin %  
- Total Revenue  
- Total Marginal Amount  
- Marginal Loss  
- HVLM Count  

### 📈 Margin Trend Line Chart  
<img width="1168" height="626" alt="Screenshot 2025-12-13 105645" src="https://github.com/user-attachments/assets/708e19d5-8385-47b9-822b-552d40ba686f" />
- Shows year-by-year margin performance.

### 📉 Top 5 Lowest Margin Products
<img width="1470" height="651" alt="image" src="https://github.com/user-attachments/assets/b36ac58d-00a1-4bc8-9f9b-eb7dfeca0846" />
- Highlights critical items pulling margins down.

### 👥 Customer-wise Margin Analysis 
<img width="1816" height="643" alt="image" src="https://github.com/user-attachments/assets/18262afb-35dc-43b3-b474-d588d9685b58" />
- Identifies customers with unstable or low profitability.

### 🗺️ State-wise Margin % Comparison  
<img width="1713" height="663" alt="image" src="https://github.com/user-attachments/assets/bafb71cb-b369-4ab5-84bc-b75f39783d68" />
- Reveals regions contributing to margin erosion.

### 📦 Cost Buildup Waterfall Chart  
<img width="920" height="565" alt="image" src="https://github.com/user-attachments/assets/a8aadb74-1255-42af-bf47-b6254768b3a2" />

- Shows cost contribution of each cost component.

### ⚖️ Price vs Cost Scatter Plot 
<img width="946" height="516" alt="image" src="https://github.com/user-attachments/assets/13f17118-a457-452b-8e70-64cd23377e56" />
- Detects underpriced or loss-making items.
 
### pareto analysis
<img width="1277" height="651" alt="image" src="https://github.com/user-attachments/assets/cdc1a74d-35a3-4f89-96ba-b77c5dfd4c0f" />

- This Pareto chart shows that top loss-making products account for most of the margin erosion, enabling targeted improvement efforts.

Add screenshots under the **Screenshots** folder and reference them here.

---

# 💡 Insights

- Several **products consistently generate low margins** due to high cost or underpricing.
- **Customer-level margins** show significant volatility; some customers generate repeated losses.
- **Certain states underperform**, impacting overall margin.
- **Packaging and freight** contribute major spikes in total cost for certain product lines.
- A large number of **HVLM products** are hurting profitability despite high sales volume.

---

# 💡 Recommendations

- 🔄 Reprice **HVLM products** to minimize leakage.  
- 📦 Renegotiate **freight & packaging vendor contracts**.  
- 🛑 Reduce unnecessary **discounting** on low-margin items.  
- 🎯 Target customer segments & regions with declining profitability.  
- 🔔 Set up **automated margin drop alerts**.  
- 📈 Build a monthly **margin monitoring report** for management.  

---
