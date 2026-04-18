# 🍽️ Zomato Restaurant Data Analysis

> Exploratory data analysis on a global restaurant dataset to identify what drives ratings, 
> customer engagement, and delivery trends across 140+ cities worldwide.

---

## 📌 Project Overview

This project analyzes **9,551 restaurant records** from Zomato across multiple countries to answer:
- What factors most influence a restaurant's aggregate rating?
- How do online delivery and table booking affect customer perception?
- Which cuisines and cities dominate the food service landscape?
- How does pricing correlate with customer satisfaction?

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python (Pandas, Seaborn, Matplotlib) | Data cleaning, EDA, statistical analysis |
| Tableau | Interactive dashboard and visual storytelling |
| Excel | Supplementary analysis and pivot exploration |
| Jupyter Notebook | Development environment |

---

## 📂 Dataset

- **Source:** Zomato public dataset
- **Records:** 9,551 restaurants
- **Features:** 19 columns including location, cuisines, cost, rating, votes, delivery options
- **Geographic scope:** 140+ cities across multiple countries

---

## 🔍 Key Findings

### 📍 Geographic Distribution
- **New Delhi** dominates with **5,473 restaurants** — over 4× the next city (Gurgaon: 1,118)
- The dataset spans 141 cities across multiple continents
- Philippine cities (Inner City, Quezon City, Makati) rank highest by average rating

### 🌮 Cuisine Insights
- **North Indian** is the most listed cuisine (3,960 restaurants), followed by Chinese (2,735) and Fast Food (1,986)
- Niche cuisines like **Sunda, Taiwanese, and Ramen** achieve the highest average ratings (4.5–4.9)
- Restaurants serve between **1 to 8 cuisines**, with specialization correlating to higher quality perception

### ⭐ Rating Drivers
| Factor | Insight |
|--------|---------|
| Online Delivery | Restaurants offering delivery rate **~0.78 points higher** on average (3.25 vs 2.47) |
| Table Booking | Table booking restaurants average **3.44** vs 2.56 for those without |
| Price Range | Higher cost brackets consistently earn higher ratings — premium positioning matters |
| City | Ratings vary significantly by geography — customer expectations differ by market |

### 💰 Cost Distribution
- Most restaurants (2,701) fall in the ₹200–400 range for two
- Only 258 restaurants exceed ₹2,000 — but this bracket averages the **highest ratings (3.69)**

### 🏪 Franchise Presence
- **Barbeque Nation** has the widest franchise footprint at 22 cities
- Pizza Hut (12), KFC (8), Domino's (7) follow

---

## 📊 Tableau Dashboard

The **Star Restaurant Dashboard** includes:
- Ratings vs Votes scatter plot (color-coded by rating tier)
- Heatmap of restaurants by city and price range
- Top cuisines by average aggregate rating
- Online delivery & table booking vs rating comparison

---

## 🧹 Data Cleaning Steps

- Identified and dropped **1 row** with missing Restaurant Name
- Dropped **9 rows** with missing Cuisine values
- Verified no duplicate Restaurant IDs
- Created derived features: `Cuisine Count`, `Cost Range` bins

---

## 💡 Business Recommendations

1. **Invest in online delivery infrastructure** — delivery-enabled restaurants consistently outperform on ratings
2. **Premium positioning pays off** — restaurants in the ₹1,000+ bracket earn significantly higher ratings despite lower volume
3. **Niche cuisine specialization** is associated with higher ratings vs broad multi-cuisine menus
4. **New Delhi market is saturated** — expansion opportunity lies in Tier 2 cities with far fewer competitors


## 👩‍💻 Author

**Shradha R Pai** — Data Analyst  
[LinkedIn](https://www.linkedin.com/in/shradha-pai/) • [GitHub](https://github.com/ShradhaPai)
