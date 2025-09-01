🍴 Zomato Data Analysis – Exploratory Data Analysis (EDA)
📌 Project Overview

The Zomato dataset provides restaurant-related information such as cuisines, locations, ratings, and pricing.
This project applies Exploratory Data Analysis (EDA) to uncover:

Which cuisines and locations dominate the food industry.

How price range impacts customer ratings and popularity.

Which factors drive customer preferences across cities.

Correlations between restaurant features and customer ratings.

📊 Dataset Information

Source: Zomato Dataset (Kaggle/Open Source)
Records: ~50K+ restaurant entries
Features:

🏙️ Location → City, Locality

🍽️ Restaurant Info → Name, Cuisine, Cost for Two, Online Order, Table Booking

⭐ Ratings → Aggregate ratings, Votes, Review counts

🔍 Methodology

Data Cleaning & Preprocessing → handled missing values, standardized categorical variables, and removed duplicates.

Univariate Analysis → explored distribution of cuisines, cost for two, and rating categories.

Bivariate Analysis → analyzed relationships between cost, ratings, cuisines, and location-based preferences.

Top-N Analysis → identified most popular cuisines, localities, and restaurants.

Correlation Study → examined associations between features and ratings.

📈 Key Findings

🌍 Popular Locations: Certain localities dominate restaurant density and customer choices.

🍛 Cuisine Trends: North Indian and Chinese are the most common cuisines across cities.

💰 Cost Insights: Higher “Cost for Two” does not always correlate with better ratings.

⭐ Customer Ratings: Majority of restaurants fall in the average rating category, with only a small fraction rated above 4.5.

📦 Online Ordering: Restaurants offering online ordering and table booking options generally attract more customers.

📊 Visual Gallery

The notebook generates:

Cuisine-wise restaurant distribution plots.

Location-based restaurant availability heatmaps.

Rating vs Cost distribution scatterplots.

Correlation heatmap of numeric features.

Top cuisines & top localities charts.

🛠️ Tech Stack

Python → Pandas, NumPy

Visualization → Matplotlib, Seaborn

Environment → Jupyter Notebook

⚙️ Installation & Usage

Clone the repository:

git clone https://github.com/G-Monesh-Reddy/EDA_ANALYSIS_ZOMATO.git
cd EDA_ANALYSIS_ZOMATO
