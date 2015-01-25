# Data-Cleaning-Project
## Files in Data-Cleaning-Project repo
* README.md - describes how the script works 
* run_analysis.R - script for performing the analysis,
* CodeBook.md - a code book that describes the variables, the data, and any transformations or work performed to clean up the data called  

## run_analysis.R description and aims
Script generated that can prepare tidy data that can be used for later analysis from the data downloaded in the link below
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

run_analysis.R that does the following. 
* Merges the training and the test sets to create one data set.
* Extracts only the measurements on the mean and standard deviation for each measurement. 
* Uses descriptive activity names to name the activities in the data set
* Appropriately labels the data set with descriptive variable names. 
* From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
 
## Steps in project
* Downlowad data  and create a folder "UCI HAR Dataset"
* create a run_analysis.R  and save it in the folder UCI HAR Dataset
* Use the folder data/UCI HAR Dataset as the working directory
* run_analysis.R  must produce two data sets 1. tidy_data.txt from which a second tidy data set named tidy_data_mean.txt will be generated and save them in the folder data

## Steps in run_analysis.R
    * Read activity labels and data column names
    * select only the means and standard deviations for each measurement.
    * Read X_test, y_test,subject_test, X_train, y_train and subject_train data
    * Assign names
    * select only the means and standard deviations for each measurement.
    * Load activity labels and label the data set with descriptive activity names.
    * Merge the training and the test sets to create one data set
    * Apply mean function to dataset using dcast function
    * Create a second, independent tidy data set with the average of each variable for each activity and each subject.
    * Write the data sets in working directory


* run_analysis.R depends on the r packages:
    * plyr   
    * data.table and 
    * reshape2
 
