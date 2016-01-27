# Getting and Cleaning Data

## Course Project on cleaning data

Create a script named run_analysis.R that does the following:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Steps to work on this.

1. Download the data and after extration we will have a ```UCI HAR Dataset``` folder.
2. Program R with script name ```run_analysis.R``` and copy it insider folder```UCI HAR Dataset```, make ```UHC HAR Dataset``` working folder.
3. Execute ```source("run_analysis.R")```, It will generate ```tiny_data.txt``` in  working directory.

## Dependencies

```run_analysis.R``` script will load the dependencies automatically.