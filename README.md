# Covid19-Analysis
COVID-19 Interactive Analysis Shiny App
The COVID-19 Interactive Analysis Shiny App is a dynamic web application that enables users to visualize and analyze COVID-19 data through interactive charts, tables, and maps. Users can filter data by date range and country, view real-time trends, and explore statistics such as cases, deaths, and vaccinations, all in an intuitive and user-friendly interface.

# Data Source
The data used in this app is sourced from [Our World in Data](https://ourworldindata.org/coronavirus-source-data).

# features
Maps: Interactive visualizations of COVID-19 data across regions.
Trends: Time-series analysis of cases, deaths, and vaccinations over time.
Summary: Display of key metrics like total cases, deaths, and recoveries.
Details: Raw data tables with filtering, sorting, and search capabilities.
Comparison: Side-by-side comparison of COVID-19 data across countries or region.

# Requrirements
The COVID-19 Analysis Shiny App requires R version 4.0.0+ .
packages like Shiny, dplyr, ggplot2, plotly, leaflet, and DT for interactive features, data manipulation, and visualization.
For deployment, use RStudio and platforms like shinyapps.io or Shiny Server.

# Installation
Install R: Download and install R from CRAN.
Install Required Packages:
install.packages(c("shiny", "dplyr", "ggplot2", "plotly", "leaflet", "DT", "lubridate", "shinythemes", "tidyr", "httr", "forecast"))
Run the App:shiny::runApp("path_to_your_app_directory")






