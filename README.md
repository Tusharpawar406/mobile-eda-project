# mobile-eda-project
# Mobile Dataset EDA 

This project explores a mobile dataset using **Pandas, Matplotlib, and Seaborn**.  
The goal is to perform **Exploratory Data Analysis (EDA)** and find insights about mobile features and pricing.

---

##  Dataset
- Columns: `battery`, `camera`, `display`, `memory`, `name`, `price`, `processor`, `rating`, `reviews`, `warranty`
- Target of interest: **price**

---

##  Steps Performed
1. Data Cleaning  
   - Checked missing values  
   - Removed duplicates  
   - Handled outliers (removed mobiles priced above 75,000)  

2. Exploratory Data Analysis  
   - Summary statistics (mean, median, etc.)  
   - Distribution of numeric features (battery, price, rating)  
   - Correlation heatmap  
   - Boxplots for price vs other features  

3. Visualizations  
   - Histograms  
   - Scatterplots  
   - Boxplots for outliers  

---

##  Insights
- Mobiles with higher RAM and processor rating tend to have higher prices.  
- Most mobile prices cluster below ₹30,000, with outliers at the flagship range.  
- Battery capacity and display size have weaker correlation with price compared to RAM/processor.  

---

##  Tools Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

##  Next Steps
- Try feature engineering for predictive modeling (Linear Regression, Random Forest).  
- Build a simple price prediction model.


