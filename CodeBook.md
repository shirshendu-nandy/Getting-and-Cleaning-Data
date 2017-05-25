Uses the ""Human Activity Recognition Using Smartphones Dataset"  and applies cleaning and merging techniques in R to produce a tidy data set

# Source datasets utilised:


* 'features.txt': List of all features.

* 'activity_labels.txt': Links the class labels with their activity name.

* 'train/X_train.txt': Training set.

* 'train/y_train.txt': Training labels.

* 'test/X_test.txt': Test set.

* 'test/y_test.txt': Test labels.

* 'train/subject_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30. 

Read the README.txt file in this source datasets to understand the content in the UCI HAR Dataset directory


# Processes:

1. Download and unzip the source file from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
2. Load the source data sets into vectors
3. Assign column names to the vectors
4. Appropriately labels the data set with descriptive variable names
5. Merge the training and the test sets to create one data set
6. Extract only the measurements on the mean and standard deviation for each measurement.
7. Use descriptive activity names to name the activities in the data set
8. Creates a second, independent tidy data set with the average of each variable for each activity and each subject
9. Download the final tidy data set.


# References:


[1] Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. Human Activity Recognition on Smartphones using a Multiclass Hardware-Friendly Support Vector Machine. International Workshop of Ambient Assisted Living (IWAAL 2012). Vitoria-Gasteiz, Spain. Dec 2012

