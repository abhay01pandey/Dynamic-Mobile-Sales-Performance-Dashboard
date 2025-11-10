# Dynamic-Mobile-Sales-Performance-Dashboard
This project is a comprehensive Mobile Sales Dashboard designed to monitor, analyze, and benchmark sales performance across different time periods, geographies, and product lines. The primary business objective is to provide sales leadership with actionable insights into revenue growth, product mix, and market performance to inform inventory and marketing strategies.

Key Performance Indicators (KPIs):

Total Sales: 769M

Total Quantity: 19K

Transactions: 4K

Average Price: 40.11K

# Dataset & Tools Used
Dataset:

The dashboard uses detailed, multi-dimensional sales data, including transactional records, geographic market data, mobile product models, brand information (Apple, Samsung, Xiaomi), customer ratings, and payment methods.

Tools:

Power BI: Utilized for data modeling, creation of complex comparative measures (Year-over-Year, MTD), and dynamic visualization.

Power Query: Used for initial data cleaning, transformation, and shaping the data model to support time-series and geographic analysis.

# Workflow
This project required structuring data to support granular analysis and comparison across multiple time scales:

Data Ingestion & Transformation: Raw sales data was imported and cleaned in Power Query, ensuring accurate data types and handling missing values.

Date Table Creation: A dedicated Date Table was built and related to the sales data to enable robust Month-to-Date (MTD) and Year-over-Year (YOY) calculations.

DAX Measure Development: DAX was used to create core KPIs and comparative measures, specifically calculating the sales for the "Same Period Last Year" and comparing it against current performance.

Dashboard Design & Visualization: Multiple pages were designed to focus on different aspects of the business:

Time Series Analysis (YOY): Visuals comparing sales/transactions by Year, Quarter, and Month against the same period last year.

Geographic & Product Analysis: Charts showing sales by City, Brand, Mobile Model, and Payment Method.

MTD Trend: A line graph demonstrating daily sales accumulation for the current month/quarter.

# Dashboard Insights
Analysis across the dashboard pages revealed several critical findings:

Year-over-Year Growth: Sales performance in 2023 and 2024 significantly exceeds that of previous years, indicating strong market traction.

Geographic Hotspots: Sales activity is heavily concentrated in major metro areas, with Delhi, Chennai, and Bangalore being the primary markets.

Brand Performance: Apple leads in total sales (16.16M) and transactions (783), followed closely by OnePlus and Samsung, confirming their dominance in the segment.

Payment & Ratings: Cash and UPI are the preferred payment methods for transactions. The majority of product ratings fall under "Good" status.

Weekly Trend: Sales volume is significantly higher on weekdays (Monday to Friday) and drops sharply over the weekend, suggesting a B2B or weekday-driven consumer base.

# Results
The primary conclusion is that the mobile sales operation is experiencing robust growth, with Total Sales at 769M. The analysis successfully identified Apple, OnePlus, and Samsung as the core revenue drivers and pinpointed key cities where inventory and marketing spend should be maximized. The dashboard enables the sales team to proactively track YOY performance and make timely adjustments based on daily, weekly, and monthly trends.
