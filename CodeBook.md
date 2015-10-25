#Code Book
This file describe the code inside run_analysis.R

Before run the program download data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

The program splitted in some sections:

1. load data and merge data 
2. Extracts the measurements on the mean and standard
3. Use descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names. 
5. Create a independent tidy data set with the average of each variable for each activity and each subject.

#1. load data and merge data 
Merges the training and the test sets to create one data set using funcation read.table

#2. Extracts the measurements on the mean and standard
Extracts the measurements on the mean and standard deviation for each measurement  

#3. Use descriptive activity names to name the activities in the data set
Uses descriptive activity names to name the activities in the data set

#4. Appropriately labels the data set with descriptive activity names. 
Appropriately labels the data set with descriptive variable names. 

#5. Create a independent tidy data set with the average of each variable for each activity and each subject.
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

