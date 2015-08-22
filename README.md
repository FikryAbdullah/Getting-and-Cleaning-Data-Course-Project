# Getting-and-Cleaning-Data-Course-Project

This is the course project for the Getting and Cleaning Data Coursera course.
The R script, `run_analysis.R`, does the following:

1. Installed alll relevant packages required (reshape, reshape2 and sos)
2. Download and unzip the dataset if it does not already exist in the working directory
3. Load activity labels + features
4. Extract only the data on mean and standard deviation
5. Load the datasets
6. merge datasets and add labels
7. turn activities & subjects into factors
8. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

The end result shown in the file named `tidy.txt`.
