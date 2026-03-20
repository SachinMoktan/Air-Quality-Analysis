#  Air Pollution Analysis & Health Impact Visualization

##  Overview
Air pollution is a major global concern affecting public health and environmental sustainability. This project analyzes large-scale air quality data to uncover pollution patterns, identify high-risk regions, and understand the potential health impacts using data-driven techniques.

The project combines **big data processing (PySpark)** and **data visualization (Tableau)** to transform raw environmental data into meaningful insights.



##  Objectives
- Analyze air pollution trends across cities and time periods  
- Identify key pollutants contributing to poor air quality  
- Understand seasonal and regional variations in AQI  
- Explore potential health impact indicators  
- Build interactive dashboards for better decision-making  



##  Tools & Technologies
- Python  
- PySpark  
- Pandas  
- Tableau  
- Google Colab  
- VS Code  


##  Dataset
- Source: Kaggle Air Quality Dataset (`city_day.csv`)  
- Contains:
  - AQI (Air Quality Index)
  - PM2.5, PM10
  - NO₂, SO₂, CO, O₃
  - Date, City information  



## ⚙️ Data Processing Steps

### 1. Data Cleaning
- Removed null values  
- Handled missing pollutant readings  
- Standardized data formats  

### 2. Feature Engineering
- Extracted:
  - Year
  - Month
  - Weekday  
- Created AQI categories (Good, Moderate, Poor, etc.)

### 3. Data Transformation
- Aggregated AQI by city and year  
- Prepared datasets for visualization  



## 📈 Visualizations (Tableau)

Key dashboards created:

-  AQI Trend Over Years by City  
-  Top 10 Most Polluted Cities  
-  AQI Distribution by Month  
-  Heatmap (City vs Year)  
-  Map Visualization (Geographic AQI)  
-  Pollutant Comparison (PM2.5, NO₂, etc.)  
-  Weekday vs AQI Analysis  



## 🔍 Key Insights

- Urban areas show consistently higher AQI levels  
- PM2.5 is the most dominant pollutant affecting air quality  
- Seasonal variation shows higher pollution in winter months  
- Certain cities consistently rank among the most polluted  
- Pollution trends indicate strong correlation with industrial and traffic activity  



##  Business & Real-World Impact

This analysis can help:

- Governments improve environmental policies  
- Health organizations assess risk exposure  
- Urban planners design cleaner cities  
- Researchers understand pollution trends  



##  Future Improvements

- Add real-time air quality data integration  
- Apply machine learning for AQI prediction  
- Build a web dashboard for live monitoring  
- Integrate health data for deeper impact analysis  



##  Project Structure
├── data/
├── notebooks/
│ └── air_pollution_analysis.ipynb
├── visuals/
│ └── tableau_dashboards.png
├── README.md




##  Author

**Sachin Moktan**  
Data Analyst | AI Enthusiast  

📍 Kathmandu, Nepal  
🔗 LinkedIn: https://www.linkedin.com/in/sachinmoktan/  

---

## \ If you found this project useful, consider giving it a star!
