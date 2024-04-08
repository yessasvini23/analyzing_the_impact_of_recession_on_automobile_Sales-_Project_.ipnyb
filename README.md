# analyzing_the_impact_of_recession_on_automobile_Sales.ipnyb

#Table of Contents
Introduction
Objectives
Data Description
Technologies Used
Dashboard Link
Visualizations and Insights - Part 1
Visualizations and Insights - Part 2
Conclusion
Acknowledgments
Introduction
This project analyzes the historical trends in automobile sales during various recession periods. By examining various factors such as GDP, Unemployment Rate, Consumer Confidence, and more, we aim to gain insights into how recessions impacted automobile sales.

#Objectives
Create informative and visually appealing plots with Matplotlib, Seaborn, and Dash.
Analyze data to uncover insights on the impact of recessions on automobile sales.
Understand the correlation between different economic indicators and their effect on sales.
Data Description
The dataset contains historical automobile sales data, representing sales and related variables during recession and non-recession periods. The key columns include:

Date: The date of the observation.
Recession: Indicates recession period (1 means it was a recession, 0 means it was normal).
Automobile_Sales: The number of vehicles sold.
GDP: The per capita GDP value in USD.
Unemployment_Rate: The monthly unemployment rate.
Consumer_Confidence: Represents consumer confidence.
Seasonality_Weight: Represents the seasonality effect on automobile sales.
Price: The average vehicle price.
Advertising_Expenditure: The advertising expenditure of the company.
Vehicle_Type: The type of vehicles sold.
Competition: The measure of competition in the market.
Month & Year: Extracted from Date.
Technologies Used
Python
Pandas
Matplotlib
Seaborn
Dash (for interactive visualizations)
Folium (for mapping)
Dashboard Link
Explore the interactive dashboard: Automobile Sales Analysis Dashboard

#Visualizations and Insights - Part 1
Yearly Sales Trend: Analyzed how automobile sales fluctuated yearly.
Sales Trend by Vehicle Type: Observed variations in sales trends between different vehicle types during recession periods.
Sales during Recession vs. Non-Recession: Compare the sales trend per vehicle type for a recession period with a non-recession period.
Effect of GDP on Sales: Examined the variations in GDP during recession and non-recession periods.
Seasonality Impact: Analyzed the effect of seasonality on automobile sales.
Correlation Analysis: Studied the correlation between consumer confidence, average vehicle price, and automobile sales during recession periods.
Advertising Expenditure Analysis: Explored how the advertising expenditure changed during recession and non-recession periods.
Visualizations and Insights - Part 2
Interactive Dashboard with Dash: Developed a comprehensive dashboard for users to select and visualize various aspects of the data dynamically.
Recession vs. Yearly Data Analysis: Users can select between analyzing data for recession periods or yearly sales statistics.
Year Selection for Analysis: Enhanced the dashboard to allow users to select a specific year and gather insights from that year's data.
Detailed Recession Analysis: The dashboard provides visualizations such as line charts, bar graphs, and pie charts, offering insights into the automobile sales trend, average number of vehicles sold by type, expenditure share by vehicle type, and the effect of unemployment during recessions.
Yearly Sales Analysis: Similar to the recession analysis but focuses on data from a selected year, allowing users to see trends and patterns specific to that year.
Conclusion
This project provided valuable insights into the behavior of automobile sales during recession periods. GDP, consumer confidence, and unemployment rates significantly influence sales trends, especially during economic downturns.

#Acknowledgments
Data provided by IBM Developer Skills Network.
Special thanks to Dr. Pooja for guidance during the project.
