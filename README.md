# Getting and Cleaning Data - Course Project
This is the course project for the Getting and Cleaning Data Coursera course. The R script, run_analysis.R, does the following:

1. Downloads the data files into the "./data" directory. If the directory doesn't exist, it will create it and download the files here 
2. Loads the activity and feature info
3. Loads both the training and test datasets. It keeps only those columns which reflect a mean or standard deviation
4. Loads the activity and subject data for each dataset; and merges those columns with the dataset
5. Merges the two corresponding datasets
6. Converts the activity and subject columns into factors
7. Creates a tidy dataset which includes the average (mean) value of each variable for each subject and activity pair.
8. The result when the data is cleaned up and merged is shown in the file tidy.txt.