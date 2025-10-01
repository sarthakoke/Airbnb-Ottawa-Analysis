# 🏠 Capital Insights: Unveiling Airbnb Dynamics in Ottawa

## 📌 Overview

This project explores the **Airbnb rental market in Ottawa, Ontario**, highlighting host activity, neighborhood pricing, and room type preferences. Using **Tableau**, I built an interactive dashboard to uncover market trends and provide insights valuable to both **travelers** and **hosts**.

> 📊 [Interactive Tableau Dashboard](https://public.tableau.com/app/profile/sarthak.oke/viz/AirBnBTableauDataAnalysisOttawa/Dashboard1)

---

## 🎯 Business Objective

**Primary Goal**:
Identify how Airbnb supply, demand, and pricing differ across Ottawa neighborhoods to guide **travel decisions**, **host strategies**, and **policy considerations**.

Key questions addressed:

* Which neighborhoods dominate the short-term rental market?
* Who are the most active and busiest hosts?
* What types of rooms do guests prefer?
* How do prices and reviews vary across areas?

---

## 👥 Stakeholders

* **Travelers** → Compare prices, reviews, and room types before booking
* **Hosts** → Benchmark competition and optimize listing strategies
* **Tourism Boards & Policymakers** → Monitor neighborhood rental concentration and impacts

---

## 🗂️ Data Source

* **Provider**: [Inside Airbnb](http://insideairbnb.com/get-the-data.html)
* **Dataset Size**: ~103,000 listings across 40 neighborhoods
* **Key Fields**: `listing_id`, `host_id`, `neighbourhood`, `room_type`, `price_per_night`, `reviews_per_month`, `availability`

---

## 🧹 Data Preparation

Steps performed before visualization:

* Removed incomplete/duplicate entries
* Standardized price and review fields
* Aggregated neighborhood-level insights
* Created calculated measures in Tableau for **availability, average pricing, and review metrics**

---

## 🧠 Key Insights

* **Neighborhood Leader** → *Rideau-Vanier* has the highest number of listings
* **Top Hosts** → *Short And Suite* (47 listings) and *Sonder* (busiest by reviews & activity)
* **Room Preference** → Guests overwhelmingly choose **Entire home/Apartment**
* **Pricing Gaps** → Premium areas show **25–40% higher average nightly rates**
* **Review Trends** → Sharp spike in guest activity post-2022, with 84K+ reviews in 2024 alone

---

## 📊 Visualizations

The Tableau dashboard includes:

* 📍 **Neighborhood distribution** of listings
* 👤 **Top 10 hosts by reviews**
* 💲 **Price comparisons across neighborhoods & room types**
* ⭐ **Review trends by year & room type**
* 🏘️ **Booking breakdown by neighborhood**

🖼️ Dashboard Preview:

![image](https://github.com/user-attachments/assets/96e13796-90ad-4174-9825-d9243d91ed24)


---

## 💡 Recommendations

* **For Hosts**: Focus on *Rideau-Vanier* & *Capital* areas where demand is strongest
* **For Travelers**: Choose *private rooms* for budget stays or compare neighborhoods for savings
* **For Tourism Boards**: Track saturation in high-demand areas like *Rideau-Vanier* to balance city planning and tourism

---

## 🛠️ Tools & Technologies

* **Tableau** → Interactive visualizations
* **Excel / CSV** → Cleaning & preprocessing
* **SQL (optional add-on)** → Aggregations and structured queries

---

## 🚧 Limitations

* Data may not cover 100% of listings (possible sampling bias)
* Relies on host self-reported information → potential inaccuracies
* Doesn’t include **external drivers** like festivals, regulations, or tourism campaigns

---

## 🏁 Conclusion

The Ottawa Airbnb market is highly concentrated in a few neighborhoods, with clear preferences for entire apartments and strong seasonal demand trends. These insights can help **travelers save money**, **hosts maximize profits**, and **policymakers regulate effectively**.

---

## 🔗 References

* [Inside Airbnb](http://insideairbnb.com/get-the-data.html)
* [Tableau Public](https://public.tableau.com/)

---
