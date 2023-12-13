# Weather Analysis Project

## Overview
This R Markdown project is designed for conducting a comprehensive weather analysis related to sales data. The script encompasses various data processing steps, including sales and weather data manipulation, trend analysis, and correlations between weather conditions and sales performance.

## Features
- **Sales Data Processing**: Functions to clean and prepare sales data for analysis.
- **Weather Data Integration**: Tools for loading and processing weather data, and aligning it with sales data.
- **Analytical Functions**: Custom functions for systemwide sales analysis and weather trend analysis.
- **Modular Design**: Each major step is encapsulated in a function for better organization and reusability.
- **Data Exporting**: Capabilities to output processed data and analysis results.

## Prerequisites
The following R packages should be installed for the script to function correctly:
- `tidyr`
- `dplyr`
- `reshape2`
- `lubridate`
- `geosphere`
- `zipcode`
- `RCurl`
- `RJSONIO`
- `corrplot`

## Usage
To use the script, follow these steps:
1. **Set Up File Paths**: Replace the placeholder paths in the `run_analysis` function call with the paths to your actual data files.
2. **Run Analysis**: Execute the `run_analysis` function to process the data and perform the analysis.
3. **Review Results**: Check the output files for insights and data visualizations.

## Example
```r
run_analysis("path/to/Flash Sales by Order Date.csv", 
             "path/to/store list.csv", 
             "path/to/weather_2018.csv", 
             "path/to/weather_2019.csv", 
             "path/to/weather_station.csv")
```

## Contributing
Contributions to enhance the script's functionality or to extend its capabilities are welcome. Please ensure to follow coding standards and add appropriate documentation for new features.

## Authors
- Lisa Li - Initial work

## License
This project is licensed under the MIT License.

## Acknowledgments
Special thanks to all contributors and collaborators who have provided data, insights, and expertise to the project.
