# Global Economic Growth and Development Infographic Report

## Overview

This project involves the analysis of the World Bank's annual economic report, which provides data on every country's economy and development statistics. The objective is to produce an infographic-style report that highlights major trends in global economic growth and development.

## Objectives

1. **Quality Assurance (QA) and Data Profiling**: 
   - Conduct QA on World Bank data and profile it for consistency and accuracy.
   - Join additional UN data to enhance the analysis.

2. **Data Preparation and Reformatting**: 
   - Prepare and reformat the data for visualization purposes.

3. **Data Visualization**: 
   - Create visualizations that depict key trends and relationships in the data.

4. **Report Compilation**: 
   - Combine the visualizations into a single report-style graphic.

## Data Processing Steps

- **Import Data**: Load the World Bank Excel file.
- **Population Calculation**: 
  - Use "GDP" and "GDP per Capita" to calculate the population in millions and create a "Population (M)" column.
- **Data Filtering and Joining**: 
  - Filter the data to the year 2014 and join it with the IDI CSV file on "Country Code".
- **Pivot Tables**: 
  - Create a "gdp_pivot" table with years as rows, regions as columns, and the sum of GDP as values.
  - Create a "pop pivot" table with years as rows, regions as columns, and the sum of population as values.
- **HDI Calculation**: 
  - Create a "wb_hdi_by_region" table by calculating the average IDI for each region and sort from highest average IDI to lowest.

## Visualizations Created

1. **Stacked Area Chart**: 
   - Growth of GDP over time, with each stack representing a geographic region.
   
2. **Stacked Area Chart**: 
   - Growth of population over time, with each stack representing a geographic region.
   
3. **Bubble Chart**: 
   - Life expectancy on the x-axis, GDP per capita on the y-axis (log scale), and population represented as bubble size. Bubbles colored by region.

4. **Bar Chart**: 
   - Average HDI by region, with region colors matching previous visualizations.

5. **Scatter Plot**: 
   - Power consumption on the x-axis and GDP per capita on the y-axis, using HDI as a color scale for the dots (excluding outliers like Iceland).

## Final Report

All visualizations have been compiled into a single page report with an overall title and descriptive text to provide context for the reader.

## Access the Project

You can access the project and all relevant code in the following Google Colab link: [Global Economic Growth and Development Infographic Report](https://colab.research.google.com/drive/1qTWaw-yyC82oZLQUnIpIVBxqVuMwWSrK?usp=sharing)

