# Customer Shopping Behavior Analysis

## Project Overview
This project presents an in-depth analysis of customer shopping behavior to understand purchasing patterns, consumer preferences, and demographics. By analyzing transactional data, this project identifies key trends that drive sales, evaluates product performance, and explores customer segmentation to aid data-driven business decisions and targeted marketing strategies.

## Project Purpose
The primary objectives of this project are:
* **Identify Customer Demographics:** Analyze age, gender, and regional patterns affecting purchasing decisions.
* **Analyze Purchase Behavior:** Evaluate spending habits, product category preferences, and seasonal buying trends.
* **Optimize Customer Retention:** Assess subscription status, discount usage, and frequency of purchases.
* **Enhance Marketing Strategies:** Provide actionable data insights to improve promotional strategies, customer loyalty programs, and inventory management.

## Dataset
The project utilizes the **Customer Shopping Trends Dataset**, which contains transaction details across various customer segments. Key columns in the dataset include:
* **Customer Info:** `Customer ID`, `Age`, `Gender`, `Location`
* **Purchase Details:** `Item Purchased`, `Category`, `Purchase Amount (USD)`, `Season`, `Size`, `Color`
* **Behavioral Data:** `Payment Method`, `Frequency of Purchases`, `Discount Applied`, `Promo Code Used`, `Previous Purchases`, `Review Rating`, `Subscription Status`, `Shipping Type`

## Data Cleaning & Validation
To ensure data integrity and quality prior to analysis, the following steps were performed:
1. **Missing Value Handling:** Checked for null values across all features and imputed or dropped incomplete records where necessary.
2. **Data Type Standardization:** Converted categorical variables into appropriate types and numerical values into correct formats for quantitative analysis.
3. **Duplicate Removal:** Identified and removed duplicate transaction entries to prevent skewing the statistical models.
4. **Outlier Detection:** Used boxplots and z-scores to detect and address extreme purchase amounts that could distort overall insights.
5. **Consistency Checks:** Validated string formatting (e.g., standardizing text case and trimming spaces for categorical features like `Category` and `Payment Method`).

## Exploratory Data Analysis
Exploratory Data Analysis (EDA) was performed to discover underlying patterns using univariate, bivariate, and multivariate analysis:
* **Demographic Breakdown:** Visualized customer age distribution and gender representation across different product categories.
* **Category & Revenue Analysis:** Mapped top-performing categories (e.g., Clothing, Accessories, Footwear, Outerwear) against total revenue generated.
* **Promotional Impact:** Analyzed the correlation between discount/promo code usage and overall transaction value.
* **Payment & Shipping Preferences:** Evaluated the popularity of payment options (e.g., Credit Card, PayPal, Cash) and preferred shipping choices.
* **Customer Loyalty:** Grouped customers by subscription status and previous purchase history to measure lifetime value metrics.

## Key Insights
* **High-Value Categories:** Clothing and Accessories generate the highest proportion of total sales volume and revenue.
* **Discount vs. Regular Buyers:** Customers using promo codes tend to buy frequently, but non-discount transactions account for a substantial portion of high-value individual cart sizes.
* **Subscription Drive:** Subscribed customers display higher purchase frequency and give consistently higher review ratings compared to non-subscribers.
* **Seasonal Demand:** Specific product categories experience significant spikes in sales during peak seasons (e.g., Fall/Winter collections).

## Tools & Libraries
The following tools and libraries were used to build and execute this analysis:
* **Programming Language:** Python 3.x
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Environment:** Jupyter Notebook / VS Code

## Conclusion
The analysis highlights clear links between customer demographics, payment preferences, and overall purchasing behavior. Leveraging customer loyalty programs and optimizing inventory around seasonal demand can significantly boost revenue and retention. Tailoring promotional campaigns to specific high-performing demographics will ensure higher marketing efficiency and ROI.

## Future Improvements
Future iterations of this project can incorporate:
* **Predictive Modeling:** Build Machine Learning models (e.g., Random Forest, XGBoost) to predict future customer spending and churn rates.
* **Customer Segmentation:** Apply Clustering algorithms (K-Means) to group customers into distinct personas based on RFM (Recency, Frequency, Monetary) metrics.
* **Interactive Dashboard:** Develop a dynamic dashboard using **Power BI**, **Tableau**, or **Streamlit** for real-time data monitoring and reporting.

---

**Author:** Malik Muhammad Aqil  
**Program:** BS Artificial Intelligence  
**Institution:** University of Management and Technology, Lahore