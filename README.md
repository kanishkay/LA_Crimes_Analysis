# 🕵️ LA Crimes Analysis (2012–2016)

📊 **An Exploratory Data Analysis (EDA) project** that investigates Los Angeles crime data from 2012 to 2016. This project analyzes and visualizes patterns related to crime categories, temporal trends, geographic hotspots, and more.

**Dataset Source**: [Los Angeles Crime Data, 2012 to 2016 (Kaggle)](https://www.kaggle.com/datasets/kingburrito666/los-angeles-crime)

---

## 📁 Project Structure

* `LA_Crimes_EDA.ipynb`: Main notebook with data cleaning, feature engineering, visual analysis, and insights.
* `LA_Crimes_2012_to_2016.csv`: Raw dataset containing crime reports from 2012 to 2016.
* `requirements.txt`: Dependencies used for data exploration and visualization.

---

## 📝 Data Overview

The dataset consists of **1,136,589 crime reports** with 14 features:
- **Key Features**:
  - `Area Name`: The jurisdiction of the crime (e.g., Olympic, Hollywood).
  - `Crime Description`: The nature of the crime (e.g., Theft, Vandalism).
  - `Date Occured` and `Time Occured`: The timestamp of the crime.
  - `Location`: Includes latitude and longitude.
- **Data Cleaning**:
  - Missing values in `Crime Description` were filled with the most frequent value.
  - Columns were renamed for readability.
  - `Date Occured` and `Time Occured` were converted into structured datetime features.
  - New features such as `Year`, `Month`, `Day`, `Day of Week`, and `Hour` were created.

---

## 📈 Key Insights

### Exploratory Findings:
1. **Geographic Hotspots**: Identified top crime-prone areas using bar plots.
2. **Temporal Analysis**:
   - Most crimes occurred in **December** and during the evening hours (8 PM - 10 PM).
   - Highest crime density on weekends, particularly on **Friday** and **Saturday** nights.
3. **Crime Categorization**:
   - Created general crime categories like Violent Crimes, Property Crimes, Traffic Offenses, etc.
   - **Property Crimes** were the most common, with Theft being a significant contributor.
4. **Heatmap Analysis**:
   - Temporal hotspots visualized by hour and day of the week, revealing peak times for criminal activities.
5. **Trends Over the Years**:
   - Yearly crime trends showed a gradual decline in overall crime after 2014.
   - Crime categories like Violent Crimes and Public Disturbances followed distinct seasonal patterns.

### Visual Highlights:
- Bar charts to compare top 10 crime-prone areas.
- Line charts showing monthly and yearly crime trends.
- Heatmaps revealing crime concentrations by hour and day.
- Distribution of crime categories with boxplots to show their timing variations.

---

## 🔬 Advanced Analysis

- **Custom Crime Categorization**:
  Used keywords in crime descriptions to classify crimes into high-level categories like `Violent Crimes`, `Property Crimes`, and `Traffic Offenses`.
  
- **Top 3 Areas by Crime Category**:
  Identified top jurisdictions for each category, enabling localized insights for law enforcement.

- **Temporal Crime Trends**:
  - Year-over-year comparisons of crime rates by category.
  - Monthly trend lines highlighted seasonal variations in criminal activity.

---

## 🛠️ Tools Used

* **Python**:
  - `pandas` for data manipulation.
  - `seaborn` and `matplotlib` for data visualization.
* **Jupyter Notebook**: For interactive coding and data analysis.
* **Git & GitHub**: For version control and project management.

---

## 🗂️ Key Findings Summary

1. **Hotspots**:
   - The area with the highest crime: **77th Street**.
2. **Timing**:
   - **Peak crime month**: December.
   - **Peak crime hour**: 8 PM.
3. **Categories**:
   - **Most common crime category**: Property Crimes (e.g., theft, vandalism).

---

📫 **Contact**: [www.linkedin.com/in/kanishkayadvv](https://www.linkedin.com/in/kanishkayadvv)

**Author**: Kanishka Yadav
