
The data set that this code book pertains to is located in the TidySet.txt file of this repository.

See the README.md file of this repository for background information on this data set.

The structure of the data set is described in the Data section, its variables are listed in the Variables section, 
and the transformations that were carried out to obtain the data set based on the source data are presented in the 
Transformations section.

Data

The tidy_data.txt data file is a text file, containing space-separated values.

The first row contains the names of the variables, which are listed and described in the Variables section, and the following rows contain the values of these variables




File with R code "run_analysis.R" perform 5 following steps (in accordance assigned task of course work):

Merging the training and the test sets to create one data set.
1.1 Reading files
1.1.1 Reading trainings tables
1.1.2 Reading testing tables
1.1.3 Reading feature vector
1.1.4 Reading activity labels
1.2 Assigning column names
1.3 Merging all data in one set
Extracting only the measurements on the mean and standard deviation for each measurement
2.1 Reading column names
2.2 Create vector for defining ID, mean and standard deviation
2.3 Making nessesary subset from setAllInOne
Using descriptive activity names to name the activities in the data set
Appropriately labeling the data set with descriptive variable names
Creating a second, independent tidy data set with the average of each variable for each activity and each subject
5.1 Making second tidy data set
5.2 Writing second tidy data set in txt file
PS..The code takes for granted all the data is present in the same folder, un-compressed and without names altered.

About variables:
x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.
x_data, y_data and subject_data merge the previous datasets to further analysis.
features contains the correct names for the x_data dataset, which are applied to the column names stored in
