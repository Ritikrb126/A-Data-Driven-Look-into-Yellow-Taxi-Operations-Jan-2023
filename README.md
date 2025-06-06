# A-Data-Driven-Look-into-Yellow-Taxi-Operations-Jan-2023
# 🚌 NYC Yellow Taxi Analysis - January 2023

# 📅 Description

A comprehensive data-driven analysis of 3.07 million Yellow Taxi trips recorded in New York City during January 2023. This project identifies peak demand zones, passenger trends, revenue patterns, data quality concerns, and operational inefficiencies. The goal is to derive actionable insights that support taxi operations, city planning, fare regulation, and data quality improvements.

---

## Overview :

This project leverages a dataset containing over **250,000 Airbnb listings** across **10 major global cities**, enriched with detailed host information, prices, locations, room types, and more than **5 million guest reviews**. It aims to provide insights into market behavior, pricing evolution, and the regulatory impact on the short-term rental ecosystem.

## 📌 Objectives
- Understand trip volume and duration patterns across hours and days
- Identify peak demand times and popular pickup/drop-off zones
- Examine fare distribution, passenger counts, and payment types
- Analyze airport and borough-wise trip behaviors
- Assess the impact of congestion surcharge during peak hours

## 🧰 Tools & Technologies

- Python 3
- Jupyter Notebook
- Pandas, NumPy
- Seaborn, Matplotlib
- Sources: NYC Taxi & Limousine Commission, Bloomberg, NYC Open Data

---

## 📁 Dataset

- Name: NYC Yellow Taxi Trip Data - January 2023
- Size: 3.07 million records, 19 columns
- Provided by: NYC TLC (Taxi & Limousine Commission)
- Main Features:
    - Pickup/Dropoff Timestamps & Locations
    - Passenger Count
    - Trip Distance & Duration
    - Fare, Surcharges, Tolls, Tips
    - Payment Type
- Dataset Source : [NYC Yellow Taxi Analysis - January 2023](https://www.kaggle.com/datasets/ritikrb/tlc-yellow-taxi-trips-dataset)

**Source**: Assumed local or from [Inside TLC](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

---

## 📊 Key Analysis Performed

- ✅ Data cleaning and preprocessing (null handling, type conversions)
- Data Preprocessing
- Feature Engineering
- 📈 Exploratory Data Analysis (EDA)
- Outlier Treatment
- Payment Behavior & Tipping Trends
- Zone & Time Heatmaps
- Airport and Toll Trends

---

## Project Link

[NYC_Yellow_Taxi_Trip_Analysis](https://www.kaggle.com/code/ritikrb/nyc-yellow-taxi-trip-analysis)

<img src="https://s.abcnews.com/images/Business/nyc-taxis-gty-rc-200220_hpMain.jpg" width="1000">


## Final Insights
### 1.Data Quality Concerns:
- Vendor 2 (Creative Mobile Technologies) contributed ~66% of data with missing or invalid entries (e.g., passenger count = 0, payment type = 0).
- Several extreme values (e.g., trip distance over 258,000 miles) indicate entry errors needing cleansing.
  
### 2.Passenger Behavior:
- 81% of trips were paid via credit card, showing high trust and digital payment preference.
- Most passengers travel solo or in pairs. Very few trips involve more than 4 people.
  
### 3.Time & Location Patterns:
- Midday (1 PM–4 PM) and Evening (4 PM–7 PM) are peak hours.
- Tuesday is the busiest day, with Sunday having longer average trips.
- Manhattan dominates both pickup and drop-off locations (~89%).
- High-demand hotspots: Midtown Center, JFK Airport, Upper East Side, and Penn Station.
  
### 4.Airport Trip Trends:
- Most airport trips are during midday and rush hours.
- A noticeable one-way fare bias (e.g., Laguardia to Times Sq costs more than return trip).
  
### 5.Trip Metrics:
- Average duration: 14.5 min
- Average distance: 3.4 miles
- Average fare per mile: $8.15
- Highly skewed distributions indicate the presence of long and costly trips affecting averages.
  
### 6.Revenue Drivers:
- Majority of revenue (80–85%) comes from:
Fare Amount + Tips + Congestion Surcharge
- Most revenue is generated within Manhattan and from airport zones (especially JFK).
  
### 7.Efficiency Gaps:
- Short trips (under a mile) often take more time per mile, indicating inefficiency.
- Cash trips report almost no tips, suggesting possible underreporting or avoidance.
 
## Recommendation 
### Data Governance:
- Flag and review data submitted by Vendor 2. Encourage better validation on their end.
- Filter out extreme outliers using median + 2×std logic for a more robust analysis.
  
### Operational Optimization:
- Allocate more taxis to Midtown and airport routes during peak midday and evening hours.
- Consider improving route optimization for short trips with high duration-per-mile inefficiency.
  
### Policy Insights:
- Investigate fare asymmetry between airport routes to ensure fairness in toll and surcharge application.
- Promote credit card or digital payment incentives—these trips consistently show higher tip amounts.
  
### Customer Service Enhancements:
- Deploy more vehicles in high-demand time slots and areas: Tuesdays, 1–7 PM in Midtown and JFK.
- Explore ride pooling or discounted group fares in areas with low occupancy efficiency.
  
### Fare Structure Transparency:
- Educate passengers on surcharge breakdowns (e.g., congestion fees, tolls, airport fees).
eption Risks:
- If the customer experience is affected due to these regulations, it may lead to an incorrect or negative brand perception.
nced ecosystem.

## 🧠 Conclusion

January 2023 Yellow Taxi data provides a detailed snapshot of NYC’s urban mobility. The findings highlight that Manhattan is the pulse of city movement, especially during midday and evening, while airport routes remain top revenue generators. However, data quality concerns—especially from certain vendors—must be addressed to maintain analytical reliability. By targeting high-efficiency zones and optimizing fare structures, the city can improve passenger experience, taxi availability, and fare fairness.


