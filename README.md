# 🎟️ Showz: Marketing Expense Optimization in Ticket Sales

## 📝 Context
**Showz** is a company dedicated to selling tickets for events and is looking to optimize its marketing expenses to maximize profitability. Through this project, the records of platform visits, orders placed, and marketing expenses from January 2017 to December 2018 are analyzed. The goal is to understand how users interact with the platform, when they become buyers, how much they contribute to the company, and when the revenue covers the customer acquisition cost.

The analysis focuses on answering key questions about customer acquisition and retention and recommending how to allocate marketing budgets more effectively.

## 🛠️ Tools Used
- **Python**: Data analysis and statistical modeling.
- **Pandas**: Data cleaning, transformation, and analysis.
- **Matplotlib** and **Seaborn**: Visualization of patterns and trends in visits, purchases, and marketing expenses.
- **SciPy**: Significance analysis and hypothesis testing.
- **Jupyter Notebook**: Interactive and detailed documentation of the analysis.

## 📈 Results Analysis
The project was structured in several phases:

1. **Data Preprocessing**:
   - Loading and cleaning the data from visits, orders, and marketing expenses from the provided files.
   - Verifying the data types of each column and ensuring each data point is in the correct format for analysis.
   - Generating key metrics such as session duration and the number of sessions per user.

2. **Descriptive Analysis**:
   - **Visits**:
     - Analyzing the number of daily, weekly, and monthly users.
     - Calculating the average session duration.
     - Determining the frequency with which users return to the website.
   - **Sales**:
     - Determining the time elapsed between user registration and their first purchase.
     - Calculating the average purchase size and the total value contributed by each customer (LTV).
   - **Marketing**:
     - Analyzing marketing expenses by source and over time.
     - Calculating the customer acquisition cost (CAC) by acquisition source.
     - Analyzing the return on marketing investment (ROMI).

3. **Data Visualization**:
   - Line and bar charts to show trends in visits and sales by month.
   - Charts comparing ROMI and CAC by acquisition source.
   - Visualizing the distribution of session duration and the time between consecutive visits.

4. **Conclusions**:
   - **ROMI**: Acquisition sources with a ROMI greater than 1 (such as sources 1, 2, and 5) are the most profitable and should be prioritized in marketing investments.
   - **Platforms**: Although most users use the "Desktop" platform, marketing investments should be diversified to boost the "Touch" platform, which is more cost-effective and provides a higher return per customer.
   - **Acquisition Sources**: Acquisition sources 3, 4, and 5 have high customer acquisition costs and generate a low ROMI. It is recommended to optimize investments in sources 1 and 2, which are more profitable and have lower acquisition costs.
   - **Users and Sales**: Peaks in users and sales from August 2017 to January 2018 indicate an opportunity to concentrate marketing efforts during those periods.
   - **Customer Satisfaction**: Most users return in less than 10 days, reflecting high customer satisfaction and the potential to encourage recommendations and loyalty.

## 📋 Recommendations
- **Acquisition Sources**: Prioritize sources with high ROMI (1, 2, and 5) and optimize sources with high acquisition costs (3, 4, and 5).
- **Platforms**: Diversify marketing to increase participation in the "Touch" platform, which offers a better return on investment.
- **Marketing Expenses**: Increase investment during months with higher peaks in users and sales, adjusting the strategy based on seasonal demand.

This analysis provides key insights for Showz to optimize its marketing budget allocation, improve ROI, and maximize customer retention and satisfaction.
