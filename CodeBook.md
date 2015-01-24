# 3) a code book that describes the variables, the data, 
# and any transformations or work that you performed to clean up the data
# called CodeBook.md. 

## Human Activity Recognition Using Smartphones Data Set 

The starting point for my project was a set of data files containing acceleromoeter and gyroscopic data collected from Samsung phones.


The project which generated the data files is described here:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones


I took the test data and the train data from the above referenced project and merged the two into one set of data values.

I assembled the non numeric data into the dataset to get the data all in one table. 

I leveraged code references for activities to expand the coded activity values into text language.

I made text substitutions to produce column headings which would be more friendly to users of R.

I sliced out a subset of the the numeric data keeping only those column which described a mean() or std().

I then summarized the data by calculating the mean of all the numeric columns, grouping the data according to the subject who participated in the original study, as well as according to the activity.

 