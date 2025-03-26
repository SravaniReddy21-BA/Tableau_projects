# Tableau_projects
A collection of Tableau dashboards and data visualization projects for business analytics, operations, and storytelling.

## 🏡 King County, Washington House Sales Dashboard

📍 [**View Interactive Dashboard on Tableau Public**](https://public.tableau.com/app/profile/sravani.tathikonda/viz/KingCountyDashboard_17430055992750/KingcountySales?publish=yes)

![KingcountySales](https://github.com/user-attachments/assets/92fd1088-60ec-4947-9eb6-dfd4705e442b)

### 📌 Project Overview

This project involves building an interactive dashboard in Tableau to analyze residential property sales in **King County, Washington (USA)**. The dataset contains detailed records of over 21,000 real estate transactions, including features like sale price, number of bedrooms and bathrooms, square footage, lot size, year built, view, and condition.

The goal was to transform raw sales data into a powerful, visual analytical tool that helps stakeholders—such as real estate analysts, agents, or potential investors—gain actionable insights into housing trends, price distributions, and the influence of property features.

---

### 📊 Key Dashboard Features

- **📅 Time Series Analysis**  
  Track the trend of daily average house sale prices across April 2015.

- **🗺 Geographic Mapping**  
  A filled map highlights ZIP code regions based on average sale prices, enabling spatial analysis of high-value and affordable areas.

- **📈 Distribution Visuals**  
  Histograms show how house prices, bedrooms, and bathrooms are distributed, offering insight into common property types.

- **🌡 View vs Condition Heatmap**  
  A matrix chart comparing the interaction between property **condition** and **view quality** against average price.

- **📍 Interactive Filters**  
  Users can filter by:
  - Month and Day
  - Year Built
  - Square Footage (Living Area and Lot Size)

---

### 📁 Dataset Description

The dashboard was built using `HouseData.xlsx`, which includes the following fields:

- `Price`: Sale price of the house
- `Date`: Date of sale
- `Bedrooms`, `Bathrooms`
- `Sqft_living`, `Sqft_lot`
- `Floors`, `Waterfront`, `View`, `Condition`
- `Grade`: Construction and design quality
- `Yr_built`, `Yr_renovated`
- `Zipcode`, `Lat`, `Long`

---

### 🧠 Insights Extracted

- Most houses are priced between **$300,000 - $600,000**
- Properties with better **views and conditions** tend to have higher sale prices
- Homes built after 2000 show slightly higher average pricing
- Certain ZIP codes like **98039 and 98004** have consistently higher property values

---

### 🛠 Tools & Techniques Used

- **Tableau Public** for interactive visualizations
- **Bins** and **calculated fields** for data grouping
- **Mapbox** integration for geographic mapping
- **Parameter controls** and **dashboard actions** for interactivity
- Basic data cleaning and transformation within Tableau

---

### ✅ Outcome

This dashboard provides an intuitive way to analyze and interpret real estate trends in King County. It supports filtering, geographic drill-downs, and multi-variable comparisons, making it useful for both technical and non-technical users.

---
