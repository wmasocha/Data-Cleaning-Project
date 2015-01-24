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
* Use the folder UCI HAR Dataset as the working directory
* run_analysis.R  must produce a tidy data set named tidydata.txt and a final one called tidydataMEAN.txt save them in the folder UCI HAR Dataset

* run_analysis.R is generated in:
    * R version 3.1.2 (2014-10-31) -- "Pumpkin Helmet"
    * Platform: x86_64-w64-mingw32/x64 (64-bit)

* run_analysis.R installs and depends on the r packages:
    *  plyr  and 
    *  reshape2.
 
