# Uber_Data_Analysis
# 🚖 Uber Trip Analysis Dashboard: Booking, Revenue & Trip Efficiency Insights  

## 1. Short Description / Purpose  
The **Uber Trip Analysis Dashboard** is an interactive Power BI solution designed to analyze Uber ride data, focusing on booking trends, revenue generation, and trip efficiency. This dashboard empowers stakeholders to make data-driven decisions on pricing, driver allocation, and customer satisfaction by providing real-time insights into ride patterns across time, location, and vehicle types.  

---

## 2. Tech Stack  
- **Power BI Desktop** – Core visualization and analytics platform  
- **Power Query** – Data cleaning, shaping, and joining multiple sources  
- **DAX (Data Analysis Expressions)** – KPI calculations for revenue, bookings, trip distances, and time analysis  
- **SQL** – For KPI validation and backend cross-checking  
- **Excel** – Used for data preprocessing and supplementary analysis  
- **Data Modeling** – Relationships built between trips, locations, vehicles, and payments  
- **PBIX File** – Development and deployment format  

---

## 3. Data Source  
Uber trip dataset (internal simulation) covering ride transactions across multiple cities.  

Data fields included:  
- **Trip Details**: Trip ID, Pickup/Drop-off Time, Distance, Duration, Fare, Surge Fee  
- **Payment Info**: Payment type (Card, Cash, Wallet)  
- **Location Info**: Pickup & Drop-off Locations  
- **Vehicle Types**: Sedan, SUV, Mini, Premium  
- **Time Dimensions**: Hourly, Daily, Weekly breakdowns  

---

## 4. Features / Highlights  

### • Business Problem  
Uber stakeholders lacked a consolidated view of **booking demand, revenue drivers, trip efficiency, and geographic patterns**. Without this, decision-making around pricing strategies, driver allocation, and customer engagement was inefficient.  

### • Goal of the Dashboard  
To provide an **interactive analytics platform** to:  
- Track **Total Bookings, Revenue, Average Fare, Trip Distance, and Trip Time**  
- Compare booking patterns across **day/night** and **payment methods**  
- Identify **top-performing and underperforming locations**  
- Highlight **most preferred vehicles** and demand clusters  
- Provide **drill-through analysis** for raw trip-level details  

### • Walkthrough of Key Visuals  

**KPI Cards (Top Center)**  
- Total Bookings  
- Total Booking Value  
- Average Booking Value  
- Total & Average Trip Distance  
- Average Trip Time  

**Dynamic Measure Selector**  
- Enables switching between metrics like *Bookings, Revenue, Distance* for flexible reporting.  

**By Payment Type & Trip Type (Card vs. Cash, Day vs. Night)**  
- Compares demand and revenue distribution.  

**Vehicle Type Analysis (Matrix Table)**  
- Breaks down KPIs across Sedan, SUV, Mini, and Premium.  
- Conditional formatting highlights high and low performers.  

**Total Bookings by Day (Line Chart)**  
- Identifies weekday vs. weekend demand trends.  
- Detects external event impacts (holidays, weather).  

**Location Analysis**  
- *Top 5 Pickup & Drop-off Points* for demand forecasting.  
- *Farthest Trip* for analyzing outlier rides.  
- *Most Preferred Vehicle per Location* for strategic fleet alignment.  

**Time Analysis Dashboard**  
- **Area Chart (10-Minute Intervals)** – Peak and off-peak demand.  
- **Line Chart by Day Name** – Weekday vs. weekend performance.  
- **Heatmap (Hour vs. Day)** – Identifies busiest booking windows.  

**Details Tab (Grid View with Drill-through)**  
- Full trip-level breakdown for selected visuals.  
- Export functionality for raw data in Excel/CSV.  

---

## 5. Business Impact & Insights  

📈 **Revenue Optimization** – Dynamic pricing opportunities identified by comparing day vs. night demand.  

📊 **Location Intelligence** – Top 5 demand clusters optimized for driver allocation and surge pricing.  

🚗 **Vehicle Preference Insights** – SUVs dominated long-distance travel, while Sedans remained most popular for short rides.  

📉 **Trip Efficiency Risks** – Average trip time and farthest trip analysis highlighted delays in certain high-traffic routes.  

🔍 **Data-Driven Decision-Making** – SQL validation ensured KPIs were accurate and trusted by stakeholders.  

---

✅ **Outcome**: The Uber Trip Analysis Dashboard provided a **unified decision-making tool**, enabling Uber to improve **pricing strategies, demand forecasting, and customer satisfaction**, while also empowering teams with self-service analytics.    
