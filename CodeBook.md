
## Human Activity Recognition Using Smartphones Data Set 

The starting point for my project was a set of data files containing acceleromoeter and gyroscopic data collected from Samsung phones.

The project which generated the data files is described here:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The specific data I used is found here:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

Attribute Information:

For each record in the dataset it is provided: 
- Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration. 
- Triaxial Angular velocity from the gyroscope. 
- A 561-feature vector with time and frequency domain variables. 
- Its activity label. 
- An identifier of the subject who carried out the experiment.


The test data and the train data from the above referenced project was merged into one set of data values.

The non numeric data was added into the dataset to get the data all in one table. 

Activity code references for activities were replaced by text language.

Text substitutions were done to produce column headings which would be more friendly to users of R.

A subset of the the numeric data was defined for analyzing, focusing on only those columns which described a mean() or std().

The data was then by calculating the mean of all the numeric columns, grouping the data according to the subject who participated in the original study, as well as according to the activity.

 