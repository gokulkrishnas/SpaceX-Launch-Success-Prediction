# 🚀 SpaceX Launch Success Prediction

Predicting the success of Falcon 9 launches using API data, web scraping, SQL, machine learning, and interactive dashboards.

## 📌 Project Overview

This project analyzes and models the success of SpaceX Falcon 9 rocket launches. Through end-to-end data science practices—from data collection and wrangling to visualization and predictive modeling—it provides insights into the factors that drive successful missions.

🔗 **[📖 View Project Presentation (PDF)](./SpaceX-Presentation-GokulkrishnaS.pdf)**

## 🧰 Tech Stack

- Python, Pandas, NumPy
- BeautifulSoup, Requests (Web Scraping)
- SQLite (SQL Queries)
- Plotly Dash (Interactive Dashboard)
- Scikit-learn (ML Models)
- Folium (Geospatial Visualization)
- Jupyter Notebooks

## 📁 Project Files

| File | Description |
|------|-------------|
| `jupyter-labs-spacex-data-collection-api-v2.ipynb` | Collect launch data from SpaceX REST API |
| `jupyter-labs-webscraping.ipynb` | Scrape launch table data from Wikipedia |
| `labs-jupyter-spacex-Data wrangling-v2.ipynb` | Clean, transform and export structured data |
| `jupyter-labs-eda-dataviz-v2.ipynb` | Explore data using visualizations |
| `jupyter-labs-eda-sql-coursera_sqllite.ipynb` | SQL-based analysis of launch data |
| `lab-jupyter-launch-site-location-v2.ipynb` | Visualize launch locations with Folium |
| `SpaceX-Machine-Learning-Prediction-Part-5-v1.ipynb` | Build and evaluate ML models |
| `spacex_dash_app.py` | Interactive dashboard app using Plotly Dash |
| `spacex_launch_dash.csv`, `spacex_launch_geo.csv` | Final cleaned datasets |

## 📊 Dashboard Features

The interactive dashboard (`spacex_dash_app.py`) allows users to:
- 🎯 Select launch sites from a dropdown
- 🥧 View pie charts of launch outcomes
- 📦 Adjust payload range via slider
- 📈 Visualize payload vs. success correlations

▶ **To Run the Dashboard Locally**:
```bash
python spacex_dash_app.py
```
Then open `http://127.0.0.1:8050/` in your browser.

## 🧠 Predictive Modeling

Using scikit-learn, classification models (Logistic Regression, SVM, Random Forest, etc.) were trained to predict mission outcomes based on:
- Launch site
- Payload
- Booster version category

📌 **Best performing model:** Random Forest Classifier with highest accuracy

## 🌍 Geospatial Analysis

Mapped launch site coordinates and analyzed distances to coastlines, railways, highways, and nearby cities using:
- Haversine formula
- Folium marker clusters and color-coded outcomes

## 📊 SQL-Based EDA

Insights include:
- Mission outcome stats
- Top-performing boosters
- Payload trends by booster and orbit
- First successful landings by date

## 🎥 Presentation Slides

🖥️ **Complete walkthrough of the project and results available in the presentation PDF.**  
It includes:
- Executive Summary
- Methodologies
- EDA results
- SQL queries
- Interactive Dash screenshots
- ML performance
- Final conclusions

👉 **[📖 Click here to view it](./SpaceX-Presentation-GokulkrishnaS.pdf)**

---

**Made with 💡 by Gokulkrishna S**
