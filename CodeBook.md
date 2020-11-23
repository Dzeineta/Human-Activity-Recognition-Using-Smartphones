##Data Set Information

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.

## Summary of Data Set
For each record it is provided:

1. An identifier of the subject who carried out the experiment.
    + Integer
2. The activity name:
    + WALKING
    + WALKING_UPSTAIRS
    + WALKING_DOWNSTAIRS
    + SITTING
    + STANDING
    + LAYING
3. The average of each meassurament for each subject and each activity
    + Float

## Variables
The file shows the following meassurements for each subject and each activity:

* MeanOfTimeBodyAccMeanX
* MeanOfTimeBodyAccMeanY
* MeanOfTimeBodyAccMeanZ
* MeanOfTimeBodyAccStdX
* MeanOfTimeBodyAccStdY
* MeanOfTimeBodyAccStdZ
* MeanOfTimeGravityAccMeanX
* MeanOfTimeGravityAccMeanY
* MeanOfTimeGravityAccMeanZ
* MeanOfTimeGravityAccStdX
* MeanOfTimeGravityAccStdY
* MeanOfTimeGravityAccStdZ
* MeanOfTimeBodyAccJerkMeanX
* MeanOfTimeBodyAccJerkMeanY
* MeanOfTimeBodyAccJerkMeanZ
* MeanOfTimeBodyAccJerkStdX
* MeanOfTimeBodyAccJerkStdY
* MeanOfTimeBodyAccJerkStdZ
* MeanOfTimeBodyGyroMeanX
* MeanOfTimeBodyGyroMeanY
* MeanOfTimeBodyGyroMeanZ
* MeanOfTimeBodyGyroStdX
* MeanOfTimeBodyGyroStdY
* MeanOfTimeBodyGyroStdZ
* MeanOfTimeBodyGyroJerkMeanX
* MeanOfTimeBodyGyroJerkMeanY
* MeanOfTimeBodyGyroJerkMeanZ
* MeanOfTimeBodyGyroJerkStdX
* MeanOfTimeBodyGyroJerkStdY
* MeanOfTimeBodyGyroJerkStdZ
* MeanOfTimeBodyAccMagMean
* MeanOfTimeBodyAccMagStd
* MeanOfTimeGravityAccMagMean
* MeanOfTimeGravityAccMagStd
* MeanOfTimeBodyAccJerkMagMean
* MeanOfTimeBodyAccJerkMagStd
* MeanOfTimeBodyGyroMagMean
* MeanOfTimeBodyGyroMagStd
* MeanOfTimeBodyGyroJerkMagMean
* MeanOfTimeBodyGyroJerkMagStd
* MeanOfFrequencyBodyAccMeanX
* MeanOfFrequencyBodyAccMeanY
* MeanOfFrequencyBodyAccMeanZ
* MeanOfFrequencyBodyAccStdX
* MeanOfFrequencyBodyAccStdY
* MeanOfFrequencyBodyAccStdZ
* MeanOfFrequencyBodyAccJerkMeanX
* MeanOfFrequencyBodyAccJerkMeanY
* MeanOfFrequencyBodyAccJerkMeanZ
* MeanOfFrequencyBodyAccJerkStdX
* MeanOfFrequencyBodyAccJerkStdY
* MeanOfFrequencyBodyAccJerkStdZ
* MeanOfFrequencyBodyGyroMeanX
* MeanOfFrequencyBodyGyroMeanY
* MeanOfFrequencyBodyGyroMeanZ
* MeanOfFrequencyBodyGyroStdX
* MeanOfFrequencyBodyGyroStdY
* MeanOfFrequencyBodyGyroStdZ
* MeanOfFrequencyBodyAccMagMean
* MeanOfFrequencyBodyAccMagStd
* MeanOfFrequencyBodyAccJerkMagMean
* MeanOfFrequencyBodyAccJerkMagStd
* MeanOfFrequencyBodyGyroMagMean
* MeanOfFrequencyBodyGyroMagStd
* MeanOfFrequencyBodyGyroJerkMagMean
* MeanOfFrequencyBodyGyroJerkMagStd