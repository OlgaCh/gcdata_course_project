The script `run_analysis.R`
- downloads the data from
  [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/index.html)
- merges the training `X_train`, `y_train` and test `X_test`, `y_test` sets to create one data set `merged`
- replaces `activity` values in the dataset with descriptive activity names: "Walking", "Walking upstairs",...
- extracts only the measurements `cx` (features) on the mean and standard deviation
  for each measurement
- appropriately labels the columns with descriptive names
- creates a second, independent `tidy` dataset with an average of each variable
  for each  activity and each subject. The processed tidy data
  set is also exported as csv file `UCI_HAR_tidy.csv`.
  



