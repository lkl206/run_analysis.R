# run_analysis.R

1. Reading in the files and merging the training and the test sets to create one data set
   > download and unzip files
   > read training, test, feature and activity files & label appropriately
   > merge all into one set
2. Extracting only the measurements on the mean and standard deviation for each measurement
   > create vector for defining ID, mean and SD
   > subset from merged data
3. Using descriptive activity names to name the activities in the data set
4. Appropriately labeling the data set with descriptive variable names
5. Creating a second, independent tidy data set with the average of each variable for each activity and each subject
   > make 2nd tidy data set w average
   > write.table into txt file
