
# **Furniture Sales Performance Dashboard (Excel)**  
![Excel Badge](https://img.shields.io/badge/Tool-Microsoft_Excel-217346?logo=microsoftexcel)  
*A dynamic Excel dashboard analyzing U.S. furniture sales performance with interactive visualizations.*  

---
### **Preview**  
![Dashboard Screenshot](https://via.placeholder.com/800x500?text=Furniture+Sales+Dashboard+Preview)  
---
## **📌 Project Overview**  
This project is an **end-to-end Excel tutorial** demonstrating how to transform raw sales data into an interactive dashboard. It provides actionable insights into furniture sales performance across U.S. regions, covering data cleaning, pivot tables, charts, and dynamic filtering.  

**Target Audience**:  
- Sales Managers, Regional Directors, Inventory Planners

---
## **📂 About the Data**  
- **Source:** Real-world U.S. furniture sales (2014-2017).  
 ```plaintext
  Order_ID, Order_Date, Ship_Date, Ship_Mode, Customer_ID, Segment, City, State, Region, Product_Category, Sales, Profit, Quantity  
  ```  
- **Cleaning**: Handled missing values, standardized dates, removed duplicates in Power Query. 
- **Limitations:** Excludes returns; pre-tax figures.  
- **Refresh Instructions:**  

```plaintext 
Data → Refresh All (Updates all pivot tables) 
```
---

## **🛠️ Tools & Skills Applied**  
| **Category**         | **Details**                                                                 |
|----------------------|----------------------------------------------------------------------------|
| **Data Preparation** | Power Query (Cleaning, Transformation)                                     |
| **Analysis**         | Pivot Tables, Pivot Charts, Calculated Fields                              |
| **Visualization**    | Dynamic Titles, Map Charts, Trend Lines, Conditional Formatting            |
| **Interactivity**    | Slicers (Region/Segment), Drill-down Capabilities                          |
| **Design**           | Custom Layout, Color Themes, Dashboard Optimization for Readability        |

---

## **🔍 Key Questions This Dashboard Answers**  

### **1. "How are our furniture sales performing overall?"**  
- **Answer:** The dashboard’s **KPI cards** show:  
  - Total Sales: `$742.0k` (↑8% YoY)  
  - Total Profit: `$18.5k` (↓57% YoY)  
  - Quantity: `$8.0k` (↑11% YoY)  
- **Where to look:** Top-left section of the dashboard.  

### **2. "Which regions or customer segments drive the most revenue?"**  
- **Answer:** Use the **Region/Segment slicers** to filter and compare:  
  - Top Region: `West` (Contributes `34.04%` of sales).  
  - Top Segment: `Consumer` (Higher Sales value vs. Corporate).  
- **Pro Tip:** Click the map chart to drill down into state-level performance.  

### **3. "When do we see peak sales periods?"**  
- **Answer:** The **monthly trend line** highlights:  
  - Best Months: `December` (Holiday season, `121.8k` in sales).  
  - Worst Month: `February` (Suggest promotions here).  
- **Actionable Insight:** Align inventory stocking with cyclical trends.  

### **4. "What’s our most popular shipping method, and how does it impact costs?"**  
- **Answer:**  
  - `Standard Class` (used in `59%` of orders) has the lowest shipping cost but longest delivery time.  
  - `Same Day` shipping has `6%` lower profit margins due to higher logistics costs.  

### **5. "Which product categories or cities should we focus on?"**  
- **Answer:**  
  - **Top Category:** `Chairs` (Generates `$328.4k` in sales).  
  - **Underperforming Category:** `Furnishings` (Generates `$91.7k` in sales).  
  - **Top City:** `New York` (High quantity `720` but profit 5.3k).  

---

## **🚀 How to Use This Dashboard**  
### **For Sales Managers:**  
1. **Identify growth opportunities**: Filter by region to allocate resources.  
2. **Track YoY trends**: Compare 2023 vs. 2024 metrics (hover over KPI cards).  

### **For Inventory Teams:**  
1. **Anticipate demand**: Use monthly trends to adjust stock levels.  
2. **Optimize shipping**: Balance cost vs. speed based on the shipping mode analysis.  

### **For Executives:**  
- **Export visuals** (Right-click → Copy as Image) for presentations.  
---

## **📊 Dashboard Features**  
### **1. Key Metrics**  
- **Total Sales, Profit, Quantity** with YoY % growth indicators.  
- **KPI Cards**: Highlight trends using conditional formatting (↑/↓ arrows).  

### **2. Shipping Analysis**  
- **Shipping Mode Distribution**: Bar/pie charts showing preferred methods (e.g., Standard Class).  
- **Shipping Duration**: Histogram of delivery days (average vs. outliers).  

### **3. Sales Trends**  
- **Monthly Sales Line Chart**: Identifies peak months (e.g., December).  
- **Annotations**: Highlights key events (e.g., promotions).  

### **4. Geographic Insights**  
- **State-wise Sales Map**: Heatmap of sales by U.S. state.  
- **Top Cities Table**: Ranks cities by order quantity (Top 10).  

### **5. Interactive Filters**  
- **Slicers**: Region (East/West), Segment (Consumer/Corporate).  
- **Dynamic Titles**: Automatically update based on filters.  
---

### **Analysis Workflow**  
1. **ETL**: Power Query transformed raw data into a structured table.  
2. **Pivot Tables**: Calculated metrics (e.g., YoY growth = `(Current Year - Prior Year)/Prior Year`).  
3. **Visualization**: Charts linked to pivot tables for real-time updates.  

---

## **🎨 Design Choices**  
- **Color Palette**: Neutral tones with accent colors for KPIs.  
- **Layout**: Grid-based for clarity; metrics prioritized top-left (F-pattern reading).  
- **Fonts**: Aptos Narrow (readability) + bold headers for hierarchy.  

---

## **❓ Frequently Asked Questions**  

### **"Why do some states show zero sales on the map?"**  
- **Answer:** Data may not cover all states. Check filters or data scope.  

### **"How often should we update this dashboard?"**  
- **Answer:** Monthly (aligned with accounting cycles).  

### **"Can we add competitor benchmarking?"**  
- **Answer:** Yes! Provide competitor data in CSV format → I’ll extend the Power Query pipeline.  
### **"Why is my map chart not working?** " 
- **Answer:** Ensure you have Excel’s **Geography Data Type** enabled (Data → Geography).   

---

## **📧 Contact for Support**  
- **Questions?** Email `nelson.mforbi@gmail.com` or open a [GitHub Issue](link).  

---

## **🤝 How to Contribute**  
- Report bugs via [Issues](https://github.com/your-repo/issues).  
- Suggest design improvements or additional metrics.  

---

## **📜 License**  
MIT License. See [LICENSE](LICENSE) for details.  

---


