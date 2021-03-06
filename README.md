# Coursera---Getting-and-Cleaning-Data---Course-Project

This repository hosts the R code and documentation files for the Data Science's track course "Getting and Cleaning data", available in Coursera.

The dataset being used is: [**Human Activity Recognition Using Smartphones**](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

1. The R script, **run_analysis.R**, which can be launched in RStudio by just importing the file does the following:

   a. Download the dataset if it does not already exist in the working directory

   b. Load the activity and feature info

   c. Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation

   d. Loads the activity and subject data for each dataset, and merges those columns with the dataset

   e. Merges the two datasets

   f. Converts the activity and subject columns into factors

   g. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

   h. The end result is shown in the file **averages_tidy.txt**.
   
2. **CodeBook.md** describes the variables, the data, and any transformations or work that was performed to clean up the data for            preparing the tidy dataset.
