# Global Economic Indicators Dashboard  

📊 **Project Overview**  
A comprehensive Power BI dashboard analyzing global economic indicators using World Bank data. The report visualizes relationships between GDP, population, and temperature changes across countries, with drill-down capabilities to explore detailed country-level metrics.  

---

## **Dashboard Features**  

### **🌍 Global Economic Overview**  
- **GDP vs. Temperature Change**: Examines the correlation between GDP (in constant 2015 USD) and global temperature anomalies.  
- **Total Countries by Region**: Bar chart distribution of countries across Europe, Sub-Saharan Africa, Latin America, East Asia, and more.  

### **📈 Country Drill-Down Page** *(Interactive Detail View)*  
When a user selects a country (e.g., **Macao SAR, China**) via the **Drillthrough** feature, the dashboard displays:  

| **Metric**               | **Value**          |  
|--------------------------|--------------------|  
| **2020 Population**      | 0.68M              |  
| **2020 GDP**             | $23.37bn          |  
| **Population Density**   | 205,557/km²       |  
| **GDP Per Capita**       | $34,562           |  

- **Time-Series Analysis**:  
  - **GDP Trends (2001–2021)**: Line chart showing annual GDP fluctuations (e.g., a 54.24% drop in 2020).  
  - **GDP Growth %**: Highlights economic volatility (e.g., 21.62% growth in 2011 vs. -21.51% decline in 2015).  
  - **Population Changes**: Tracks demographic shifts over time.  

- **Key Insight**: Macao’s economy heavily relies on tourism, explaining its sharp GDP swings during crises (e.g., COVID-19).  

---

### **📸 Dashboard Screenshots**

1. **Global View**  
   - Heatmap of GDP vs. population density.  
   - Regional breakdown of economic output.  

2. **Drill-Down Page** *(Example: Macao SAR, China)*  
   - **Top Section**: Key metrics (GDP, population).  
   - **Middle Section**: Time-series charts (GDP growth, population trends).  
   - **Bottom Section**: Comparative analysis (e.g., GDP per capita vs. regional averages).  

---

## **🛠️ Technical Implementation**  
### **Data Pipeline**  
- **Source**: World Bank API ([databank.worldbank.org](https://databank.worldbank.org)).  
- **Key Datasets**:  
  - `NY.GDP.MKTP.KD` (GDP in constant USD).  
  - `SP.POP.TOTL` (Total population).  
- **Processing**: Power Query cleans and aggregates data by country/year.  

### **Metrics Calculated**  
- **Economic**: GDP growth %, GDP per capita.  
- **Demographic**: Population density, regional distributions.  

### **Tools Used**  
- **Power BI**: Visualizations (maps, line charts, tables).  
- **Drillthrough**: Enables dynamic country-level analysis.  
- **DAX**: Formulas for growth rate calculations.  

---

## **▶️ How It Works**  
1. **Global Analysis**: Users explore macro trends (e.g., GDP vs. temperature).  
2. **Drill Down**: Right-click a country to view its detailed economic profile.  
3. **Dynamic Filtering**: Adjust time ranges or regions for comparative insights.  

---

### **📌 Key Insights**  
- **High-Density Economies** (e.g., Macao, Monaco) show extreme GDP per capita but vulnerability to external shocks.  
- **Regional Disparities**: Sub-Saharan Africa has lower GDP/capita vs. North America.  
