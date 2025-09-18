
#  Car Sales Performance Analysis  

## Project Overview  
This project analyzes car sales data to uncover insights about **revenue, profit, customer behavior, and car model performance**.  
We apply **feature engineering, exploratory data analysis (EDA), and time series analysis** to understand key drivers of sales performance.  

The analysis answers questions such as:  
- Which car makes and models generate the most profit and revenue?  
- How do **seasons, weekdays, and regions** impact sales performance?  
- Does **discounting affect profitability**?  
- What role do **luxury vs non-luxury cars** play in revenue contribution?  
- How do **customer demographics** (age, gender) influence buying behavior?  

---

## 📂 Dataset Features  
The dataset contains the following columns:  



### ➕ Engineered Features  
- `Age Group` → Customer segmentation by age  
- `Profit Margin %` → Profitability ratio  
- `Discount Level` → Categorized discount impact  
- `Is Luxury` → Flag for luxury vs. non-luxury cars  
- `Is Weekend` → Weekend vs weekday sales flag  
- `YearMonth` → For monthly trend analysis  

---

##  Methods & Techniques  

### 🔹 Data Cleaning & Preprocessing  
- Handled missing values and formatting issues  
- Outlier detection (IQR method)  
- Feature encoding & scaling (for ML readiness)  

### 🔹 Exploratory Data Analysis (EDA)  
- **Univariate & Bivariate analysis**  
- Correlation heatmaps  
- Seasonality & time series analysis  
- Luxury vs non-luxury comparison  
- Regional & demographic performance  

### 🔹 Feature Engineering  
- Created business-driven features for **profit margin, luxury flag, time-based grouping**.  

---

##  Key Insights  

### Revenue & Profit Trends  
- 📉 Overall revenue showed **downward trends** with slight recoveries in **Feb 2020 & 2023–24**.  
- 💰 Profit margins were **strongly correlated with sale price** (>0.7).  

### Customer Behavior  
- 👨 Most buyers were **male customers**, slightly ahead of females.  
- 🎯 Age group **40–50 years** dominated sales, especially in luxury cars.  

### Product Performance  
- 🚘 **S-Class dominated revenue & profit**, followed by C-Class, GLC, and E-Class.  
- 🏆 **Toyota, BMW, and Audi** were strong performers overall.  
- 📉 Newer models (2020–23) showed a **downfall in revenue** compared to 2018–19.  

### Discounts & Profitability  
- Higher discounts → Lower profit margins.  
- Customers responded to discounts, but **volume gains didn’t fully offset profit loss**.  

### Regional & Seasonal Insights  
- 🌎 Regions like **Pennsylvania** performed consistently.  
- 🌸 Seasons had **similar profit distributions**, with spring slightly leading.  
- 📅 Weekdays (esp. Monday) generated **higher revenue than weekends**.  

---

## ✅ Suggested Business Actions  
1. **Boost Luxury Marketing** → Focus on high-performing models (S-Class, GLC, E-Class).  
2. **Balanced Portfolio** → Push mid-range Toyota & BMW models to reduce reliance on luxury.  
3. **Discount Strategy** → Use discounts **strategically**, not aggressively, to protect margins.  
4. **Customer Segmentation** → Target **40–50 year-olds** with premium financing & loyalty offers.  
5. **Seasonal Campaigns** → Run strong **spring campaigns** to maximize natural demand.  
6. **Regional Expansion** → Replicate successful strategies from **Pennsylvania** into weaker regions.  

---

## 📈 Visualizations  

Here are some of the plots used in the analysis (replace with your actual charts):  

- **Monthly Revenue & Profit Trends**  
  ![Monthly Revenue](images/monthly_revenue.png)  
  ![Monthly Profit](images/monthly_profit.png)  

- **Revenue by Car Model**  
  ![Top Models](images/top_models.png)  

- **Profit Margin by Car Make**  
  ![Profit Margin](images/profit_margin.png)  

- **Customer Age vs Sale Price (Hexbin)**  
  ![Age vs Sale Price](images/age_vs_sale_price.png)  

- **Luxury vs Non-Luxury Comparison**  
  ![Luxury vs Non-Luxury](images/luxury_nonluxury.png)  

---

## 🚀 Next Steps  
- Apply **predictive modeling (ML)** to forecast sales & revenue.  
- Explore **clustering customers** to create targeted marketing campaigns.  
- Build an **interactive dashboard** for real-time car sales monitoring.  

---

## 🛠️ Tech Stack  
- **Python** (Pandas, NumPy, Seaborn, Matplotlib)  
- **Feature Engineering**  
- **EDA & Visualization**  
- Jupyter Notebook for analysis  

---

✨ *This project highlights how car sales data can be leveraged for business strategy, customer insights, and revenue optimization.*  
