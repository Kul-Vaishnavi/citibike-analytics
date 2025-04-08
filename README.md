# 🚴 CitiBike Data Analytics & Machine Learning

This project explores user behavior, station utilization, and real-time operations in New York City’s CitiBike program using trip data from 2013–2024. It combines exploratory data analysis (EDA), real-time analytics, machine learning, and optimization techniques.

## 📦 Project Structure

- **Trip Data Analysis**: Time-series trends, station usage, trip durations
- **Real-Time Analytics**: Bike availability and station status visualization
- **Machine Learning**: Predicting demand using historical trends (Random Forest/XGBoost)
- **Optimization**: Solving the Traveling Salesman Problem for bike rebalancing

## 🛠 Tools Used
- Python, Pandas, NumPy, Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook
- JSON APIs for live station data

## 🧠 Tasks Completed

### ✔️ Task 0 – Python Functions
Basic analytics functions: trip counts, durations, weekly trends, and top stations.

### ✔️ Task 1 – CitiBike Trip Data Analysis
- Total/avg trips by year, day, hour
- Most popular stations and trip routes
- Usage heatmaps and trip-duration vs distance analysis

### ✔️ Task 2 – Real-Time Data Analysis
- Fetched station data from GBFS API
- Mapped live availability and utilization by area

### ✔️ Task 3 – Trip Prediction
- Forecasted bike demand using ML models
- Compared performance with/without COVID-era data

### ✔️ Task 4 – Optimization (TSP)
- Selected 20 stations and solved the shortest route using latitude/longitude data

## 📊 Data Sources
- Historical trip data: [CitiBike NYC](https://citibikenyc.com/system-data)
- Live station feeds: [GBFS JSON](https://gbfs.citibikenyc.com/gbfs/2.3/gbfs.json)

---

This project was developed as part of **IE 555 – Programming for Analytics** at the University at Buffalo.
