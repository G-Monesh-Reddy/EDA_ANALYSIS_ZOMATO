# 🍴 Zomato Restaurants – Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-orange)
![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-green)
![Seaborn](https://img.shields.io/badge/Visualization-Seaborn-purple)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-lightgrey)

---

## 📌 Project Overview

The **Zomato Restaurants Dataset** (Bangalore) contains **42K+ restaurant records**.
This project applies **Exploratory Data Analysis (EDA)** to uncover:

* Which **restaurant types and locations** dominate the market
* How **pricing trends** affect affordability
* Adoption of **table booking and online ordering** services
* Geographic **distribution of food hubs** in Bangalore

---

## 📊 Dataset Information

* **Source**: Zomato Restaurant Listings (Bangalore)
* **Records**: \~42,700
* **Features**:

  * 🧑 Restaurant Info → `Name`, `Type`, `Location`, `Rating`
  * 📦 Services → `Table_Booking`, `Online_Order`
  * 💰 Pricing → `Approx_Cost(for two people)`

---

## 🔍 Methodology

1. Data Cleaning → handled missing values, standardized categories
2. Univariate Analysis → restaurant type counts, cost distribution
3. Bivariate Analysis → table booking & ordering behavior
4. Location Analysis → high-density food hubs
5. Distribution Study → affordability and adoption trends

---

## 📈 Key Findings

### 🍽️ Restaurant Types

* **Quick Bites (14K)** and **Casual Dining (12K)** dominate
* Together ≈ **61% of listings (\~26K of 42.7K)**

### 🪑 Table Booking Availability

* Split nearly half: **Yes \~49% (20.9K)** vs. **No \~51% (21.8K)**
* Suggests balanced adoption of reservations

### 📦 Online Ordering

* **13.6K restaurants (\~32%)** enable online ordering
* Shows strong but not universal adoption

### 📍 Top Locations

* High-density hubs: **Lavelle Road, Church Street, Koramangala (3rd Block), Rajarajeshwari Nagar, Sankey Road, BTM, Whitefield, Yeshwantpur**
* Counts **600–800 per location**, clusters reaching \~4,000

### 💰 Cost for Two Distribution

* Prices range up to **₹6,000**, but majority **< ₹2,000**
* Peak affordability density ≈ **₹1,000–₹1,500**

### 🧭 Additional Observations

* Location plots show varying **scales of raw vs. aggregated counts**
* **Overlapping labels** → recommend horizontal or grouped bar charts

---

## 📊 Visual Gallery

The notebook generates:

* **Bar plots** for restaurant types, booking, and ordering
* **Location distribution charts**
* **Histograms & density plots** for pricing
* **Aggregated views** of top localities

---

## 🛠️ Tech Stack
- **Python** → Pandas, NumPy  
- **Visualization** → Matplotlib, Seaborn  
- **Environment** → Jupyter Notebook 

---

---

## ⚙️ Installation & Usage

Clone the repository:
```bash
git clone https://github.com/G-Monesh-Reddy/EDA_ANALYSIS_ZOMATO.git
---

## 📂 Repository Structure
