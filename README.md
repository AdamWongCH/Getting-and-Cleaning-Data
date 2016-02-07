# Getting-and-Cleaning-Data
This repository hosts the R code and documentation files for the Data Science's track course "Getting and Cleaning data", available in coursera

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

The code takes for granted all the data is present in the same folder, un-compressed and without names altered.

CodeBook.md describes the variables, the data, and any transformations or work that was performed to clean up the data.

R script called run_analysis.R is created that does the following.

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names.
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
