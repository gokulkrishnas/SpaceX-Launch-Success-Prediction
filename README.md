# 🚀 SpaceX Launch Success Prediction

Predicting the success of Falcon 9 launches using exploratory data analysis, SQL, machine learning, and interactive dashboards.

## 📌 Project Overview

This end-to-end data science project explores the SpaceX Falcon 9 launch dataset to identify factors contributing to successful missions. It involves data collection from APIs and web scraping, thorough wrangling and analysis, SQL querying, interactive dashboards using Dash and Plotly, and a classification model to predict launch outcomes.

## 🧰 Tech Stack

- Python, Pandas, NumPy
- BeautifulSoup, Requests (Web Scraping)
- SQLite (SQL Queries)
- Plotly Dash (Interactive Dashboard)
- Scikit-learn (ML Model)
- Folium (Geospatial Visualization)
- Jupyter Notebook

## 📁 Notebooks & Key Components

| File | Description |
|------|-------------|
| `jupyter-labs-spacex-data-collection-api-v2.ipynb` | Data collection via SpaceX API |
| `jupyter-labs-webscraping.ipynb` | Web scraping launch data using BeautifulSoup |
| `labs-jupyter-spacex-Data wrangling-v2.ipynb` | Data cleaning, wrangling, and transformation |
| `jupyter-labs-eda-dataviz-v2.ipynb` | Exploratory Data Analysis and visualization |
| `jupyter-labs-eda-sql-coursera_sqllite.ipynb` | SQL-based EDA on launch records |
| `lab-jupyter-launch-site-location-v2.ipynb` | Folium map visualizing launch sites |
| `SpaceX-Machine-Learning-Prediction-Part-5-v1.ipynb` | Predictive modeling using Logistic Regression |
| `spacex_dash_app.py` | Interactive dashboard for site-wise launch analysis |
| `spacex_launch_dash.csv` / `spacex_launch_geo.csv` | Cleaned data for dashboard and geo visualizations |

## 📊 Dash Application Highlights

The Plotly Dash app (`spacex_dash_app.py`) includes:
- 📍 Dropdown to filter by Launch Site
- 🥧 Pie Chart showing success distribution
- 📏 Payload slider for range selection
- 🔍 Scatter plot for success vs. payload correlation

> Run locally:  
> `python spacex_dash_app.py` → Navigate to `http://127.0.0.1:8050/`

## 🤖 Machine Learning Model

A Logistic Regression model is trained on launch features to predict binary success outcomes (`Success` / `Failure`), based on payload, site, and booster information.

## 🌍 Geospatial Insights

Using **Folium**, launch site locations are visualized on an interactive map with clickable launch details.

## 🧠 Key Learnings

- API integration and web scraping for real-world data collection
- SQL queries for structured data exploration
- Dashboarding and visual storytelling using Plotly Dash
- Applying classification models on real datasets
- Geospatial mapping for deeper context

---

**Made with 💻 by Gokulkrishna S**

