🍽️ Restaurant Recommendation System (Las Vegas) — Yelp Dataset + K-Means Clustering

This project is a location-based Restaurant Recommendation System built using the Yelp Academic Dataset.
It identifies restaurant clusters in Las Vegas (NV) using K-Means clustering, visualizes them on interactive maps, and recommends the best nearby restaurants based on user latitude and longitude.

⭐ Project Highlights
✔ 1. Data Preprocessing & Filtering

Loaded the Yelp Academic JSON dataset

Filtered restaurant-related businesses using category extraction

Cleaned missing values and removed invalid records

Focused analysis on Las Vegas, Nevada

✔ 2. Exploratory Data Analysis

Star rating distributions

Most reviewed restaurants

Visualization using Countplots & Barplots

Identified top-performing restaurants

✔ 3. Geospatial Mapping (Plotly Mapbox)

Plotted thousands of restaurants on interactive maps

Used colors to represent star ratings

Used marker size to represent review count

Created a heatmap-like visualization of restaurant density

✔ 4. K-Means Clustering

Clustering based on restaurant latitude & longitude

Used Elbow Method to determine optimal clusters

Calculated Silhouette Score for performance validation

Clustered Las Vegas into 5 meaningful geographic zones

✔ 5. Recommendation Engine

Developed a function that:

Predicts the user's cluster from their coordinates

Returns top 5 restaurants from that cluster

Filters based on review count and ratings

Helps users find popular restaurants near their location

🛠️ Tech Stack

Python

Pandas, NumPy

Scikit-Learn (KMeans, Silhouette Score)

Matplotlib, Seaborn

Plotly & Mapbox

Google Colab

Yelp Academic Dataset

This project demonstrates data cleaning, clustering, geospatial analysis, and ML-based recommendations using real-world data.
