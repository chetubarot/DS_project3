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

* preprocessing
  * Import software packages (pandas, matplotlib, numpy) into python notebook
  * Import h5py, os, and packages from tensorflow
  * Specify the path to your ZIP file
  * Specify the directory where you want to extract the contents
  * Check the contents of the extracted folder
  * Walk through the directory and print the full paths of the files
  * !pip install h5py
  * Load and process h5 files
  * Preprocess data
  
* modeling
  * Build the CNN model
  * Train and evaluate the model
  * Load dataset metadata
  * Data augmentation
  * Build model, incorporate callbacks, and train batches
  * Evaluate model, generate predictions, and create classification report and confusion matrix
  * Train and evaluate on 32x32x3 images
  * Train and evaluate on 64x64x3 images
  * Train and evaluate on 384x384x3 images

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


