
# ☕ Coffee Shop Sales Analysis (EDA Project)

## 📌 Project Overview

This project performs an **Exploratory Data Analysis (EDA)** on a Coffee Shop sales dataset to uncover business insights such as:

* Revenue trends
* Top-performing product categories
* Peak sales hours
* Store location performance
* Seasonal patterns

The objective of this project is to transform raw transactional data into meaningful business insights using Python and data visualization.

---

## 📊 Dataset Information

The dataset contains transaction-level sales data with the following columns:

* `transaction_id`
* `transaction_date`
* `transaction_time`
* `store_id`
* `store_location`
* `product_id`
* `transaction_qty`
* `unit_price`
* `Total_Bill`
* `product_category`
* `product_type`
* `product_detail`
* `Size`
* `Month Name`
* `Day Name`
* `Hour`
* `Month`
* `Day of Week`
* `month`

---

## 🛠 Tools & Technologies Used

* **Python**
* **Pandas** – Data manipulation & aggregation
* **NumPy**
* **Matplotlib**
* **Seaborn** – Data visualization
* Jupyter Notebook

---

## 🔎 Key Business Questions Answered

### 1️⃣ Which product category generates the highest revenue?

* Aggregated total revenue using `groupby()`
* Identified top-performing product categories

---

### 2️⃣ What are the monthly revenue trends?

* Analyzed sales trends across months
* Detected seasonal patterns

---

### 3️⃣ Which store location performs best?

* Compared total revenue by store
* Identified high-performing locations

---

### 4️⃣ What are peak business hours?

* Analyzed sales by hour
* Identified busiest time slots
* Useful for staff scheduling & operations planning

---

### 5️⃣ Revenue Analysis by Day and Hour (Heatmap)

* Created pivot tables
* Visualized revenue patterns using heatmaps
* Identified high-traffic sales periods

---

## 📈 Key Insights

* Certain product categories consistently drive the majority of revenue.
* Sales show clear peak hours during the day.
* Some store locations significantly outperform others.
* Seasonal monthly patterns indicate potential promotional timing.

---

## 📊 Visualizations Included

* Bar plots (Revenue by Category & Location)
* Line plots (Monthly & Hourly Trends)
* Stacked revenue comparisons
* Heatmaps (Day vs Hour Analysis) 
---

## 🚀 How to Run the Project

1. Clone the repository
2. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook
```

4. Run all cells inside `Coffee_Sales_EDA.ipynb`

---

## 📌 Learning Outcomes

Through this project, I strengthened my skills in:

* Data cleaning and preprocessing
* GroupBy operations and aggregation
* Time-based feature extraction
* Business-focused visualization
* Writing analytical insights from raw data

