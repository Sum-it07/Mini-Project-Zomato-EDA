# 🍽️ Zomato Restaurant Data Analysis

This project explores and analyzes restaurant data from [Zomato](https://www.zomato.com/) to uncover insights about ratings, cost, delivery options, cuisines, and location-based trends. The data spans multiple countries and includes key restaurant metrics.

---

## 📁 Dataset

- **Main File:** `zomato.csv`
- **Supporting File:** `Country-Code.xlsx`

---

## 📊 Key Objectives

1. ✅ Merge Zomato data with country codes
2. ✅ Identify top-rated restaurants in Indian cities
3. ✅ Analyze relationship between **aggregate rating** and **votes**
4. ✅ Count number of restaurants in each country
5. ✅ List top 5 restaurants offering **online delivery**
6. ✅ Find **cheap but highly rated** restaurants in each city
7. ✅ Identify most popular cuisines by region
8. ✅ Compute average ratings for each city per country
9. ✅ Explore if **rating influences cost** (boxplot)
10. ✅ Show **top cities by restaurant count** (pie chart)
11. ✅ Highlight top cuisines in Indian restaurants (pie chart)

---

## 📈 Techniques Used

- **Data Wrangling**: `pandas`, `merge`, `groupby`, filtering
- **Visualization**: `matplotlib`, `seaborn`
- **Outlier Handling**: IQR method and log-scaled axes
- **Correlation Analysis**: Pearson correlation and regression plots

---

## 📷 Sample Visualizations

- **Boxplot**: Rating vs. Average Cost for Two
- **Pie Chart**: Top Cities by Restaurant Count
- **Scatter/Regression Plot**: Votes vs. Rating

---

## 💡 Insights

- No strong correlation between **rating** and **cost** (confirmed visually & statistically)
- Cities like **New Delhi, Bangalore, and Mumbai** dominate restaurant counts
- **North Indian, Chinese**, and **Fast Food** are top cuisines in India
- Many highly-rated restaurants also offer **online delivery**

