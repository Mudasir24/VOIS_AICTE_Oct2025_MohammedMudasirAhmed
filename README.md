# 🏨 Airbnb Hotel Booking Analysis

This project explores and analyzes Airbnb listing data to gain insights into pricing, neighborhood trends, availability, and other key metrics.  
It focuses on identifying patterns that can help improve decision-making for hosts and guests alike.

---

## 📊 Project Overview

The **Airbnb Hotel Booking Analysis** aims to:
- Understand how prices vary across different neighborhood groups.
- Examine host activity and room availability.
- Identify popular areas and potential factors influencing pricing.

The analysis was performed using Python (Pandas, NumPy, Matplotlib, and Seaborn) in a Jupyter Notebook environment.

---

## 🧹 Data Cleaning

Several data preprocessing steps were performed:
1. Removed duplicates using `df.drop_duplicates()`.
2. Dropped unnecessary columns like `house_rules` and `license`.
3. Cleaned the `price` column (removed symbols and converted to numeric).
4. Handled missing values appropriately.
5. Ensured correct data types for analysis.

---

## 📈 Analysis Performed

The following analyses and visualizations were conducted:

1. **Average Price by Neighborhood Group**  
   - Compared average prices among Bronx, Brooklyn, Manhattan, Queens, and Staten Island.  
   - Used a bar chart to represent average pricing distribution.


2. **Room Type Distribution**  
   - Analyzed proportions of room types (Entire home/apt, Private room, etc.).  
   - Visualized using a pie chart.


3. **Top Hosts by Number of Listings**  
   - Identified hosts with the most properties listed.  
   - Displayed using a horizontal bar chart.


4. **Availability Analysis**  
   - Examined how many days listings are available per year.  
   - Showed availability trends across neighborhoods.


---

## 🧠 Key Insights

- **Manhattan and Brooklyn** tend to have the highest average prices.
- **Private rooms** are the most common type of listing.
- Some hosts own a significant number of listings, indicating professional property management.
- Availability varies by area — some neighborhoods have listings available year-round, while others are booked most of the time.

---

## 🧰 Tools & Libraries Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 🧾 Conclusion

This analysis offers valuable insights into Airbnb’s pricing patterns, neighborhood behavior, and host activity.  
Future work could include:
- Predicting prices using machine learning models.
- Studying the correlation between reviews and booking rates.
- Building an interactive dashboard using Streamlit or Power BI.

---

## 👨‍💻 Author

**Mohammed Mudasir Ahmed**  
🎓 Muffakham Jah College of Engineering and Technology  

---

## 🏷️ License

This project is open-source and available under the [MIT License](LICENSE).

