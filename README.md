# **MIST 4610 Group Project 2: Real Estate Sales 2001-2024**
**Team Name** <br>
59925 Group 3

## **Team Members:** <br>
David Kenny @djk42296 <br>
Sahasra Manchikanti @sahasra-22 <br>
Grant Harris @gaharris13 <br>
Joseph Enck @havemercy74<br>
Sofia Drescher @s-drescher

## Dataset Overview

This dataset contains **20+ years of property sale transactions**, capturing sale prices, property classifications, locations, and assessment details across the U.S. It enables analysis of **housing trends, price dynamics, and geographic market behavior**.

### **Relevant Columns**
- **Date Recorded**
- **Sale Amount**
- **Property Type**
- **Residential Type**
- **Address**
- **Latitude and Longitude**

There were **~1.5 million records** in total, so we filtered the dataset by year range to make the analysis manageable.

### **Data in Table View** <br>
<img width="350" height="358" alt="Screenshot 2025-11-21 at 3 34 05 PM" src="https://github.com/user-attachments/assets/d8451a80-4d76-4f44-8967-93edd727bc37" /> <br>

<img width="551" height="358" alt="Screenshot 2025-11-21 at 3 35 25 PM" src="https://github.com/user-attachments/assets/9704eb4e-1469-4fd2-849c-564cec234f3d" /> <br>

<img width="214" height="356" alt="Screenshot 2025-11-21 at 3 35 59 PM" src="https://github.com/user-attachments/assets/cb300a61-8142-4617-b5ab-dabe040e0225" />

---

## Why This Dataset Matters

The real estate market is a major indicator of **economic health**, **consumer confidence**, and **regional development**.

Understanding sales patterns helps identify:

- **Housing Demand**
- **Urban Growth**
- **Market Volatility**

This dataset interests us because it brings together insights about how money moves in the housing market, how different areas grow, and what those patterns suggest about the future.

---

# Question 1 — How have property sales changed over time, and what can we forecast about monthly & yearly sales trends?

### **Line Chart — “Amount of Sales per Month with Forecast”**  
<img width="712" height="448" alt="Screenshot 2025-11-21 at 3 36 37 PM" src="https://github.com/user-attachments/assets/de80c1a1-8701-4ff8-8af1-e7a15a7c4b6b" />


**Why this matters:**  
Real estate cycles reflect **economic shifts**, **pandemic impacts**, and **seasonal buying patterns**.

### **Key Patterns**
- Strong seasonality, with peaks in mid-year
- A large decline in 2023–2024, likely tied to interest rate hikes
- Forecast suggests recovery through 2025


### **Bar Chart — “Average Sale Amount by Property Type (2021–2023)”**  
<img width="760" height="445" alt="Screenshot 2025-11-21 at 3 37 08 PM" src="https://github.com/user-attachments/assets/160c552c-ca9f-47b0-8217-16e4d12e7d2f" />


### **Key Insights**
- Clear yearly **seasonality**
- Sales spike in **spring–summer**, drop in **winter**
- **Pandemic-era surge (2020–2021)** demonstrates elevated demand
- **Sharp decline in 2023–2024**, possibly due to high mortgage rates and low inventory
- Forecast shows **upward trend in 2025** (with wide confidence intervals)


# Question 2 — How Do Property Types Differ in Total Sale Amount Across the U.S.?  

### **Geo Map — Property Type Distribution Across the U.S.**  
<img width="592" height="464" alt="Screenshot 2025-11-21 at 3 37 49 PM" src="https://github.com/user-attachments/assets/3d64f301-20ef-42f8-864a-5f4cbb169c3d" />


**Why this matters:**  
Understanding which property types dominate each region explains local market behavior.

### **Key Patterns**
- High-value transactions cluster around major metros
- Single Family and Condo dominate most regions
- Commercial, Industrial, and Apartments produce large but isolated spikes
- Vacant land clusters in rural/expanding regions
- Geographic differences are major drivers of sale variability


### **Bar Chart — Total Sale Amount by Property Type Across the U.S.**  
<img width="732" height="463" alt="Screenshot 2025-11-21 at 3 38 20 PM" src="https://github.com/user-attachments/assets/9cadbde0-5157-4064-934c-bb85586e83cd" />


### **Key Insights**
- **Single Family homes** represent most transactions nationwide
- Large value clusters in **coastal** and **Midwest metro** areas
- Commercial/industrial properties cause **big spikes** in certain markets
- Regions show **clear specialization**
- **Value density ≠ transaction density**
- Industrial values cluster around **logistics hubs**


# 03 — Data Preparation & Findings  
## Data Preparation

- Converted coordinates (Latitude/Longitude auto-generated in Tableau)
- Filtered dataset by year range
- Removed null sale amounts or missing category data
- Applied a forecasting model
- Grouped property types for cleaner visualization


## Importance of Findings

### **Buyers**
- Seasonal timing matters — winter = lowest competition

### **Policymakers**
- High-value clusters may indicate where zoning or infrastructure changes are needed

### **Communities**
- Property type trends support development planning and housing affordability

### **Businesses**
- Regional specialization helps guide strategy and investment


# Conclusion

### **Final Takeaways**
- Real estate activity follows **predictable seasonal and economic cycles**
- Property types cluster differently across regions, shaping **value patterns**
- Forecast shows **potential rebound** in sales over the next several months
- Dataset provides strong insights for **buyers, investors, and policymakers**

### *Note:*

Workbooks are attached and seperated by question. Each workbook contains two visualizations. PDF for presentation is also attached.

