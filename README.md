#Getting and Cleaning Data Course Project 
##Human Activity Recognition Using Smartphones


The goal is to prepare tidy data that can be used for later analysis.

Here are the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones


Create one R script called run_analysis.R that does the following:

1. Merges the training and the test sets to create one data set: 
  + load the X_train.txt and X_test.txt datasets and bind them together into one main dataset.

2. Extracts only the measurements on the mean and standard deviation for each measurement: 
  + the meassurements that were representatives for this analysis were all the Means and StdDev.     Using regular expressions the script selects only the columns containing that data and creates   a subset of the original one.

3. Uses descriptive activity names to name the activities in the data set: 
  + as the original labels were too hard to read, using regular expresions the script changes the   original names for more readable ones using as input the features.txt file. Also, adds to the     beggining the words MeanOf, so the final script can contains more representative names.

4. Appropriately labels the data set with descriptive variable names: 
  + the script pulls out all the activities from the y_train.txt and y_test.txt. After that it       changes the numbers by more understandable names and attach it to the data set in the first      position.

5. From the data set in step 4, creates a second, independent tidy data set with the average of     each variable for each activity and each subject:
  + the scripts adds the subject column from subjects_train.txt and subjects_test.txt. Using the     dplyr package to calculate the average of each variable for each activity and each subject. The   script exports the tidy data to a txt file using function write.table.