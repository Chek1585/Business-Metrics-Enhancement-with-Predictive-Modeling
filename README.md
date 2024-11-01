# Business-Metrics-Enhancement-with-Predictive-Modeling
Final project on improving business metrics (retention, churn, CLV, ARPU) using data analysis and predictive modeling. Included data cleaning, handling missing values via ML, and hypothesis testing. Achieved a 19% ROI increase with filters for top managers and campaigns, supported by Python visualizations.

# Notebook "Contacts_f.ipynb"
The "Contacts_f.ipynb" notebook primarily focuses on data preprocessing and analysis. Here are some key points:

Data Import: Pandas is used for loading and working with the data.
Data Description: Methods like describe() and info() are applied to get an overview of the dataset.
Missing Value Handling: The percentage of missing values in each column is calculated.
Duplicate Removal: Duplicate records are identified and removed based on certain columns.
Data Saving: Data is saved in pickle format for future use and for tracking managers.
Tools Used: Python, pandas.

# Notebook "Calls_f.ipynb"
The "Calls_f.ipynb" notebook focuses on analyzing call data. Here are the key points:

Call Analysis: Call durations, statuses, and types are explored.
Call Statistics: Average and median call durations are calculated.
Call Types: The distribution of call types (outgoing, incoming) is analyzed.
Call Statuses: The number of calls by statuses is considered, which helps understand interaction success.
Data Visualization: Graphs are created for visual representation of call data.
Tools Used: Python, pandas, seaborn, matplotlib.

# Notebook "Deals_f.ipynb"
The "Deals_f.ipynb" notebook is focused on analyzing deals and their closures. Here are the main points:

Data Processing: Data about deals is loaded, cleaned, and processed.
Closing Time Analysis: The average closing time for deals is calculated, and a distribution graph is created.
Deal Filtering: Paid and unpaid deals are identified for more detailed analysis.
Metric Calculation: Various metrics, such as ARPU and CLV, are calculated to assess deal effectiveness.
Visualization: Graphs are created to represent deal data, including revenues and expenses.
Tools Used: Python, pandas, seaborn, matplotlib, scikit-learn.

# Notebook "Spend_f.ipynb"
The "Spend_f.ipynb" notebook focuses on analyzing marketing expenditure data. Here are the main points:

Data Processing: The notebook starts with loading and cleaning data on expenditures.
Missing Value Imputation: Machine learning methods are used to fill in missing values in the data, which improves the quality of analysis.
Expenditure Distribution Analysis: The distribution of marketing expenses across various categories is investigated.
Key Metric Calculation: Various financial metrics, such as total expenditures and average expenses per campaign, are calculated.
Expenditure Comparison: Expenses are compared across different sources and campaigns to identify trends and patterns.
Data Saving: Data is saved in pickle format for further tracking and analysis.
Tools Used: Python, pandas, seaborn, matplotlib, scikit-learn.

# The notebook "campaign_performance.ipynb" focuses on analyzing the performance of marketing campaigns. Here are the key points:

Data Merging: Various datasets related to campaigns are loaded and merged for further analysis.
Metric Aggregation: Key metrics for each campaign are calculated, such as the number of leads, clients, expenses, and revenues.
Rating Determination: A machine learning method is used to determine the rating of campaigns based on their performance.
Financial Metrics: Financial metrics such as Customer Acquisition Cost (CAC), Average Revenue Per User (ARPU), and profit per lead are calculated.
Feature Creation: New features, such as profit per lead and profit per client, are added for a more accurate assessment of economic efficiency.
Data Visualization: Graphs are created to visually represent the effectiveness of various campaigns and their financial results.
Correlation Analysis: A correlation matrix is built to analyze the relationships between key features.
Tools Used: Python, pandas, seaborn, matplotlib, scikit-learn.

# Notebook "product_and_training_type_performance.ipynb"
The notebook "product_and_training_type_performance.ipynb" focuses on analyzing the performance of various products and training types. Here are the key points:

Data Loading: Loads pre-processed deal data that has been saved in pickle format.
Data Filtering: A filter is created for deals in the 'Payment Done' stage to focus on successful deals.
Payment Type Analysis: Analyzes the distribution of payment types to understand which payment methods are most popular among clients.
Successful Deals: Examines which payment types lead to successful deals and which products are the most successful.
Popular Products and Training Types: Investigates popular products and training types to identify their success.
Data Visualization: Creates graphs for a visual representation of information about products and training types.
Financial Metrics: Calculates financial metrics such as the number of clients, revenues, and expenses.
Tools used: Python, pandas, seaborn, matplotlib.

# Notebook "sales_department_performance.ipynb" focuses on analyzing the performance of the sales department. Here are the key points:

Data Analysis: Sales data is loaded and processed, including information about clients, managers, and deals.
Evaluation of Manager Performance: The number of calls and their outcomes are examined, and metrics such as conversion rates and customer retention levels are analyzed.
Determining Manager Ratings: A machine learning method is used to fill in missing data and to determine the ratings of managers based on their performance.
Cohort Analysis: Retention analysis is performed by cohorts to identify trends and issues in the service process.
Identifying Areas for Improvement: Problems with customer retention and opportunities for enhancing manager performance are identified.
Recommendations: Based on the analysis, measures are proposed to improve customer retention and enhance service quality.
Tools Used: Python, pandas, seaborn, matplotlib, scikit-learn.

# Notebook "source_performance.ipynb"
The "source_performance.ipynb" notebook focuses on analyzing the performance of various traffic sources. Here are the key points:

Data Import: Data about sources is loaded using the pickle format for further analysis.
Data Analysis: Various metrics, such as the number of leads, clients, expenses, and revenues for each source, are examined.
Ranking Determination: A machine learning method is used to determine the ranking of sources based on their performance.
Financial Metrics: Key financial metrics, such as Customer Acquisition Cost (CAC) and Average Revenue per User (ARPU), are calculated.
Data Visualization: Graphs are created for a visual representation of the effectiveness of various traffic sources and their impact on key metrics.
Correlation Analysis: An analysis of relationships between key metrics is conducted to understand how different sources influence the business.
Tools Used: Python, pandas, seaborn, matplotlib, scikit-learn.

# 
Here’s the description in English for the notebook "time_series_analysis.ipynb":

Notebook "time_series_analysis.ipynb"
This notebook focuses on time series analysis of company data to evaluate trends in key performance metrics. The main tasks include:

Data Aggregation by Time Periods: Data is grouped by weeks and months to analyze trends across different time frames.

Time Series Analysis: The seasonal_decompose method is used to assess the seasonal, trend, and residual components of the time series. Key metrics such as the number of calls, deals, and advertising expenses are analyzed.

Time Series Visualization: Trend and seasonal charts are created to visually represent changes in key indicators over time.

Correlation Analysis: Relationships between metrics are evaluated to determine possible influences of advertising expenses on the number of calls and deals.

Conclusions and Recommendations: Recommendations are formulated based on the analysis to improve advertising spending strategies and optimize timing to increase calls and deal closures.

# Notebook "geo_language_performance.ipynb"
This notebook focuses on analyzing performance by regions and language groups. Key steps include:

Parsing Language Data: Processes language level data from text format to categorize clients by language proficiency (e.g., A1, B2), enabling systematic grouping and further analysis.

Integrating Regional Data (Lands): Loads data on lands and cities from JSON files for more detailed regional segmentation within the dataset.

Geographical Analysis and Visualization:

Creates geo-maps to analyze client distribution by city and identify profit by region.
Analyzes client density and profitability across regions, helping to pinpoint areas with the highest activity and profitability.
Determining Region and Language Group Ratings: Uses machine learning to calculate ratings for regions and language groups based on their impact on key metrics, such as profitability and client retention.

Tools Used:
Python, pandas, GeoPandas, Matplotlib, Seaborn, JSON, machine learning library (for ranking regions).

# The "unit_economics.ipynb" notebook focuses on calculating key unit economics metrics and creating synthetic data to test hypotheses about the effectiveness of campaigns, resources, and managers.

Main steps:

Data Loading: Preprocessed data saved in pickle format is used, which includes information on deals, advertising expenses, sources, campaigns, and managers.

Synthetic Data Generation:

Synthetic data is first generated using machine learning based on the original data.
Then, synthetic data is generated again but with filters applied, including top campaigns, resources, and managers (based on their ratings), to test the hypothesis about the higher effectiveness of top-performing segments.
Unit Economics Calculations:

CAC (Customer Acquisition Cost): Cost of acquiring a client.
ARPU (Average Revenue per User): Average revenue per client.
CLV (Customer Lifetime Value): Lifetime value of a client, based on the Retention Rate and Churn Rate, calculated for both data groups.
Machine Learning for Synthetic Data Creation: Lasso and RandomForest models are used to forecast metric values, enabling dataset expansion and comparative analysis.

Metrics Analysis and Hypothesis Testing: Comparative analysis of CAC, ARPU, and CLV is performed for both original data and synthetic data with top filters. This helps determine whether using the best resources, managers, and campaigns improves key business metrics.

Visualization of Results: Charts and bar charts are created to display analysis results and metric comparisons across different segments for a clear assessment of the filter impact.

Tools used: Python, pandas, seaborn, matplotlib, scikit-learn.