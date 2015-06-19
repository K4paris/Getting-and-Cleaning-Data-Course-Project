CodeBook to clean up the data

Data Source
This dataset is derived from the "Human Activity Recognition Using Smartphones Data Set" which was originally made avaiable here: 
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

This code book that describes the variables, the data, and any transformations or work that you performed to clean up the data:
 1.   Merges the training and the test sets to create one data set.
 2.   Extracts only the measurements on the mean and standard deviation for each measurement.
 3.   Uses descriptive activity names to name the activities in the data set.
 4.   Appropriately labels the data set with descriptive activity names. 
 5.   Creates a second, independent tidy data set with the average of each variable for each activity and each subject.
 
 Feature Variables:
 1.  std()  : standard deviation of multiple measurements of the original variables 
 2.  mean() : mean values of multiple measurements of the original variables
 3.  subject_id : identifier, identify each subject
 4.  activity_id : identifier, identifying the activity of each subject
 5.  activity_name : descriptive name of each subject's activity
    
 
