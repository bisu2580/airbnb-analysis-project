# 🏡 Airbnb Amsterdam Data Analysis

This project presents a comprehensive analysis of Airbnb listings in Amsterdam using both **Python (Jupyter Notebook)** for EDA and **Power BI** for interactive dashboards. The objective is to extract meaningful insights to assist hosts, travelers, and stakeholders in understanding market dynamics.

---

## 📂 Project Structure

```
├── data/
│   └── listings.csv (sample dataset)
├── images/
│   └──(dashboard screenshots, plots)
├── notebooks/
│   └── EDA_Airbnb.ipynb
├── powerbi/
│   └── airbnb.pbix
├── README.md
```

---

## 🧪 Exploratory Data Analysis (EDA)

Using Python libraries like Pandas, Matplotlib, and Seaborn, we explored various dimensions of the data:

### 🔍 Key EDA Insights:

1. **Data Cleaning:**

   * Null values in `reviews_per_month`, `last_review`, and `host_name` columns handled appropriately.
   * Converted `last_review` to datetime for trend analysis.

2. **Room Type Distribution:**

   * `Entire home/apt`: \~75% of listings.
   * `Private room`: \~25%.
   * `Shared room`: <1%.

3. **Price Distribution:**

   * Most listings fall within ₹100 - ₹200 range.
   * Outliers identified above ₹10,000 per night.

4. **Review Trends:**

   * February sees the **highest volume of reviews**, indicating seasonal demand.

5. **Top Hosts:**

   * Silvina Soledad leads with the most listings.
   * Other active hosts include David, Mike, Anna, and Laura.

---

## 📊 Power BI Dashboard Insights

The project also includes a dynamic Power BI dashboard with key metrics and interactive visualizations.

### ✅ Overview Dashboard:

* **Total Listings:** 5,166

* **Total Reviews:** 371K

* **Average Price:** ₹260.20

* **Room Type Distribution:**

  * Entire home/apt: 3.84K
  * Private room: 1.28K
  * Shared room: 0.01K

* **Listings by Neighbourhood Group:**

  * Most listings are concentrated in:

    * De Baarsjes
    * Centrum-West
    * De Pijp – Rivierenbuurt

* **Top 5 Hosts by Listings:**

  * Silvina Soledad (48)
  * David (32)
  * Mike (26)
  * Anna (25)
  * Laura (25)

---

### 💰 Price Analysis:

* **Price Distribution by Listings:**

  * Majority fall in ₹101–₹200 and ₹201–₹300 buckets.
* **Average Price by Room Type:**

  * Hotel room: ₹845.12
  * Entire home/apt: ₹293.14
  * Private room: ₹148.66
  * Shared room: ₹76.29
* **Price vs. Number of Reviews:**

  * Listings with moderate prices (\~₹100–₹300) get more reviews.
  * Very expensive listings (>₹10,000) receive fewer reviews.

---

### 🧑‍💼 Host & Occupancy Insights:

* **Average Estimated Occupancy:** 65.27

* **Top Occupancy Month:** March

* **Top Hosts by Occupancy:**

  * Danielle (25,000)
  * Christiaan (9,100)
  * Joost (8,200)

* **Monthly Trends in Reviews:**

  * February and March have significant review spikes — peak booking seasons.

---

## 📌 Key Takeaways

* February and March are peak demand months, critical for pricing strategies.
* Entire home/apartments dominate the market and attract the most bookings.
* Moderate pricing leads to higher engagement (more reviews).
* A small group of hosts manages a large number of listings — power sellers.
* Location plays a crucial role, with specific neighborhoods consistently outperforming others.

---

## 🚀 Tools & Technologies

* Python (Pandas, Matplotlib, Seaborn)
* Power BI
* Git & GitHub
* Jupyter Notebook
* Excel/CSV Data Source

---

## 📸 Screenshots

You can find full dashboard screenshots inside the `assets/images/` folder for reference.

---

## 📥 How to Use

1. Clone the repo:

```bash
git clone https://github.com/your-username/airbnb-amsterdam-analysis.git
```

2. Run the Jupyter Notebook inside `/notebooks/` to explore EDA.

3. Open `airbnb.pbix` with Power BI Desktop to explore the dashboards interactively.

---

## 📧 Contact

For queries, suggestions, or collaborations:
**Biswajit Sahoo**
📬 Email: [biswajitsahoo1424@gmail.com](mailto:biswajitsahoo1424@gmail.com)
📍 Location: India