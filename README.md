# nyc-taxi-dataset
🚖 NYC Taxi Trip Analysis
City Transportation Trends - Data Analysis & Visualization

This project explores taxi trip data from New York City, analyzing key patterns in passenger movement, fare trends, and geographical trip distributions. Using public trip records provided by the NYC Taxi & Limousine Commission, we derive insights that support urban planning, transportation optimization, and demand forecasting.

📌 Features of the Project
✅ Data Cleaning & Preprocessing
Handling missing and null values

Converting string formats to datetime or float

Removing duplicates and unrealistic entries (e.g., zero-distance trips)

Filtering for consistent data (e.g., valid coordinates)

🔍 Exploratory Data Analysis (EDA)
Analyzing trip frequency over time (hourly, daily, monthly)

Studying passenger count distribution

Exploring relationships between fare amount, distance, and time

📊 Visualizations using Matplotlib & Seaborn
Line plots showing daily and monthly trends

Histograms for fare and tip distribution

Bar charts of payment types

Geospatial visualizations of pickup and drop-off density using heatmaps

📈 Insights from Trip Data
Identifying peak hours for taxi demand

Most common pickup/drop-off locations (e.g., airports, midtown)

Tip behavior by payment type and ride duration

Fare distribution across boroughs

📂 Dataset
Source: NYC TLC Trip Record Data

Taxi Types: Yellow Taxi, Green Taxi, FHV (Uber/Lyft)

Data Available: 2009 to present (monthly CSV files)

Columns Include:

tpep_pickup_datetime, tpep_dropoff_datetime

trip_distance, passenger_count

fare_amount, tip_amount, total_amount

pickup_longitude, pickup_latitude

dropoff_longitude, dropoff_latitude

payment_type

📊 Technologies Used
Python

Pandas, NumPy – Data handling and transformation

Matplotlib, Seaborn – Visualizations

Folium, Geopandas – Geospatial plotting

Google Colab / Jupyter Notebook – Notebook-based analysis

📝 How to Use
Open the .ipynb file using Google Colab or Jupyter Notebook

Follow these steps in the notebook:

Load a sample CSV or monthly dataset

Clean the dataset (null values, datatype conversion, filtering)

Run visualizations to explore trends

Customize the notebook to:

Analyze different months/years

Focus on specific locations (e.g., JFK trips)

Build prediction models (optional)

📈 Key Insights
Rush hours (8–10 AM and 4–7 PM) show the highest trip volumes

Tips are significantly higher with credit card payments

Short-distance trips dominate in Manhattan; long trips often involve airports

Trip durations increase during bad weather and holidays
