# Guest Satisfaction Analysis of Airbnb Listings in Italy

## 📊 Project Overview

This project analyzes Airbnb listings across Italy to identify the key factors influencing guest satisfaction, pricing behavior, host performance, property characteristics, and value for money.

The analysis was completed using **Microsoft Excel** for data cleaning and **Microsoft Power BI** for data analysis, visualization, and business intelligence.

The project was designed around five key business questions and transformed raw Airbnb listing data into actionable insights for travelers and accommodation decision-makers.

---

## 🎯 Business Questions

The analysis sought to answer:

1. Which aspects of the guest experience have the strongest relationship with overall guest satisfaction?
2. How does price influence guest satisfaction and value for money?
3. How do host characteristics influence guest satisfaction?
4. Which property types and property sizes have the greatest influence on guest satisfaction?
5. Which cities and neighborhoods offer the best value for money?

---

## 🛠️ Tools & Technologies

* **Microsoft Excel** — Data cleaning and preparation
* **Microsoft Power BI** — Data analysis and visualization
* **DAX** — Measures and calculated columns
* **Kaggle** — Data source

---

## 📂 Dataset

The project used an **Italy Airbnb Listings Dataset**, originally sourced from Kaggle.

The dataset contained information including:

* Listing ID
* City
* Neighborhood
* Property Type
* Bedrooms
* Beds
* Bathrooms
* Maximum Guests
* Price
* Host information
* Super Host status
* Rating Score
* Accuracy Score
* Cleanliness Score
* Check-in Score
* Communication Score
* Location Score
* Value for Money Score
* Reviews

---

## 🧹 Data Preparation

The dataset was cleaned in Microsoft Excel before being imported into Power BI.

The preparation process included:

* Removing duplicate records
* Standardizing data formats
* Creating a **Price Flag** to identify unusually high prices
* Identifying listings with an overall rating of 0.00
* Creating calculated fields required for analysis

A total of **650 records** contained unusually high prices and were excluded from price-based calculations. These records were flagged rather than corrected because their intended values could not be reliably verified.

Additionally, **23 listings** contained an overall rating of 0.00 and were treated cautiously during rating analysis due to insufficient documentation about what those values represented.

---

## 📈 Power BI Analysis

Several DAX measures and calculated columns were created to support the analysis.

### Key calculations included:

* Average Rating
* Average Price
* Median Price
* Total Listings
* Average Price of Highly Rated Listings
* Host Rating
* Super Host Rating
* Host Years
* Super Host Years
* Property Size
* Price Band
* Years of Experience
* Price Flag

### Visualizations

The Power BI dashboard incorporated:

* KPI Cards
* Key Influencer Visual
* Scatter Charts
* Clustered Column Charts
* Pie Charts
* Donut Charts
* Bar Charts
* Maps

Each visualization was designed to address one or more of the project's business questions.

---

## 🔍 Key Findings

### 1. Value for Money is the strongest driver of satisfaction

The Power BI Key Influencer analysis identified **Value for Money** as the strongest predictor of overall guest ratings.

When the average Value for Money score increased by **0.41**, the average Rating Score increased by approximately **0.11**.

Cleanliness ranked second, followed by Accuracy.

---

### 2. Price has only a weak relationship with guest satisfaction

The analysis found only a weak positive relationship between price and guest ratings.

| Metric                                 |  Result |
| -------------------------------------- | ------: |
| Average Listing Price                  | €173.16 |
| Average Price of Highly Rated Listings | €178.50 |
| Difference                             |   €5.34 |

This suggests that travelers do not necessarily need to spend substantially more to find highly rated accommodation.

---

### 3. Super Hosts received higher ratings

Super Hosts achieved an average rating of **4.86**, compared with **4.64** for regular hosts.

Interestingly, their average hosting experience was almost identical:

| Host Category | Average Rating | Experience |
| ------------- | -------------: | ---------: |
| Super Host    |           4.86 |  7.2 years |
| Regular Host  |           4.64 |  7.0 years |

This suggests that Super Host status may be a stronger indicator of guest satisfaction than hosting experience alone.

---

### 4. Property size had little influence

Average ratings were almost identical across property-size categories:

| Property Size | Average Rating |
| ------------- | -------------: |
| Small         |           4.72 |
| Medium        |           4.72 |
| Large         |           4.72 |
| Very Large    |           4.75 |

This indicates that property size had limited influence on guest satisfaction within the analyzed dataset.

---

### 5. Property type had a modest influence

| Property Type | Average Rating |
| ------------- | -------------: |
| Entire Home   |           4.73 |
| Private Room  |           4.70 |
| Hotel Room    |           4.66 |
| Shared Room   |           4.55 |

Although entire homes recorded the highest average rating, the differences were relatively small.

---

### 6. Napoli and Firenze offered the best value for money

Average Value for Money scores by city were:

| City    | Value for Money |
| ------- | --------------: |
| Napoli  |           4.667 |
| Firenze |           4.661 |
| Roma    |           4.657 |
| Venezia |           4.626 |
| Milano  |           4.583 |

**Napoli** recorded the highest average Value for Money score, followed by **Firenze**.

---

## 💡 Recommendations

Based on the analysis:

* Travelers should prioritize listings with high **Value for Money, Cleanliness, and Accuracy** scores.
* Booking decisions should not be based on price alone.
* Highly rated budget and mid-range listings should be considered when searching for accommodation.
* Travelers should consider **Super Hosts**, who recorded higher average ratings.
* Property size and accommodation type should be selected based on travel needs, group size, and budget rather than assuming larger properties provide better experiences.
* Travelers seeking strong value for money should consider **Napoli and Firenze**, while also comparing neighborhood-level ratings.

---

## 📊 Dashboard Preview

The interactive Power BI dashboard brings together the project's KPIs, guest satisfaction analysis, pricing analysis, host analysis, property analysis, and city-level value-for-money analysis.

> **Dashboard screenshot:** Add the screenshot of the completed Power BI dashboard here.

---

## 📁 Project Files

### Power BI Dashboard

[Airbnb Guest Satisfaction Dashboard](../Airbnb_Guest_Satisfaction_Dashboard.pbix)

### Documentation

* [Technical Report](Documentation/Technical_Report.pdf)


---

## ⚠️ Limitations

* 650 listings contained unusually high prices that could not be verified and were therefore excluded from price-based calculations.
* 23 listings contained an overall rating of 0.00 without sufficient documentation explaining whether they were unrated or genuinely rated zero.
* The dataset represents a historical period and may not reflect current Airbnb market conditions.
* The analysis was limited to the variables available within the dataset.

---

## 🚀 Future Analysis

Future analysis could explore:

* Seasonal booking patterns
* Occupancy rates
* Cancellation behavior
* Revenue analysis

---

## 👤 Project Type

**Data Analytics / Business Intelligence Project**

**Tools:** Microsoft Excel | Microsoft Power BI | DAX

**Sector:** Tourism & Hospitality
