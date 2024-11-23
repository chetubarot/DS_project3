# Project Title

Analyzing Food Image Data using a Convolutional Neural Network (CNN) for 101 Food Categories


## Description

This project aims to classify food images into categories using a Convolutional Neural Network (CNN). Specifically, we will use 101 food categories with transfer learning for our CNN architecture to ensure we predict the correct food category regardless of varying lighting and complex backgrounds. The process involves handling multiple h5 files containing food image data, evaluating the model's performance with different image resolutions, and comparing the impact of image quality on the accuracy of food classification.

## Section 1: Software and platform

### Types of software used for the project

* Packages that should be installed in Python:
  * Numpy
  * Pandas
  * Matplotlib
  * Tensorflow
  * h5py
  * Scikit-learn
  
* Platform: Windows 10, MacOS

## Section 2: A Map of our repository

* Files (Outline)
  * DATA - Folder
    * Data Appendix.pdf
    * food.csv
  * OUTPUT - Folder
    * ConfusionMatrix32x32.png
    * ConfusionMatrix64x64.png
    * ConfusionMatrix384x384.png
  * SCRIPTS - Folder
    * preprocessing+modeling.ipynb
  * LICENSE.md
  * README.md

## Section 3: Instructions for reproducing our results

* preprocessing.ipynb
  * Import software packages (pandas, matplotlib, numpy) into python notebook
  * Specify the path to your ZIP file
  * Specify the directory where you want to extract the contents
  * Check the contents of the extracted folder
  * Walk through the directory and print the full paths of the files
  * !pip install h5py
  * Load and process h5 files
  * Preprocess data
  
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
* https://world.openfoodfacts.org/data
* food.csv


