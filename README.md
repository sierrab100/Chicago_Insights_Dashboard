# Chicago Insights Dashboard - Python/Tableau

## Project Overview
Built on publicly available data, the Chicago Insights Dashboard proposed in this project intends to provide Chicago residents with insights into safety, schools, and housing value regarding their neighborhoods. While government open-data projects provide residents with raw data, and dashboards to hold their local government accountable, this data has rarely been readily available for practical use such as home shopping and determining community metrics.

Several previous projects have explored the creation of a community insights dashboard to provide average citizens with actionable insights. For example, in her thesis, Dowling develops a web-based GIS application to help residents of Anchorage, Alaska find neighborhoods that best fit their preferences based on crime rates, weather, real estate and other factors [5]. Sunkpho & Wipulanusat explored the potential value of using a Business Intelligence (BI) style dashboard, to present publicly available geospatial data [6]. While Ruiming Xu examined the effects that COVID-19 had on NYC neighborhoods [7]. These three dashboards are a few examples of previous projects utilizing publicly available data to deliver insights to average citizens. However, despite the large quantity of data available, the city of Chicago lacks a similar style dashboard.

The Chicago Community Insights Dashboard attempts to resolve this issue by creating a relational database that allows for deep, unrestricted analysis of the advantages and disadvantages of Chicago neighborhoods across multiple dimensions. The creation of the dashboard was initiated with the collection of multiple datasets covering housing, crime, and education in the Chicago metropolitan area. These datasets were transformed into a relational database that could be queried to provide insights. The queries provided by the relational database were then utilized to design and develop an elegant, user-friendly dashboard that empowers citizens to make informed decisions and learn about their neighborhoods. Included in the dashboard is a community score which is designed to evaluate neighborhood quality based on metrics from a combination of factors.

This project evaluates the quality of neighborhoods in Chicago by combining:
- **Crime Rates**
- **Education Metrics**
- **Housing Data**

The result is a **Neighborhood Quality Index (NQI)** that ranks each neighborhood from 1 (highest quality) to N (lowest).

