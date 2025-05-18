# 🏠 Predicting Housing Prices with Machine Learning

**Author:** Lenise Muso Nkwain  
**Project Type:** Capstone Project  
**Goal:** Build a machine learning model that accurately predicts home prices using geographic, socioeconomic, and housing data.

---

## 📌 Project Overview

The project addresses challenges in real estate pricing by creating a digital home appraisal tool. Traditional appraisals are costly, time-consuming, and subject to human error. Using data and machine learning, this project offers a smarter, faster way to estimate home values.

---

## 💡 Problem Statement

Prospective buyers, sellers, and real estate agents struggle with:

- High cost of appraisals (~$625 per home on average in New York)
- Inaccurate or outdated pricing from tools like Zillow or Trulia
- Limited access to market and geographic data insights

---

## 🎯 Objectives

- Predict house prices using machine learning models.
- Analyze the impact of variables such as income, population, location, and proximity to amenities.
- Offer a more accessible and cost-effective alternative to traditional home appraisals.

---

## 📊 Dataset

**Source:** California Housing Dataset from the U.S. Census  
**Format:** CSV (`housing 2.csv`)

### Key Variables

| Variable          | Description                               |
|-------------------|-------------------------------------------|
| `longitude`       | Longitude of the property                 |
| `latitude`        | Latitude of the property                  |
| `housing_median_age` | Age of the property                     |
| `total_rooms`     | Total number of rooms                     |
| `population`      | Population in the district                |
| `median_income`   | Median income of residents                |
| `median_house_value` | House price (target variable)          |
| `ocean_proximity` | Proximity to ocean (categorical)          |

---

## 🔍 Methodology

1. **Data Preprocessing**
   - Handle missing values
   - Normalize/encode features
   - Feature engineering

2. **Exploratory Data Analysis**
   - Correlation matrix
   - Geospatial visualizations

3. **Modeling**
   - Regression models (Linear, Random Forest, etc.)
   - Cross-validation and performance tuning

4. **Evaluation**
   - Metrics: RMSE, MAE, R²
   - Visual comparison of predicted vs actual prices

---

## 📈 Results & Insights

- Median income shows strong correlation with housing prices.
- Proximity to coastal regions had a moderate effect.
- Machine learning models outperformed manual estimation and public listing tools.

---

## ⚠️ Limitations

- Real-time changes (e.g., new amenities or disasters) are hard to account for.
- Gentrification trends and climatic effects need dynamic data feeds.
- Geographical data limited to California for now.

---

## 🔮 Future Work

- Incorporate computer vision on satellite images for location quality.
- Include weather and zoning data.
- Compare predictions to actual market appraisals.
- Expand to nationwide housing datasets.

---

## 📂 Files in This Repository

- `housing 2.csv`: Cleaned housing data
- `Homework_3_Eulojio.ipynb`: Jupyter notebook with data analysis & modeling
- `Capstone project 1 - Copy-2.pdf`: Full project report
- `Capstone 1 Slides.pdf`: Presentation slides

---

## 📜 License

This project is released under the [MIT License](LICENSE) — free to use and modify with attribution.

---

## 🤝 Acknowledgments

Special thanks to the U.S. Census for the open dataset and all collaborators on the capstone project.


