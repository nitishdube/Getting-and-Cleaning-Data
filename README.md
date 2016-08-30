# Getting-and-Cleaning-Data

This is the course project for the Getting and Cleaning Data Coursera course.
The R script, `run_analysis.R`, does the following:

1. Download the dataset if it does not already exist in the working directory.
2. Load the activity and feature info.
3. Loads both the training and test datasets, keeping only those columns which
   reflect a mean or standard deviation.
4. Loads the activity and subject data for each dataset, and merges those
   columns with the dataset.
5. Merges the two datasets.
6. Converts the `activity` and `subject` columns into factors.
7. Creates a tidy dataset that consists of the average (mean) value of each
   variable for each subject and activity pair.

The end result is stored in the file `tidy.txt`.

## Dependencies
* run_analysis.R file will help you to install the dependencies automatically. It depends on reshape

## Steps to Run the script:
* Download the data source and put into a folder in your working directory. You'll have a UCI HAR Dataset folder.
* Run source("run_analysis.R"), then it will generate a new file tiny_data.txt in your working directory.
