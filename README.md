
Getting and Cleaning Data - Course Project
==========================================

* This is about getting and cleaning data coursera course.
* R code is used for find the avearge of measurements on the mean and standard deviation for each measurement.
* The included R script, `run_analysis.R`, conducts the following:

   
1.The test and training data files imported in R from files x_train and x_test is first merged using rbind.

2.Then the column names for the variables of the merged table is obtained from file features. 
From this table only the mean and standard deviation measurements are retained.

3.Then the descriptive activity names are added in the file using cbind

4.The variables are then grouped for each subject and each activity.

5. Generate 'Tidy Dataset' that consists of the average (mean) of each variable for each subject and each activity.
   The result is shown in the file `tidy_dataset.txt`.