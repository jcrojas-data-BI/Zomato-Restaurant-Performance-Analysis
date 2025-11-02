# 🍽️ ZOMATO RESTAURANT PERFORMANCE ANALYSIS (TABLEAU PROJECT)

## 📖 Overview
This project is part of my **Business Intelligence Analyst portfolio**, representing a complete end-to-end analytical process — from defining the research plan to developing interactive Tableau dashboards and presenting insights in a structured business story.

The analysis explores the performance of restaurants listed on **Zomato**, a major food delivery and restaurant aggregator platform.  
It aims to uncover patterns in popularity, revenue, and performance drivers to guide data-driven business decisions.

The Tableau Story is structured into four connected dashboards:

1. **Overview** – Understanding dataset composition and general trends  
2. **Popularity Analysis** – Identifying which restaurants and cuisines attract customers  
3. **Revenue Analysis** – Revealing which restaurants generate the highest revenue  
4. **Performance Drivers** – Connecting cost, rating, and engagement to overall performance  

---

## 🎯 Research Plan

### Objective
To analyze restaurant performance on Zomato and identify factors that make certain restaurants more successful than others.

### Research Questions
1. Which restaurants and cuisines are most popular?  
2. Which ones generate the most revenue and why?  
3. How do ratings, cost, and city location influence performance?  
4. What recommendations can be made to improve profitability and customer satisfaction?

### Hypotheses
- Highly rated restaurants receive more votes and engagement.  
- Affordability and good service drive higher retention.  
- City concentration affects visibility and competitiveness.  

### Data Preparation Steps
- Cleaned missing or invalid ratings (“--” replaced with `NULL`).  
- Converted local currencies to USD using the most recent exchange rate.  
- Standardized restaurant names and cities for aggregation.  
- Added calculated fields for `Revenue_USD` and `Avg_Cost_Converted`.  
- Imported into Tableau for visualization and exploration.

---

## 📊 Dashboard Story Components

### 1️⃣ Overview Dashboard
**Purpose:**  
Provides a summary of the dataset, including restaurant count, average rating, number of cuisines, and key markets.  

**Insights:**  
- India dominates the dataset with the highest number of restaurants.  
- Delhi and Mumbai emerge as key competitive hubs.  

**Interpretation Guidance:**  
Start here when presenting — use this view to set the context about scale and data diversity.

**Visual Example:**  
![Overview Dashboard](images/overview_dashboard.png)

---

### 2️⃣ Popularity Analysis
**Purpose:**  
Explores which restaurants and cuisines attract the most engagement, measured by ratings and votes.

**Insights:**  
- Indian and Asian cuisines dominate customer engagement.  
- Restaurants in the mid-cost range receive higher votes and ratings.  

**Interpretation Guidance:**  
Explain how affordability and familiarity drive preference. Encourage exploring filters by cuisine and city.

**Visual Example:**  
![Popularity Dashboard](images/popularity_dashboard.png)

---

### 3️⃣ Revenue Analysis
**Purpose:**  
Focuses on identifying which restaurants generate the most revenue (converted to USD).

**Insights:**  
- High-end restaurants have higher per-order revenue but not necessarily higher ratings.  
- Top earners are typically in metro cities with premium service offerings.  

**Interpretation Guidance:**  
When presenting, highlight that profitability ≠ customer satisfaction — both need to be balanced.

**Visual Example:**  
![Revenue Dashboard](images/revenue_dashboard.png)

---

### 4️⃣ Performance Drivers
**Purpose:**  
Combines multiple variables to show relationships between cost, rating, and engagement.

**Insights:**  
- High-rated, mid-cost restaurants represent the optimal performance zone.  
- Some expensive restaurants show declining ratings — potential service mismatch.  

**Interpretation Guidance:**  
Use this as the “story conclusion” — it connects all previous dashboards and shows what actually drives success.

**Visual Example:**  
![Performance Drivers Dashboard]<img width="1657" height="965" alt="Overview" src="https://github.com/user-attachments/assets/c4ca9523-d901-483f-b8e5-218780716c7a" />


---

## 🧭 How to Use the Dashboard

### Instructions
1. Open `Zomato_Restaurant_Analysis.twbx` in **Tableau Public** or **Tableau Desktop**.  
2. Navigate through the story: **Overview → Popularity → Revenue → Performance Drivers**.  
3. Use filters for:
   - City  
   - Cuisine  
   - Cost category  
   - Rating group  
4. Hover over data points for restaurant-level tooltips.

### Live/Recorded Presentation Script (Suggested Flow)
When presenting this Tableau Story live or in a recording:
1. **Start with context** — “This dataset contains restaurant data from Zomato, covering multiple cities and cuisines.”  
2. **Explain the Overview dashboard** — highlight dataset size and city distribution.  
3. **Move to Popularity Analysis** — explain how engagement reveals customer behavior patterns.  
4. **Transition to Revenue Analysis** — focus on profitability and cost differences.  
5. **Conclude with Performance Drivers** — summarize what truly drives success and propose data-backed recommendations.  

---

## 🧠 Key Conclusions

### Findings
- Urban hubs like Delhi and Mumbai dominate the restaurant market.  
- Mid-range restaurants consistently outperform in both popularity and satisfaction.  
- Premium pricing doesn’t guarantee high ratings — value perception is critical.  
- Engagement metrics like votes are strong indicators of customer loyalty.

### Recommendations
- Increase visibility of mid-range, high-rated restaurants.  
- Address feedback in low-rated premium venues.  
- Maintain periodic Tableau dashboard reviews to monitor performance trends.  

---

## 🧰 Technologies Used
- **Tableau** – Data visualization and storytelling  
- **Excel / CSV** – Source data formatting  
- **USD Currency Conversion API** – Data standardization for revenue analysis  

---

## 📁 Repository Contents
| File | Description |
|------|--------------|
| `Zomato_Restaurant_Analysis.twbx` | Tableau workbook containing all dashboards |
| `Zomato_Story_Presentation_Full.pdf` | Final presentation report with visuals and narrative |
| `Zomato_Research_Plan.pdf` | Full project research plan |
| `README.md` | Documentation and usage instructions |

---

## 👤 Author
**Jorge Rojas**  
📊 *Aspiring Business Intelligence Analyst*  
TripleTen Bootcamp | Tableau | SQL | Data Visualization  

🔗 [LinkedIn](https://www.linkedin.com/) *(add your link)*  
📧 jcrojas1256@gmail.com  

---

## ⭐ Acknowledgment
Thanks to **TripleTen Bootcamp** for guidance in developing analytical storytelling, and to **Zomato** for making valuable data publicly available for educational purposes.

---


