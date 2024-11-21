# Project Title

Analyzing Food Image Data using a Convolutional Neural Network (CNN) for 101 Food Categories


## Description

This project aims to classify food images into categories using a Convolutional Neural Network (CNN). Specifically, we will use 101 food categories with transfer learning for our CNN architecture to ensure we predict the correct food category regardless of varying lighting and complex backgrounds. The process involves handling multiple h5 files containing food image data, evaluating the model's performance with different image resolutions, and comparing the impact of image quality on the accuracy of food classification.

## Section 1: Software and platform

### Types of software used for the project

* Packages that should be installed in Python:
  * Numpy
  * Pandas
  * VAR
  * adfuller
  
* Platform: Windows 10, MacOS

## Section 2: A Map of our repository

* Files (Outline)
  * DATA - Folder
    * cleaned_data
    * original_data
    * DataAppendix.pdf
  * OUTPUT - Folder
  * SCRIPTS - Folder
    * modeling.ipynb
    * preprocessing.ipynb
  * LICENSE.md
  * README.md

## Section 3: Instructions for reproducing our results

* preprocessing.ipynb
  * Import software packages (pandas, matplotlib, numpy) into python notebook
  * Define and return all time series data from data folder as data frames
  * Load all time series data from data folder in Google Drive
  * Generate time series data and reword columns based on your name preference
  * Combine data into several possibly useful frames and rename columns
  * Combine CPI and Inflation DataFrames; Merge Real Estate Loan Data; Merge Real Estate Price Data; Merge Mortgage Data
  * Save cleaned data as a csv file in Google Drive
  
* modeling.ipynb
  * Import software packages (pandas, matplotlib, matplotlib.dates, numpy) into python notebook
  * Use combined_2010.csv to analyze economic data from the year 2010 to 2024
  * Plot the change in quantity of real estate loans over time
  * Plot the change in value of the financial metrics (mortgage rate, inflation rate, CPI percent change, real estate price change) over time
  * Plot the change in value of the financial metrics (mortgage rate, inflation rate, and CPI percent change) over time
  * Import VAR and adfuller from statsmodels.tsa.api
  * Check stationarity for each variable
  * Fit VAR model
  * Determine optimal lag order
  * Get the last observed values for forecasting
  * Forecast for 10 years
  * Convert forecast to DataFrame for easier handling
  * Plot respective graphs for mortgage rate, inflation, CPI, RE prices with their 3-year moving averages (2010-2025)
  * Plot the 3yr Averaged Financial Metrics over time
  * Check stationarity for each variable
  * Fit dataframe into VAR model and forecast for 10 years

## Authors

Contributors names:

* Chetu Barot 
* Adarsh Mohanraju
* Travis Montgomery


## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* https://fred.stlouisfed.org/series/CORESTICKM159SFRBATL
* https://fred.stlouisfed.org/searchresults/?st=inflation&isTst=1
* https://fred.stlouisfed.org/series/MORTGAGE30US
* https://fred.stlouisfed.org/series/CREACBW027SBOG
* https://fred.stlouisfed.org/series/COMREPUSQ159N


