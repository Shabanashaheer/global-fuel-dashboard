# global-fuel-dashboard
Global Fuel Analysis Dashboard

 Purpose & Description
An interactive analytical dashboard designed to visualize and analyze global fuel consumption trends, pricing fluctuations, and distribution metrics. The project aims to provide actionable insights into energy utilization patterns and economic impacts across different regions.

  Tech Stack
Business Intelligence & Visualization: Power BI 
Data Transformation & Modeling: Power Query (M Language), DAX
Storage & Version Control: GitHub, Git

  Data Source & Structure
Source:Tabular fuel datasets (CSV/Excel format covering regional fuel stats, pricing, and consumption over time).
  Structure:
  Fact Tables: Historical transactional data including fuel prices, consumption volumes, and timestamps.
    Dimension Tables: Categorized reference data mapping regions/countries, fuel types (e.g., Petrol, Diesel, EV), and time periods.
    Relationships: Structured star-schema model connecting fact tables to date and geographic dimensions for optimized slicing and querying.
