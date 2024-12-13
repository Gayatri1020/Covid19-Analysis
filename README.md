# COVID-19 Interactive Analysis Shiny App

The **COVID-19 Interactive Analysis Shiny App** is a dynamic web application that enables users to visualize and analyze COVID-19 data through interactive charts, tables, and maps. Users can filter data by date range and country, view real-time trends, and explore statistics such as cases, deaths, and vaccinations, all in an intuitive and user-friendly interface.

## Data Source
The data used in this app is sourced from [Our World in Data](https://ourworldindata.org/covid-cases).

## Features
- **Maps**: Interactive visualizations of COVID-19 data across regions.
- **Trends**: Time-series analysis of cases, deaths, and vaccinations over time.
- **Summary**: Display of key metrics like total cases, deaths, and recoveries.
- **Details**: Raw data tables with filtering, sorting, and search capabilities.
- **Comparison**: Side-by-side comparison of COVID-19 data across countries or regions.

## Requirements
The **COVID-19 Interactive Analysis Shiny App** requires:
- **R version 4.0.0+**
- R packages:
  - `shiny` - `dplyr` - `ggplot2`- `plotly` - `leaflet`  - `DT`  - `lubridate` - `shinythemes` - `tidyr` - `httr`  - `forecast`

For deployment, use **RStudio** and platforms like **shinyapps.io** or **Shiny Server**.

## Installation
1. **Install R**: Download and install R from [CRAN](https://cran.r-project.org/).
2. **Install Required Packages**: Run the following command in R:
   ```r
   install.packages(c("shiny", "dplyr", "ggplot2", "plotly", "leaflet", "DT", "lubridate", "shinythemes", "tidyr", "httr", "forecast"))
