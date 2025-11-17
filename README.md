# AtliQ-Hotels-Data-Analysis-Project
This project involved a Python data analysis for Atliq Grands, a major Indian hotel chain, to address declining revenue and market share. Key insights revealed high weekend (72.39%) vs. low weekday (50.90%) occupancy, with Delhi leading cities (61.61%). Strategies focus on strengthening weekday performance and expanding demand in weaker segments.

# Atliq Hotel Analysis Project - Python

## **Problem Statement**

Atliq Grands, a prominent player in India’s hospitality industry, is currently facing mounting challenges due to rising competition, declining revenues, and a loss of market share. To address these issues, the management team has chosen to leverage data-driven insights. With limited internal expertise in analytics, they have sought external support to evaluate the situation, generate actionable insights, and design strategies aimed at customer retention and revenue growth.

## **Project Goal**

The objective of this project is to conduct a comprehensive analysis of the hotel industry domain using Python. By applying data-driven techniques and strategic recommendations, the aim is to empower Atliq Grands to make informed decisions. Ultimately, the project seeks to help the company regain its competitive edge, counter revenue decline, and recover lost market share.

## **Datasets**
- `dim_date.csv`  
- `dim_hotels.csv`  
- `dim_rooms.csv`  
- `fact_bookings.csv`  
- `new_data_august.csv`  
- `fact_aggregated_bookings.csv`  

## **Data Analysis Process**
1. **Data Import & Exploration** – Imported datasets (bookings, hotels, room categories) and assessed structure and quality.  
2. **Data Cleaning** – Handled missing values, corrected inconsistencies, and removed outliers to ensure reliability.  
3. **Data Transformation** – Engineered new variables (e.g., occupancy percentage) and merged datasets for a holistic view.  
4. **Insights & Visualization** – Analyzed occupancy, revenue, and booking trends; visualized findings using Python libraries.  
5. **Key Insights Summary** – Consolidated findings into clear, actionable insights.  
6. **Recommendations** – Proposed strategies to address identified business challenges.  

---

#  Tools & Functions Used
- **Pandas** – Data manipulation and analysis (`groupby`, `merge`, `describe`).  
- **NumPy** – Numerical operations and derived metrics (e.g., occupancy percentage).  
- **Matplotlib** – Visualization (bar charts, pie charts, line plots).  
- **Data Cleaning Techniques** – Missing value imputation, format corrections, outlier removal.  

---

#  Key Insights

**Average Occupancy by Room Type**  
- Presidential rooms: highest average occupancy (59.30%).  
- Elite & Premium rooms: lowest occupancy (~58%).  

**Average Occupancy Rate per City**  
- Delhi: highest average occupancy (61.61%).  
- Bangalore: lowest (56.59%).  

**Weekday vs. Weekend Occupancy**  
- Weekends: significantly higher occupancy (72.39%) vs. weekdays (50.90%).  

**Occupancy Rates in June**  
- Delhi: highest (62.47%).  
- Bangalore: lowest (56.58%).  

**Revenue Realized per City**  
- Mumbai: highest revenue (`$668,569,251`).  
- Bangalore: lowest revenue (`$420,383,550`).  

**Revenue by Hotel Type**  
- Atliq Exotica: highest revenue (`$32,436,799`).  
- Atliq Seasons: lowest revenue (`$6,672,245`).  

**Average Rating per City**  
- Delhi: highest average rating (3.79).  
- Bangalore: lowest average rating (3.41).  

---

#  Recommendations

**1. Expand Demand in Underperforming Segments**  
- Use targeted promotions and partnerships to boost occupancy in less popular room types and cities.  

**2. Strengthen Weekday Performance**  
- Introduce corporate tie-ups and weekday-specific offers to balance occupancy rates.  

**3. Align Strategies with Revenue & Ratings**  
- Focus improvement efforts on cities and hotel types with lower revenue and ratings.  

**4. Institutionalize Data-Driven Decision Making**  
- Regularly integrate and analyze new datasets to guide forecasts and proactive decisions.  

**5. Elevate Customer Satisfaction**  
- Invest in staff training and service quality, particularly in locations with lower ratings.  

**6. Optimize Marketing Investments**  
- Tailor campaigns using historical data to target high-potential markets and maximize occupancy.  

---

##  Key Learnings
- **Data Cleaning** – Handling outliers and inconsistencies is essential for reliable insights.  
- **Visualization** – Clear, effective charts enhance understanding and communication.  
- **Strategic Analysis** – Derived metrics and merged datasets reveal hidden patterns critical for decision-making.  

---

#  Conclusion
This project provided valuable experience in applying Python-based data analysis to real-world business problems. The insights generated offer Atliq Grands a roadmap to strengthen competitiveness, improve customer satisfaction, and drive sustainable revenue growth.
